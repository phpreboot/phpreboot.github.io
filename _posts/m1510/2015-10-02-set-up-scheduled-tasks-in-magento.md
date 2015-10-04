---
layout: post
title: "Set Up Scheduled Tasks in Magento"
date: 2015-10-02 12:00:00
categories: October2015
tags:
  - Magento
author:
    name: Sajal soni
    twitter: sajalsoni
    github: sajalsoni
    url: http://code.tutsplus.com/tutorials/set-up-scheduled-tasks-in-magento--cms-23858
---

On Tutsplus, Sajal Soni posted a short tutorial on how to enable scheduled tasks in Magento

> Cron is an important utility which allows you to execute scripts at certain regular intervals. It has become an important aspect for web­-based applications as well. There are lots of ways in which cron is useful to websites, from sending regular newsletter mails to synchronizing the database with third-party systems. You can also use cron to clean up the back­-end storage to improve the overall performance of an application.
>
> Magento supports cron in the core itself, as it does with several other utilities! It allows you to set up scheduled tasks in the module, so that they can run at regular intervals. Magento runs all the cron tasks using the "cron.sh" and "cron.php" files located in the root of the site. So you'll need to make sure that you've set up the system-level cron to run the "cron.sh" file at regular intervals, which eventually triggers the Magento cron system. And finally, Magento gathers all the cron jobs located in the modules, and runs them if needed in that particular cron run.