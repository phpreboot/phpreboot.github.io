---
layout: post
title: "Configuration Values Are Dependencies, Too"
date: 2015-12-08 12:00:00
categories: December2015
tags:
  - Concept
author:
    name: Paul M Jones
    twitter: pmjones
    url: http://paul-m-jones.com/archives/6203
---

On his blog, Paul M Jones suggest configurations of application are also dependencies, not just library and classes.

> As part of my consulting work, I get the opportunity to review lots of different codebases of varying modernity. One thing I’ve noticed with some otherwise-modern codebases is that they often “reach out” from inside a class to retrieve configuration values, instead of injecting those values into the class from the outside. That is, they use an equivalent of globals or service-location to read configuration, instead of using dependency injection.