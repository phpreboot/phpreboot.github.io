---
layout: post
title: "Using Composer with shared hosting"
date: 2015-12-28 12:00:00
categories: December2015
tags:
  - Views
author:
    name: Rob Allen
    twitter: akrabat
    github: akrabat
    url: https://akrabat.com/using-composer-with-shared-hosting/
---

On his blog, Rob Allen is suggesting how to use composer on shared hosting without ssh access.

> I can't use Composer because I'm using shared hosting and don't have SSH
> 
> I've seen this sentiment a few times now, so this seems like a good time to point out that you do not need SSH access to your server in order to use Composer. In fact, I don't run Composer on a live server (regardless of whether it's using shared hosting) and it's not on my list of things to do in the near future.
>
> In my view, you have two choices: commit your Composer dependencies directly to your project or write a build script that runs Composer for you and uploads the resulting files.