---
layout: post
title: "Custom conditionals with Laravel's Blade Directives"
date: 2015-10-10 12:00:00
categories: October2015
tags:
  - Laravel
  - Laravel5
author:
    name: Matt Stauffer
    twitter: stauffermatt
    url: https://mattstauffer.co/blog/custom-conditionals-with-laravels-blade-directives
---

On his blog, Matt described how to make custom conditionals with Laravel's Blade Directive. He also provided an example where he recently used custom conditionals.

> One of the greatest aspects of Laravel Blade is that it's incredibly easy to handle view partials and control logic. I find myself frequently extracting the contents of a loop out to a Blade partial and then passing just a bit of data into the partial.
>
> But sometimes the repetitive code isn't the view itself, but the conditional logic I'm running.
>
> ## A recent example
>
> I'm writing a quick Laravel app for my physical trainer, and it needs to be multitenant, which means it needs to handle and route visits from myapp.com but also username.myapp.com. The way I'm handling this is that I want to have an App\Context object available globally, which contains knowledge about the application's state.
>
> I have a service provider that binds a new App\Context object to the IOC, and it has knowledge of which URL was used to access it, which helps it know if the user is visiting from a "public" (myapp.com) or "client" (username.myapp.com) context.
>
> So, I find myself writing conditionals all over the place to test whether I'm in a public context or a client context.