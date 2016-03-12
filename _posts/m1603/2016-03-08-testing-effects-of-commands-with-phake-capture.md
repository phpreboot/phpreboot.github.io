---
layout: post
title: "Testing Effects of Commands With Phake::capture()"
date: 2016-03-08 12:00:00
categories: March2016
tags:
  - Testing
  - Library
author:
    name: Benjamin Eberlei
    twitter: beberlei
    url: https://qafoo.com/blog/078_phake_capture.html
---

On Qafoo blog, Benjamin Eberlei posted a nice quick tutorial on using Phake (Mocking framework) to test a method which do not return anything.

He has taken an example of checkout, where code is saving an order but not return anything. Later he demonstrated with code how phake can test such code.

> Testing becomes harder when you are using command / query separation in your code and service operations don't return values anymore. If your command method creates objects and passes them down the stack, then you usually want to make assertions on the nature of the changes.