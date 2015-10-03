---
layout: post
title: "Importing large CVS with PHP using one query"
date: 2015-09-22 12:00:00
categories: September2015
tags:
  - Concept
  - Csv
  - MySQL
author:
    name: Anton Domratchev
    url: http://www.grok-interactive.com/blog/import-large-csv-into-mysql-with-php-part-1/
---

On Gork Interactive blog, Anton Domratchev posted an article showing how to import large CSV files in PHP using single query.

> Importing CSV files into your application can become a problem when the file is really big, > 65,000 rows big. Each row of the file needs to be parsed, converted into an object, and then saved to a database. All of this needs to happen within a 30 second timeout window. It may sound like an impossible task, but there are actually a couple of solutions that can solve this problem. While working on a project at Grok, I was tasked with doing exactly that.
>
> Initially I hoped to save the CSV file to a directory and iterate through it in a single request. I was only able to get through about 1/3 of the file before the request timed out. The second attempt was to upload the file and process it at a later time. I saved the CSV file to a temp directory, used a support class to split the original file, and saved 10,000 row chunks in processing directory. I decided to split the file in order to reduce the margin of error for large files in this case that the import did fail at some point, it would only be a part of the file instead of the entire file.