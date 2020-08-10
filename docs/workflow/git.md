---
layout: page
title: Git
permalink: /workflow/git/
parent: Workflow
nav_order: 3
---


# Git

## Version Control

We always use source code control. It's like a time machine. We can work in parallel universes of our source code, experimenting without fear of losing work, rolling back if something goes wrong.

Git is an open source source code control system written by Linus Torvalds. It's fast and great for working in branches.

`ref: Thoughtbot Playbook` 

We use GitHub and GitLab for hosting our Git repositories. By using these, our code is always backed up and available for other team members to access.

Commits should be made often with descriptive messages. They should also be pushed to GitHub or GitLab repos often as well in case anything were to happen to your computer.

## Git Flow

Gitflow Workflow defines a strict branching model designed around the project release. This provides a robust framework for managing larger projects. [Atlassian](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) has a great tutorial on the gitflow workflow if you are not familiar with it.

**The overall flow of Gitflow is:**

1. A `develop` branch is created from `master`

1. A `release` branch is created from `develop`

1. `Feature` branches are created from `develop`

1. When a `feature` is complete it is merged into the `develop` branch

1. When the `release` branch is done it is merged into `develop` and `master`

1. If an issue in `master` is detected a `hotfix` branch is created from `master`

1. Once the `hotfix` is complete it is merged to both `develop` and `master`

![img](https://t2232791.p.clickup-attachments.com/t2232791/3f54e324-4773-44d3-8c84-1e676192ba19/Screen%20Shot%202020-07-16%20at%204.02.30%20PM.png)

`ref: Atlassian`