---
layout: post
title: "A new type of PHP, part 2: Scalar types"
date: 2015-09-11 12:00:00
categories: September2015
tags:
  - Php7
  - Php-basics
author:
    name: Larry Garfield
    url: http://devzone.zend.com/6622/a-new-type-of-php-part-2-scalar-types/
---

On Zend devzone, Larry Garfield is explaining new features on PHP 7. In this second post of articles, he explained in details about 'Scalar Types'.

> In our last installment, we talked about the benefits of more robust variable typing in PHP 7, and specifically the new support for typed return values.  That is already a big boon to the maintainability of our code, but PHP 7 goes a step further.
> 
> So far, we’ve only talked about typing against classes and interfaces.  We’ve been able to type against those (and arrays) for years.  PHP 7, however, adds the ability to type against scalar values too, such as int, string, and float.
> 
> But wait. In PHP, most primitives are interchangeable.  We can pass “123” to a function that wants an int and trust PHP to do the “right thing”, and vice versa.  So what value do scalar types serve?