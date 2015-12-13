---
layout: post
title: "Weird PHP error output bug"
date: 2015-12-10 12:00:00
categories: December2015
tags:
  - Php-basics
author:
    name: Leonid Mamchenkov
    twitter: mamchenkov
    github: mamchenkov
    url: http://mamchenkov.net/wordpress/2015/12/10/weird-php-error-output-bug/
---

On his blog, Leonid Mamchenkov posted about 'A PHP Error Output Bug' that he recently encountered.

He later found that PHP 'missing file' error is not showing correctly for his error_log and disply_errors settings.

> We came across this PHP bug at work today.  But before you go and read it, let me show you a use case.  See, if you can spot the problem.
>
> After a rather lengthy troubleshooting session we noticed that the updateProducts.php file was in fact named udpateProducts.php.  A simple typo in the file name.  But shouldn’t that be printed out into the error output?