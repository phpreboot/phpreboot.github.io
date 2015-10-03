---
layout: post
title: "Slim 3: Replacing Pimple with Aura.Di"
date: 2015-09-26 12:00:00
categories: September2015
tags:
  - SlimFramework
  - Aura
  - Pimple
author:
    name: Shameer
    twitter: shameerc
    github: shameerc
    url: http://blog.shameerc.com/2015/09/slim-3-replacing-pimple-with-auradi
---

On his blog, Shameer is telling how to replace Slim Framework's default DI container 'Pimple' with Aura's Aura.di

> Slim framework is my go-to micro framework for all small projects because of it's simplicity and easiness to use. The new version of this cool framework is just around the corner and they have released RC-1 a few days back. Slim 3 have some very good features that makes it more flexible and easy to use. Support for PSR-7 and Dependency Container are the two really interesting features in the new version.
> 
> Slim 3 has a default DI Container that extends Pimple. Pimple is quite simple and often people tend to use it as a service locator than a DI Container. You will set the services in the container and will pass the di container around the application to get the services in different classes. This idea is not always good for several reasons.