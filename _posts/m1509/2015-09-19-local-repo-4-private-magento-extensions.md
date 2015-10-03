---
layout: post
title: "Using local repositories to easily install private Magento extensions with Composer"
date: 2015-09-19 12:00:00
categories: September2015
tags:
  - Magento
  - Tools
author:
    name: Barry Vd. Heuvel
    twitter: barryvdh
    url: https://medium.com/@barryvdh/using-local-repositories-to-easily-install-private-magento-extensions-with-composer-7eb966dec23e
---

On medium.com, Barry Vd Heuvel posted new article, defining how to use new composer feature of local repository, to easily install private magento extensions. Although he took example of Magento, this can be utilized on any PHP project.

> There are a few ways to handle Magento extensions, for example:
>
> - Magento Connect
> - Copying files in the Magento directory
> - Use Composer (with composer-installer)
>
> I’m a fan of using Composer (in- and outside Magento), so I like to use that option. This works great for free packages listed on Magento connect or Firegento Packages, because you can just require the packages and run composer update.