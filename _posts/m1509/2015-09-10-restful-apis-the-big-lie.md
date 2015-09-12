---
layout: post
title:  "RESTful APIs, the big lie"
date:   2015-09-10 00:00:00
categories: September2015
tags:
  - Views
author:
    name: Michael S. Mikowski
    twitter: z_mikowski
    github: mmikowski
    url: http://mmikowski.github.io/the_lie/
---
On his github blog, Michael Mikowski suggests that RESTful API is a big lie and should be replaced by something he names as 'JSON-pure API'.

> If you have read an internet developer resume or job posting in the past 10 years, then you might be forgiven if you think that RESTful APIs are gifts bestowed from the heavens by The One True Web Developer Deity. RESTful APIs are everywhere. Even the marketing folks are pushing them in sales material intended for CEOs and Human Resources-type folks.

The problems he mentioned were:

> - Problem #1: There is little agreement on what a RESTful API is
> - Problem #2: The REST vocabulary is not fully supported
> - Problem #3: The REST vocabulary is not rich enough for APIs
> - Problem #4: RESTful APIs are very hard to debug
> - Problem #5: RESTful APIs are usually tied to HTTP

He further suggest JSON-Pure API is solution

> JSON-Pure APIs fix most of the problem we've just discussed.
>
> - They use just one transmission method to send a request - typically POST for HTTP or a send for WebSockets.
> - They completely separate the request content from the transmission mechanism. All errors, warnings, and data are placed in the JSON request payload.
> - They use only one response code to confirm proper receipt of a message - typically 200 OK for HTTP.
> - They completely separate the response content from the transmission mechanism. All errors, warnings, and data are placed in the JSON response payload.
> - They are easy to debug since transaction information is found in easy-to-read JSON inside the payloads using a single, domain specific vocabulary.
> - They can easily be moved or shared between transmission channels such as HTTP/S, WebSockets, XMPP, telnet, SFTP, SCP, or SSH.

Follow original URL to learn more about his article.
