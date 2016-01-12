---
layout: post
title: "The internal pointer of an array"
date: 2016-01-12 12:00:00
categories: January2016
tags:
  - PHP7
author:
    name: Rob Allen
    twitter: akrabat
    github: akrabat
    url: https://akrabat.com/the-internal-pointer-of-an-array/
---

On his blog, Rob Allen is describing difference between foreach behavior on PHP 5 and PHP 7.

> I discovered recently that if you walk through an array using array_walk or array_walk_recursive, then the array's internal pointer is left at the end of the array. Clearly this isn't something that I've needed to know before!