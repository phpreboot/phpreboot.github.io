---
layout: post
title: "Introducing Tombstones for PHP"
date: 2015-09-15 12:00:00
categories: September2015
tags:
  - Tools
author:
    name: Christian Scheb
    twitter: scheb_
    github: scheb
    url: http://www.christianscheb.de/archives/717
---
Christian Scheb, on his blog, introduced his new library, which can help you find dead code in your codebase.

> Earlier this year I took over that project at my new company. A project, that existed for many years and has been continuously growing. My first impression, it was missing some love recently. The repository was cluttered by many files, that could assumed to be dead code. Unfortunately, you never know. Although I felt the urgent need of removing stuff, I was able to keep myself from blindly deleting files and breaking everything ;). The mission was clear: Cleaning up the project, without breaking things.
>
> We started by browsing through the code and removing everything, which was collective agreed to be dead. But sometimes you simply cannot tell, if that piece of code is still in use. Even worse, good old human error can make you delete something, which is still in use. So I had to find a better way to clean the project. Thankfully, there are tools out there, which can help you finding dead pieces of code. phpdcd is such a tool and PHPStorm has built-in code analysis and dead code detection. Both do a quite decent job, but pure static code analysis has its limitations – especially in dynamic languages such as PHP.
>
> ...
>
> ... So I started to implement a library for tombstones on my own, and here it is: Tombstones for PHP. It is split into two packages, scheb/tombstone and scheb/tombstone-analyzer. The first, lightweight one provides the basic functionality, which is required for placing tombstones in the code and logging their invocations. The other one adds report-generation on top of it. I recommend adding that one to the require-dev part of composer.json, since it is most probably not needed in a production environment.
