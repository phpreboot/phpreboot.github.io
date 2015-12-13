---
layout: post
title: "Running Phan against Slim 3"
date: 2015-12-10 12:00:00
categories: December2015
tags:
  - Tools
author:
    name: Rob Allen
    twitter: akrabat
    github: akrabat
    url: https://akrabat.com/running-phan-against-slim-3/
---

On his blog, Rob Allen shows how he run Phan against Slim 3 framework

Phan is a static analyzer for PHP. Some of important features of Phan are:

- Checks for calls and instantiations of undeclared functions, methods, closures and classes
- Checks types of all arguments and return values to/from functions, closures and methods
- Supports `@param`, `@return`, `@var` and `@deprecated` phpdoc comments including union and void/null types
- Checks for Uniform Variable Syntax PHP 5 -> PHP 7 BC breaks
- Undefined variable tracking
- Supports namespaces, traits and variadics
- Generics (from phpdoc hints - int[], string[], UserObject[], etc.)

> Having installed Phan, I decided to use it against the upcoming Slim 3 codebase.
>
> A lot of issues have been found – most of them due to missing dependent classes & interfaces, so I ignored those when working through the list. Next time, I'll add the relevant vendor files to see if that catches anything else.