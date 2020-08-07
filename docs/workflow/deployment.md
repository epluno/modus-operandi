---
layout: page
title: Deployment
permalink: /workflow/deployment/
parent: Workflow
---

# Deployment

## CI/CD

Continuous integration puts a great emphasis on testing automation to check that the application is not broken whenever new commits are integrated into the main branch.

Continuous delivery is an extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button.

Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes all stages of your production pipeline is released to your customers. There's no human intervention, and only a failed test will prevent a new change to be deployed to production.

`ref: Atlassian`

### GitLab pipelines

Pipelines are the top-level component of continuous integration, delivery, and deployment.

Pipelines comprise:

- Jobs, which define *what* to do. For example, jobs that compile or test code.

- Stages, which define *when* to run the jobs. For example, stages that run tests after stages that compile the code.

If *all* jobs in a stage succeed, the pipeline moves on to the next stage.

If *any* job in a stage fails, the next stage is not (usually) executed and the pipeline ends early.

In general, pipelines are executed automatically and require no intervention once created. However, there are also times when you can manually interact with a pipeline.

A typical pipeline might consist of four stages, executed in the following order:

- A `build` stage, with a job called `compile`.

- A `test` stage, with two jobs called `test1` and `test2`.

- A `staging` stage, with a job called `deploy-to-stage`.

- A `production` stage, with a job called `deploy-to-prod`.

`ref: GitLab Docs`

### GitHub Actions

GitHub Actions are similar to GitLab pipelines. They makes it easy to automate all your software workflows like building, testing, and deploying your code right from GitHub.

### Command Line Tools

**rsync -** command-line utility for efficiently transferring and synchronizing files between a computer and an external hard drive and across networked computers by comparing the modification times and sizes of files.

**scp** - command-line utility that allows you to securely copy files and directories between two locations

## Flightdeck

Flightdeck is an opinionated starter project for Jekyll that uses modern front-end tooling.

Use the *flightdeck.manifest.js* file to configure build options. It contains tasks such as `browsersync`, `eslint`, `imagemin`, `sass`, `watch`, `webpack`, and `deploy`.

**Usage:**

```
npm install
npm start
```

**Production Build:**

```
npm run build
```

**Deploy:**

```
npm run deploy
```

## Releases

### Semantic Versioning

Having a universal way of versioning the software development projects is the best way to track what is going on with the software as new plugins, addons, libraries and extensions are being built almost everyday.

Semantic Versioning is a 3-component number in the format of **X.Y.Z**, where :

- X stands for a major version.

- Y stands for a minor version.

- Z stands for a patch.