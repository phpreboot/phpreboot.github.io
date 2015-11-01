---
layout: post
title: "Flyweight Design Pattern and Immutability: A Perfect Match"
date: 2015-10-21 12:00:00
categories: October2015
tags:
  - Concept
author:
    name: Andrew Carter
    twitter: AndrewCarterUK
    github: AndrewCarterUK
    url: http://www.sitepoint.com/flyweight-design-pattern-immutability-perfect-match/
---

On Sitepoint, Andrew Carter posted about Flyweight design pattern and immutability and how they become perfect match.

> The flyweight pattern is a relatively unknown design pattern in PHP. The fundamental principle behind the flyweight pattern is that memory can be saved by remembering objects after they have been created. Then, if the same objects need to be used again, resources do not have to be wasted recreating them.
>
> You can think of the flyweight pattern as a modification to a conventional object factory. The modification being that rather than just creating new objects all the time, the factory should check to see if it has already created the requested object. If it has, it should return this instance rather than create the object again.