---
layout: post
title: "Secure PHAR Automation"
date: 2015-12-14 12:00:00
categories: December2015
tags:
  - Guide
author:
    name: Matthew O'Phinney
    twitter: mwop
    github: weierophinney
    url: https://mwop.net/blog/2015-12-14-secure-phar-automation.html
---

On his blog, Mattew O'Phinney is describing how to make secure PHAR Packages. He first start with the fact that there are security concerns with PHAR packages.

Later he describe how to create PHAR packages which are secure.

> For a variety of reasons, I've been working on a utility that is best distributed via PHAR file. As has been noted by others (archive.is link, due to lack of availability of original site), PHAR distribution, while useful, is not without security concerns, and I decided to investigate how to securely create, distribute, and update PHAR utilities as part of this exercise.
>
>This is an account of my journey, as well as concrete steps you can take to secure your own PHAR downloads.