---
title: Merge a branch
type: snippet
language: git
tags: [repository,branch]
cover: sparkles
dateModified: 2021-04-13T21:10:59+03:00
---

Merges a branch into the current branch.

- Use `git checkout <target-branch>` to switch to the branch into which you want to merge.
- Use `git merge <source-branch>` to merge a branch into the current branch.

```shell
git checkout <target-branch>
git merge <source-branch>
```

```shell
git checkout master
git merge patch-1 # Merges the `patch-1` branch into `master`
```
