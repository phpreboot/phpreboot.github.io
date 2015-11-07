---
layout: post
title: "Analyze the Quality Of Your PHP Code"
date: 2015-10-23 12:00:00
categories: October2015
tags:
  - Tools
author:
    name: Kore Nordmann
    twitter: koredn
    url: https://qafoo.com/blog/076_quality_analyzer.html
---

On Qafoo blog, Kore Nordmann posted about their new and open source code quality analyzer tool. A must look article if you care about your code quality.

> In code reviews we often browse metrics, source code and reported code issues together with our customers. This leads to discussions about the current state of the code and possible improvements. First we used a bunch of shells scripts for that. In a second step we developed a simple PHP (Open Source) application helping us to do the job. Now we did the third step and rewrote that application into a React based client side (Open Source) application. Read on for the reasons and benefits…
>
> There was another reason to do this for quite some time: Continuous Integration (CI). The old software required a PHP backend so that it was hard to calculate the results and display them from your CI solution (Jenkins, …). The new software just consists of some static files you can serve with any webserver (in theory, we did not verify this yet).