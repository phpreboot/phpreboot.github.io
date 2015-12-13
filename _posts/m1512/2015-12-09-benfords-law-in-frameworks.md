---
layout: post
title: "Benford's law in frameworks"
date: 2015-12-09 12:00:00
categories: December2015
tags:
  - Statistics
author:
    name: Joshua Thijssen
    twitter: JayTaph
    github: JayTaph
    url: https://www.adayinthelifeof.nl/2015/12/09/benfords-law-in-frameworks/
---

On his blog, Joshua Thijssen posted an interesting post about Benford's Law in PHP Frameworks.

Benford's law, also called the First-Digit Law, is a phenomenological law about the frequency distribution of leading digits in many (but not all) real-life sets of numerical data. ... For example, in sets which obey the law the number 1 would appear as the most significant digit about 30% of the time, while larger digits would occur in that position less frequently: 9 would appear less than 5% of the time. --Wikipedia

> In a new talk I’m currently presenting at conferences and meetups, I talk - amongst other things - about Benford’s law. This law states that in natural occurring numbers, the first digit of those numbers will most often start with a 1 (around 30% of the time), and logarithmically drops down to the number 9, which occurs only 5% of the time. This might sound strange: why would a number that starts with 1, (like 1, 16, 152 or even 152533), be more common than 2,25, 266, or even the lesser common 6, 63, 6474 etc? And although there are some explanations, a definitive one still isn’t there.
>
> But Benford works! Think of something regarding numbers, and you’ll find that most likely it will follow Benford’s law. For instance, on the wikipedia page, they use the example of the 60 largest structures made, and they find that they follow Benford’s law, even if you measure the heights in feet or meters. But some goes for measuring lengths of rivers, population counts in countries, and most likely, the sizes of national parks in the US (haven’t tried it though).