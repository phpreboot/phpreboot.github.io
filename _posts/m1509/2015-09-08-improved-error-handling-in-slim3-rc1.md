---
layout: post
title:  "Improved error handling in Slim 3 RC1"
date:   2015-09-08 00:00:00
categories: September2015
tags:
  - SlimFramework
author:
    name: Rob Allen
    twitter: akrabat
    github: akrabat
    url: http://akrabat.com/improved-error-handling-in-slim-3/
---
On his blog, Rob Allen describes about improved error handling facility in upcoming Slim framework 3 (RC1)

> From RC1 of Slim 3, we have improved our error handling. We've always had error handling for HTML so that when an exception occurs, you get a nice error page
>
> However, we can do better than this and do it for you. Starting with RC1, Slim will now output JSON (or XML) when an error occurs if the client's Accept header is applcation/json (or application/xml) and it will also provide all the previous exception too. This is much nicer and also works for the two other error handlers: notFound and notAllowed.
