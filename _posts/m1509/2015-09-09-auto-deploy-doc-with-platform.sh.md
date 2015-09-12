---
layout: post
title: "Auto-deploy Documentation pull request with Platform.sh"
date: 2015-09-09 12:00:00
categories: September2015
tags:
  - Symfony
author:
    name: Ryan Weaver
    twitter: weaverryan
    github: weaverryan
    url: http://symfony.com/blog/how-we-auto-deploy-documentation-pull-requests-with-platform-sh
---

On Symfony blog, Ryan Weaver posted an article on how they automate their document generation process using Platform.sh.

> Symfony's documentation is an open source project with more than 800 contributors. That’s great! But our goal is to always make it easier to contribute and faster to merge in changes. And today, we’ve started doing something really cool to improve our workflow: integration with Platform.sh.
>
> Platform.sh is a hosting solution that provides out-of-the-box continuous deployment for Symfony, Drupal and any other PHP applications. It extends the concept of a Git branch at the infrastructure level. Basically, this means that it’s easy to deploy every branch and/or Pull Request to its own URL.
>
> Symfony's documentation is written in Sphinx (Markdown on steroids) with linking, complex code blocks and more. That gives us a lot of flexibility, but also causes 2 major problems:
> 
> - When someone makes a pull request to the docs, they can't immediately see how it will render.
> - It's tough to review, since it takes too much time for a reviewer to pull down the branch, compile it locally, then open it up in a browser.
