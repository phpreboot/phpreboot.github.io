---
layout: post
title: "Composer Install in CI"
date: 2015-09-28 12:00:00
categories: September2015
tags:
  - Concept
  - Composer
author:
    name: Marc Morera
    twitter: mmoreram
    github: mmoreram
    url: http://mmoreram.com/blog/2015/09/28/composer-install-in-ci/
---

On his blog, Mark Morera posted an article describing side effects of using 'composer install' command in CI server.

> If you have a project with a lot of dependencies, then you might now what I am talking about. We all love composer, but we all know as well that, at least with current PHP versions, some composer.json are very heavy to compute and fulfill. All this problems are reduced to time, and some CI engines, like Travis, only allow a finite number of seconds (in Travis case, 20 minutes).