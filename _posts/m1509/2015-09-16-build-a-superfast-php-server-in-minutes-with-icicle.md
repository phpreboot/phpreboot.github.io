---
layout: post
title: "Build a Superfast PHP Server in Minutes with Icicle"
date: 2015-09-16 12:00:00
categories: September2015
tags:
  - Tools
author:
    name: Christopher Pitt
    twitter: assertchris
    github: assertchris
    url: http://www.sitepoint.com/build-a-superfast-php-server-in-minutes-with-icicle/
---

On Sitepoint, Christopher Pitt posted a tutorial on making fast PHP server using icircle.

> Event-based programming is a strange topic for PHP developers. In a language as procedural; events are little more than function calls. Nothing happens between events, and all meaningful code is still blocking.
>
> Languages like JavaScript show us what PHP could be like if event loops were at the center. Some folks have taken these insights and coded them into event loops and HTTP servers. Today we’re going to create an HTTP server, in PHP. We’ll connect it to Apache to serve static files quickly. Everything else will pass through our PHP HTTP server, based on Icicle.
