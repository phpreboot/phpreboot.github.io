---
layout: post
title: "Drupal 8 Queue API – Powerful Manual and Cron Queueing"
date: 2015-12-11 12:00:00
categories: December2015
tags:
  - Drupal
  - Drupal8
author:
    name: Daniel Sipos
    twitter: drupalexp
    url: http://www.sitepoint.com/drupal-8-queue-api-powerful-manual-and-cron-queueing/
---

On Sitepoint, Saniel Sipos posted an article describing Drupal 8 Aueue API. In the article, he presented two simple example of triggering queue througn cron and manually.

> The Queue API in Drupal allows us to handle a number of tasks at a later stage. What this means is that we can place items into a queue which will run some time in the future and process each individual item at that point and at least once. Usually, this happens on CRON runs, and Drupal 8 allows for a quick set up for cronjob based queues. It doesn’t necessarily have to be CRON, however.
> 
> In this article, we will look at using the Queue API in Drupal 8 by exploring two simple examples. The first will see the queue triggered by Cron while the second will allow us to manually do so ourselves. However, the actual processing will be handled by a similar worker. If you want to follow along, clone this git repository where you can find the npq module we will write in this article.