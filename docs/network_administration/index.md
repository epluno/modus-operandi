---
layout: page
title: Network Administration
permalink: /network-administration/
has_children: false
---

# Network Administration

## Office Internet Access

### Wireless Networks

- epluno5G

- ePI Lyons Secure 

## Communication

We utilize email, [Discord](http://discord.com/), and [Click Up](https://clickup.com/) for communication. See [Communication]({{ site.baseurl }}/communication/) for more details and procedures.

## Data Storage

### Project Repositories

Project repositories are stored on [GitHub](https://github.com/orgs/epluno/dashboard) and [GitLab](https://gitlab.com/epluno). Its important to push all projects you're working on to the remote repositories for shared access and so its backed up. 

### General

Documents, images, and other files are stored on shared Google Drives. By keeping files on google drive it allows shared access and its backed up.

## Authentication

We use SSH keys for authentication for server access and github repositories.

- SSH keys are very secure and prevent vulnerabilities from poor or reused passwords.
- By only using SSH keys, we ensure only apporved devices have access.
- Using SSH keys is more convienet because you don't have to enter your password every time you login.

## Docker Integration

Allows multiple micro services to run side by side. If one component stops working, the others will not be affected.

## Server Configuration

### Master-Slave

When the master server reaches its max load or performance is hindered, it will direct requests to the secondary server to balance the load.

## Database Redundancies

In the case that the database goes down, there are redundancies so that our services can continue to operate.

