---
layout: post
title: "Implicit route model binding in Laravel 5.2"
date: 2015-12-18 12:00:00
categories: December2015
tags:
  - Laravel
  - Laravel5
author:
    name: Matt Stauffer
    twitter: stauffermatt
    url: https://mattstauffer.co/blog/implicit-model-binding-in-laravel-5-2
---

On his personal blog, Matt Stauffer started a new series on `New features in Laravel 5.2`. In the second article of the series, he is talking about `Implicit route model binding in Laravel 5.2`.

> In Laravel 5.2, it's even easier to use route model binding. Just typehint a parameter in the route Closure (or your controller method) and name the parameter the same thing as the route parameter, and it'll automatically treat it as a route model binding.
>
> That means you can now get the benefits of route model binding without having to define anything in the Route Service Provider. Easy!