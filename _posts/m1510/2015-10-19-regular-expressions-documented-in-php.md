---
layout: post
title: "Regular expressions documented in PHP"
date: 2015-10-19 12:00:00
categories: October2015
tags:
  - Concept
author:
    name: Ignace Nyamagana Butera
    twitter: nyamsprod
    github: nyamsprod
    url: http://nyamsprod.com/blog/2015/regular-expressions-documented-in-php/
---

On his blog, Ignace Nyamagana Butera wrote a blogpost describing how to document complex regular expressions in you code

> One of the most challenging aspect of using regular expressions is documenting them. More than often you end up with a complex expression that even you as a creator have a hard time documenting. While reading sitepoint recent article around regular expressions I was intrigued that this article did not feature any tips on how to document them.  So let’s take a very complex regular expression and see how we could improve its documentation.
>
> For the purpose of this article we will look at RFC3986 regular expression used to parse any given URI into its main parts. When adapted to be used in PHP you end up with the following code