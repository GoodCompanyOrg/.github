<!--
Title: <type>(<scope>): <subject> [GC-1234]. The Jira key is required in the PR title: it is how the change reaches the release record.
This is the organisation-wide default. A repository with its own .github/pull_request_template.md uses that instead.
-->

## Summary

<!-- What changes and why, in a few lines. A small diagram, call tree or diff sketch beats prose. -->

## Evidence

<!-- Before / after: the test that now passes, command output, screenshot. -->

## Merge Danger

**Door:** <!-- two-way (easy to revert) or one-way (migration, data change, external effect) -->

**Blast Radius:** <!-- who or what breaks if this is wrong -->

### ⚠️ Deploy checklist

<!--
Keep this section LAST: /release-notes copies everything from this heading to the end into the release record.
- [ ] = a task for whoever deploys. [x] = already done: add the date, e.g. "[x] … (2026-10-12)".
Nothing to do? Replace the lists with "None: <why>" (e.g. "None: code only, no config, migration or flag").
Think about: migrations or SQL, config or environment keys, feature flags, package publishing order,
scheduled jobs, reindexes, infrastructure manifests, and anything that must happen in a particular order.
-->

**Beta**

- [ ] 

**Production: pre-deploy**

- [ ] 

**Production: post-deploy**

- [ ] 
