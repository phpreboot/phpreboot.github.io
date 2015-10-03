---
layout: post
title: "Environment specific configuration using PHPDotEnv"
date: 2015-09-24 12:00:00
categories: September2015
tags:
  - Guide
author:
    name: Matt Stauffer
    twitter: stauffermatt
    url: https://mattstauffer.co/blog/environment-specific-configuration-for-craftcms-using-phpdotenv
---
On his blog, Matt Stauffer posted a nice article on using PHPDotEnv to set environment specific configurations.
He had taken an example of CraftCMS but concept he present applies on most cases.

> Craft is a fantastic CMS, but every CMS shows some pain points when you have a large team working on the same site at the same time. One of these points for me is Craft's native multi-environment configuration options, which allow you to define configuration options based on the domain name:
>
> This is great, but it's limited: You're hard-coding the configuration details into your code, which sometimes means putting sensitive information into your version control. Every developer's local installs either all have to have different domains, or if they use the same domain they need to all have the same configuration settings. And something just feels dirty about the codebase having such knowledge of every place it's going to be deployed.
>
> ## A better way
>
> I've fallen in love with how easy dotenv and phpdotenv make it to keep particular variables (e.g. database connection information) unique for each environment (local, staging, production, etc.) without committing them all to version control (e.g. GitHub).
