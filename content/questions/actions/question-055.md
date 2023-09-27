---
title: "Question 055"
date: 2023-09-04T11:43:24+02:00
draft: false
subject: []
---

# A workflow was initially run on `commit A` and failed. You fixed the workflow with the subsequent `commit B`. When You re-run that workflow it will run with code from which commit?
> https://docs.github.com/en/actions/managing-workflow-runs/re-running-workflows-and-jobs#about-re-running-workflows-and-jobs
1. [x] It will run with code from `commit A`
1. [ ] It will run with code from `commit B`
> Re-running a workflow uses the same commit SHA and Git ref of the original event that triggered the workflow run.
1. [ ] You cannot re-run workflows in GitHub Actions. You have to trigger a new workflow which will run with latest changes
1. [ ] It will trigger two workflows, one with code from `commit A` and one with code from `commit B`