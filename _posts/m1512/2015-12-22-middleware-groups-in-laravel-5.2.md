---
layout: post
title: "Middleware groups in Laravel 5.2"
date: 2015-12-22 12:00:00
categories: December2015
tags:
  - Laravel
  - Laravel5
author:
    name: Matt Stauffer
    twitter: stauffermatt
    url: https://mattstauffer.co/blog/middleware-groups-in-laravel-5-2
---

On his personal blog, Matt Stauffer started a new series on `New features in Laravel 5.2`. In the last article of the series, he is talking about `Middleware groups in Laravel 5.2`.

> When you are creating a site of any significant size in Laravel, your routes file will often get pretty large. One of the first things I do in a new site is group my routes by logically distinct sections like "admin", "auth", "public". Usually each of these groups get their own set of middleware—admin, for example, gets auth. Maybe the API group gets a different auth middleware, and it might get an API-specific rate limiter or something else.
> 
> Laravel 5.2 has introduced something called middleware groups, which are essentially a shortcut to applying a larger group of middleware, using a single key.