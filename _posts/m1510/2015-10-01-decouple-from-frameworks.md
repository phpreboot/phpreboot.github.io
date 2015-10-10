---
layout: post
title: "Decouple from Frameworks"
date: 2015-10-01 12:00:00
categories: October2015
tags:
  - Concept
author:
    name: Decouple from Frameworks
    twitter: epiloic
    github: gnugat
    url: http://gnugat.github.io/2015/09/30/decouple-from-frameworks.html
---

On his blog, Loic described how to decouple your project from frameworks. He took example of PSR-7 forcing synfony to break backward compatibility, which have severy impact on real projects.

> Frameworks solve infrastructure problems, for example how to create a HTTP or CLI application. While necessary, those concerns don't add any value to your project: the business need will not be fulfilled by creating an empty application.
> 
> As always, different responsibilities mean also different reasons to change: frameworks have a history of Backward Compatibility (BC) breaks and they do so regardless of your project.
>
> Take for example Symfony: it only started to follow Semantic Versioning from version 2.3. The upgrade to version 3 has been made easier by allowing developers to know what was deprecated, but the removal of those features still means a lot of work in your application. The arrival of the new standard PSR-7 brings a lot of questions on the future of Symfony: for now it allows to choose between symfony/http-foundation and psr/http-message, but if Symfony doesn't want to fall back behind (Zend 3 is fully based on PSR-7) it might have to introduce another big BC break (event listeners with the Request and Response are not possible the way they are now with PSR-7).