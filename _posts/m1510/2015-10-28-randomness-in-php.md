---
layout: post
title: "Randomness in PHP"
date: 2015-10-28 12:00:00
categories: October2015
tags:
  - PHP7
  - Guide
author:
    name: Nicola Pietroluongo
    twitter: niklongstone
    github: niklongstone
    url: http://www.sitepoint.com/randomness-php-feel-lucky/
---

On Sitepoint, Nicola Pietroluongo explained about behavior of random number generators in PHP. He further explained what is 'Cryptographically Secure Pseudorandom Number Generator (CSPRNG)', and PHP7 support for CSPRNG.

> This article analyzes problems related to random number generation used for cryptography purposes. PHP 5 does not provide an easy mechanism for generating cryptographically strong random numbers, while PHP 7 solves this by introducing a couple of CSPRNG functions.
> 
> ## What Is a CSPRNG?
> 
> Quoting Wikipedia, a Cryptographically Secure Pseudorandom Number Generator (CSPRNG) is a pseudo-random number generator (PRNG) with properties that make it suitable for use in cryptography.
> 
> A CSPRNG could be mainly useful for:
> 
> - Key generation (e.g. generation of complicated keys)
> - Creating random passwords for new user accounts
> - Encryption systems