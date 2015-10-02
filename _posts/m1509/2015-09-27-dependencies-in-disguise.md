---
layout: post
title: "Dependencies in Disguise"
date: 2015-09-27 12:00:00
categories: September2015
tags:
  - Concept
author:
    name: Stefan Priebsch
    twitter: spriebsch
    url: https://thephp.cc/news/2015/09/dependencies-in-disguise
---

On thephp.cc, Stefan Priebsch posted an article describing dependency injection in details. This post is based on his workshop during Bulgaria PHP conference.

> Yesterday I gave a presentation at the Bulgaria PHP Conference (a great event, by the way).
>
> These days, we all know that dependency injection is a best practice that we should use whenever an object has a collaborator. Instead of creating it in place (where we would have to deal with its dependencies), we use dependency injection:
> 
> We delegate the problem of creating the collaborator to somewhere else. This means that we will not have to deal with creating the collaborating object or its dependencies. ...