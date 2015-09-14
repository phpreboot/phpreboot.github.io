---
layout: post
title: "My first approach to Zend Expressive"
date: 2015-09-14 12:00:00
categories: September2015
tags:
  - ZendExpressive
author:
    name: Alejandro Celaya
    twitter: acelayaa
    github: acelaya
    url: http://blog.alejandrocelaya.com/2015/09/12/my-first-approach-to-zend-expressive/
---

Zend has recently announced new microframework - 'Zend Expressive'

In his new blog post, Alejandro Celaya is explaining about his experience with Zend Expressive

> One of the trending topics in the PHP world nowadays is the one about microframeworks. It started some years ago with Slim and Silex, but recently it has been an explossion of new microframeworks.
>
> First, Slim's team announced the third version of its own framework, which implemented the psr-7 HTTP standard by taking advantage of the middleware concept. The previos version works with Middleware too, but psr-7 looks to be designed to be used with middleware.
>
> Then, Laravel launched the Lumen project, which is another microframework based on Laravel components, similar to Silex, which is based on Symfony components.
>
> And finally, Zend framework's team launched Zend Expressive, which is similar to Slim 3 in the fact that it works with middleware and psr-7, built on top of zend-stratigility and zend-diactoros.
>
> Recently, after playing with Slim 3 and Zend Expressive, I decided to use the last one to rebuild my website, which used to be a ZF2 application.
>
> ## Why microframeworks
>
> I have said several times that composer has completely changed PHP. Now it is possible to access to any package or component in any application, which is a really big advantage. You don't have to stick to certain framework's implementation if there is another one that you like better.
>
> That's made possible to start working with a framework that doesn't have a solution for everything, and your poroject can still scale thanks to the fact that composer gives you access to almost anything.
