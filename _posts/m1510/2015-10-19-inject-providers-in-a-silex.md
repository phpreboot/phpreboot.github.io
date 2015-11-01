---
layout: post
title: "Alternative way to inject providers in a Silex application"
date: 2015-10-19 12:00:00
categories: October2015
tags:
  - Silex
author:
    name: Gonzalo Ayuso
    twitter: gonzalo123
    url: http://gonzalo123.com/2015/10/19/alternative-way-to-inject-providers-in-a-silex-application/
---

On his blog, Gonzalo Ayuso posted an article introducing an alternate way of injecting providers in a silex.

> I normally use Silex when I need to build one Backend. It’s simple and straightforward to build one API endpoint using this micro framework. But there’s something that I don’t like it: The “array access” way to access to the dependency injection container. I need to remember what kind of object provides my service provider and also my IDE doesn’t help me with autocompletion. OK I can use PHPDoc comments or even create one class that inherits from Silex\Application and use Traits. Normally I’m lazy to do it. Because of that I’ve create this simple service provider to help me to do what I’m looking for. Let me explain it a little bit