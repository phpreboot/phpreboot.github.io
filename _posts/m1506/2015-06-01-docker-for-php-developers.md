---
layout: post
title:  "Docker for PHP Developers"
date:   2015-06-01 00:00:00
categories: June2015
tags:
  - Devenv
author:
    name: Josh Lockhart
    twitter: codeguy
    github: codeguy
    url: http://www.newmediacampaigns.com/blog/docker-for-php-developers
---
On newmediacampaigns.com, Josh Lockhart posted a tutorial on Docker. He highlighted some of the problems of vagrant and how docker fixed them with different approach. In the tutorial, he also covered creating your first docker with Nginx, PHP-FPM and MySQL on ubuntu.

> I've used Vagrant to manage local development servers for several years. Vagrant is, according to its official website, a tool to "create and configure light-weight, reproducible, and portable development environments." Basically, Vagrant helps me create and provision virtual machines with unique combinations of software and configuration customized for each of my projects. This approach accomplishes three important things: <br/>
> &nbsp;&nbsp;1. Vagrant isolates project environments to avoid software conflicts.<br/>
> &nbsp;&nbsp;2. Vagrant provides the same software versions for each team member.<br/>
> &nbsp;&nbsp;3. Vagrant builds a local environment that is identical to the production environment.<br/>
> <br/><br/>
> However, Vagrant has one large downside—it implies hardware virtualization. This means each project runs atop a full virtual machine, and each virtual machine has a complete operating system that demands a large overhead in system resources (e.g., CPU, memory, and gigabytes of disk space). I can't tell you how often I have seen this warning message when I have too many concurrent projects: <br/>
> `Your startup disk is almost full.`
