---
layout: post
title: "OAuth2 with PHP streams functions"
date: 2016-01-07 12:00:00
categories: January2016
tags:
  - Php-basics
author:
    name: Lorna Jane Mitchell
    twitter: lornajane
    url: http://www.lornajane.net/posts/2016/oauth2-phps-built-streams-functions
---

On her blog, Lorna Jane gave a short tutorial about using PHP's build in stream function for OAuth2.

> Most of the time when I work with APIs from PHP, I use Guzzle - it's awesome and modern and elegant. However some of my work is with legacy platforms and I recently had a situation where we needed to integrate with a API using OAuth2, and launch that integration before the planned platform upgrade from an older version of PHP was expected to complete.
>
> For OAuth2, all I had to be able to do was to send an Authorization header with my web request from PHP. My second-favourite way of making API calls from PHP is to use PHP's stream handling, so I did that. It's not code you see very often but it's super-simple and it works on every PHP platform I've tried so far, so here's an example