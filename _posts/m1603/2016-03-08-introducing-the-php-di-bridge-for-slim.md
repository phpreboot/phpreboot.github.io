---
layout: post
title: "Introducing the PHP-DI bridge for Slim"
date: 2016-03-08 12:00:00
categories: March2016
tags:
  - SlimFramework
  - Concept
author:
    name: Matthieu Napoli
    twitter: matthieunapoli
    url: http://php-di.org/news/18-slim-bridge-released.html
---

Dependency Injection is one of the most talked topics now a days. DI is the way of injecting dependency into code, so that code is configured by external entity, is testable and isolated.

PHP-DI (php-di.org) is a dependency injection container, supposed to make di more simple and practical.

Slim Framework is a PHP micro-framework, which comes with its own container, called Pimple. This article by Matthieu Napoli tells how to use PHP-DI with Slim framework.

> Slim 3 was released 3 months ago and it was significant. It is one of the first frameworks to integrate the latest standards and concepts in its core:
>
> It is very easy to replace the default container (Pimple) with PHP-DI, but today we are releasing a "PHP-DI - Slim" bridge that goes a little further. Read below for an introduction of what's possible with the PHP-DI bridge.
