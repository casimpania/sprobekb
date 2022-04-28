---
title: "Git Latest Hash"
date: 2022-03-27T23:17:11+08:00
tags: [git]
draft: false
---

Sometimes, for automation purposes, you would like to get the latest commit in a working copy.

Below is how you do it.
```
~$ git rev-parse --short HEAD
```

Remove the `--short HEAD` if you need the longer version.