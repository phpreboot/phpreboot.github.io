---
layout: post
title: "Immutable Data Structures in PHP"
date: 2015-09-23 12:00:00
categories: September2015
tags:
  - Concept
author:
    name: Woody Gilk
    twitter: shadowhand
    github: shadowhand
    url: http://shadowhand.me/immutable-data-structures-in-php/
---

On his blog, Woody Gilk described 'Immutable Data Structure in PHP' and his experiments with them which resulted into a library 'Destrukt'.

> As someone who most often works with PHP I often find myself envious of the more advanced data structures that are present in a language like Python. As an experiment, I decided to see if it would be possible to bring some of those basic structures to PHP while also preserving immutability. The result of this experiment is Destrukt.
>
> ## Why immutable?
>
> Before we talk about the structures themselves, let's talk about immutability for a second. Since PSR-7 decided to implement immutability there has a been a lot of buzz about it in the PHP community. The basic reasoning is this:
> 
> **An immutable object cannot be modified by accident.**
>
> That might seem like a completely obvious statement or too trivial but this comes with a number of interesting "constraints" that help us write better code: