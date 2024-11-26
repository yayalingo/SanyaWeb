---
layout: post
title: Suspicious Process
date: 2024-11-25 15:40:16
description: Suspicious Process Knwon
tags: Widnows
categories: sample-posts
featured: true
---

1. Is it a new or recognized process?
2. IS the name random-looking or very short?
   1. Hacker use random name to prevent SOC search in EDR or SIEM
   2. Use a.exe to a malware
3. is it running from a non-standard path?
   1. Most of Windows binary running from Directory : Windows\System32
      1. most of windows system binary and associate dll locate
   2. How many svchost running, what’s it?
      1. Lots of in Windows, host services
   3. If Hacker want to use svchost to name a malware, have two option
      1. Put it in a ono-standard path(not system32)
      2. Name it similar and put it in right location.
4. Is the parent suspicious?
5. Is the parent-child relationship suspicious?
6. Is it tied to suspicious activity?
7. Base64 encoded command-line options?
