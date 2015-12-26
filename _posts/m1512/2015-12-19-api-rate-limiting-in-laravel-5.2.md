---
layout: post
title: "API rate limiting in Laravel 5.2"
date: 2015-12-19 12:00:00
categories: December2015
tags:
  - Laravel
  - Laravel5
author:
    name: Matt Stauffer
    twitter: stauffermatt
    url: https://mattstauffer.co/blog/api-rate-limiting-in-laravel-5-2
---

On his personal blog, Matt Stauffer started a new series on `New features in Laravel 5.2`. In the third article of the series, he is talking about `API rate limiting in Laravel 5.2`.

> If you're not familiar with it, rate limiting is a tool—most often used in APIs—that limits the rate at which any individual requester can make requests.
>
> That means, for example, if some bot is hitting a particularly expensive API route a thousand times a minute, your application won't crash, because after the nth try, they will instead get a 429: Too Many Attempts. response back from the server.
>
> Usually a well-written application that implements rate limiting will also pass back three headers that might not be on another application: X-RateLimit-Limit, X-RateLimit-Remaining, and Retry-After (you'll only get Retry-After if you've hit the limit). X-RateLimit-Limit tells you the max number of requests you're allowed to make within this application's time period, X-RateLimit-Remaining tells you how many requests you have left within this current time period, and Retry-After tells you how many seconds to wait until you try again. (Retry-After could also be a date instead of a number of seconds).