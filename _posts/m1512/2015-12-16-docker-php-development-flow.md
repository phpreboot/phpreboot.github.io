---
layout: post
title: "Docker PHP development flow"
date: 2015-12-16 12:00:00
categories: December2015
tags:
  - Devenv
author:
    name: Joeri Verdeyen
    twitter: jverdeyen
    url: http://tech.yappa.be/docker-php-development
---

On Yappa technical blog, Joeri Verdeyan posted an article about their new development environment setup using docker. They listed different options they tried including vagrant and what befefit they find in docker.

Later in article, Joeri listed out all steps to replicate their development environment.

> During a regular work day we work on several PHP projects. Sometimes new projects, but also legacy code which still require earlier versions of PHP. We all work on Macbooks and want to switch quickly and easily between projects. The project requirements vary, the PHP version may be different, or additional services may be required (such as Redis, Elasticsearch, ..).
>
> Unable to mimic the production environment without spending countless hours installing packages on a virtual box for each project.
>
> The next most logical step to us was vagrant. We'd set it up with a set of ansible playbooks and it worked pretty good for some time, but there were issues with high memory usage and building took ages. We did look into packer, but the image sizes would grow too large, and space is somewhat limited.