---
layout: page
title: Development
permalink: /workflow/development/
parent: Workflow
has_children: true
nav_order: 3
---



# Development

## Vision

A development team of software engineers and managers who make our customers happy when using our product(s). Our products should contain broad rich features, high availability, high quality, fast performance, trustworthy security, and reliable operation.

`ref: Thoughtbot Playbook `  ﻿**@Ed Heltzel**﻿ ﻿[Add what you want](https://app.clickup.com/t/a0kgh4)﻿ 

We are working to develop a headless commerce platform.

## Mission

The development department strives to:

- Provide new product requirements

- Resolve of customer issues/bugs

- Fix security problems

- Increase availability, quality, and reliability

- Foster open source community contributions

- Improve user experience

- Foster best agile practices for fast iterations

The department also focuses on career development and process to make this a preferred destination for high performing software engineers.

We use data to make decisions. If data doesn't exist we use anecdotal information. If anecdotal information isn't available we use first principles.

`ref: Thoughtbot Playbook`

## Team Members

The following people are members of the Development Department:

- Ed Heltzel - CTO

- Josh Fischer - Lead Developer

- Andres Archondo - Developer

- Kyle Okolowitz - Intern

## Onboarding

When onboarding new team members, we want to get them up to speed as soon as possible. This documentation can be used to help them get familiar with how we work here at Epluno.

In addition here is a check list of things to do for onboarding a new team member:

- Collect developers information

- Invite them to remote repositories 

  - Github

  - Gitlab

- Shared team goals

- Give them assignments

​	

## Project Management

We use [Click Up](https://clickup.com/) to keep track of to-do tasks, goals, deadlines, notes, support tickets, etc. It helps teams work together, stay productive, organized, and accountable.

For more information on how to use Click Up click [here]({{ site.baseurl }}/workflow/development/click-up/).

## Agile Scrum

**Scrum** is an agile framework for developing, delivering, and sustaining complex products, with an initial emphasis on software development, although it has been used in other fields including research, sales, marketing and advanced technologies. It is designed for teams of ten or fewer members, who break their work into goals that can be completed within time boxed iterations, called *sprints*, no longer than one month and most commonly two weeks. The Scrum Team track progress in 15-minute time-boxed daily meetings, called daily scrums. At the end of the sprint, the team holds sprint review, to demonstrate the work done, and sprint retrospective to continuously improve.

### Stand Up

Daily 15 minute conference call at 10 AM with dev team members to discuss previous days progress, what we are working on today, and any blocks that we had.

### Sprints

A design sprint orients the team and aims our efforts toward a mutual goal. It allows us to invest our time and money wisely by eliminating inherent risk in building products by shortening the product design feedback loop with real world data as a focused group.

![img](https://t2232791.p.clickup-attachments.com/t2232791/abbb6b7a-8477-49a6-9a90-bccc652398bf/image.png)

Epluno's sprints each last 6 weeks long.

At the end of the sprint, the team should have a shared understanding of the problem and have tested assumptions with a prototype. After testing, the team should decide on and document next steps for the product. 

That could mean: 

- Rolling into product design and development 

- Taking learning from the testing and starting a new Design Sprint

- Deciding not to move forward with the product

`ref: Thoughtbot Playbook `

## Coding Style Guide

Within the the project repositories, we keep an editor.config file that specifies the style and formatting to be used.

Code should be well commented and documented! Other and future team members need to be able to understand the code you write so that they can use and update it when you are not around. 

## Tools

Everyone is free to use their own developing environments and machines.

We mainly use [Visual Studio Code](https://code.visualstudio.com/) for our editor. VS Code will automatically style the code according to the editor.config file in the project repositories.

## Code Review

Code review is an important step before we start using developed code in production. Reviews that happen before code goes into `master` offer many benefits:

- The whole team learns about new code as it is written.

- Mistakes are caught earlier.

- Coding standards are more likely to be established, discussed, and followed.

- Feedback from this style of code review is far more likely to be applied.

- No one forgets context ("Why did we write this?") since it's fresh in the author's mind.

**Basic Development Process:**

1. Create a local feature branch based off master.
2. When feature is complete and tests pass, stage the changes.
3. When you've staged the changes, commit them.
4. Write a good commit message.
5. Share your branch.
6. Submit a GitHub pull request.
7. Ask for a code review in Discord.
8. A team member other than the author reviews the pull request. 
9. They make comments and ask questions directly on lines of code in the GitHub web interface or in Discord.
10. When satisfied, they approve or comment on the pull request that it's ready to merge.
11. Rebase interactively. Squash commits like "Fix whitespace" into one or a small number of valuable commit(s). Edit commit messages to reveal intent.
12. View a list of new commits. View changed files. Merge branch into master.
13. Delete your remote feature branch.
14. Delete your local feature branch.

`ref: Thoughtbot Playbook`

Click [here]({{ site.baseurl }}/workflow/development/code-review/) for more information about code reviews.

## Freelance Friday

Technology is constantly changing, being updated, and improving. Therefore it is important that we are staying current with these changes and learning about new things. 

On Fridays, you are free to spend some time learning and working on non work related projects.