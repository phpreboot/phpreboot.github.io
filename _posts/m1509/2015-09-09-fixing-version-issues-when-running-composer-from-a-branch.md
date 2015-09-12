---
layout: post
title: "Fixing Version Issues When Running Composer from a Branch"
date: 2015-09-09 12:00:00
categories: September2015
tags:
  - Tools
author:
    name: Matthew Weier O'Phinney
    twitter: mwop
    github: weierophinney
    url: https://mwop.net/blog/2015-09-09-composer-root.html
---

On his blog, Matthew presented how to fix version issue in branches of composer packages.

> For the Zend Framework component repositories, we occasionally need to backport changes to the 2.4 LTS releases. This requires checking out a branch based off the last LTS tag, applying patches (often with edits to translate PHP 5.5 syntax to PHP 5.3), and running tests against PHP 5.3 and 5.4.
>
> Of course, to run the tests, you need the correct set of dependencies installed. If you have any component dependencies, that means running a composer update to ensure that you get the 2.4 versions of those components.
