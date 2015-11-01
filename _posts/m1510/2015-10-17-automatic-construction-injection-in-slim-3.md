---
layout: post
title: "Automatic construction injection in Slim 3"
date: 2015-10-17 12:00:00
categories: October2015
tags:
  - SlimFramework
author:
    name: Shameer C
    twitter: shameerc
    github: shameerc
    url: http://blog.shameerc.com/2015/10/automatic-construction-injection-in-slim-3
---

On his personal blog, Shameer posted a new blog plst, describing "Automatic construction injection in Slim 3".

> In the previous blog post we have discussed how to replace the default Pimple Container with Aura.DI in Slim framework 3. Aura.DI gives us more flexibility in terms of managing dependencies. We saw one most useful feature in Aura.DI, Inheritance of contructor parameters, that will help us to avoid repeating common parameters for Controllers and Models. In this article we will see another advantage of the same feature.
> 
> One thing that people often complains about the default Pimple DI implementation in Slim 3 is that, it require us to manually create object of each classes.