---
layout: post
title: "Custom @requires annotations for PHPUnit"
date: 2015-10-27 12:00:00
categories: October2015
tags:
  - Guide
author:
    name: Matt Stauffer
    twitter: stauffermatt
    url: https://mattstauffer.co/blog/creating-custom-requires-annotations-for-phpunit
---

On his blog, Matt Stauffer posted a tutorial on how to add a custom @require annotation in PHP Unit. He futher explained how he is using custom annotations to exclude some test cases from particular environment like Travis CI.

> I was working on a project this weekend that required skipping certain tests in a particular environment (Travis CI)
> 
> I remembered that there was a @requires annotation in PHPUnit that works natively to allow you to skip a test under a certain version of PHP or with certain extensions disabled, so I set out to write my own custom @requires block.