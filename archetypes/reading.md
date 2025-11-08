---
author: ""
date: "{{ .Date }}"
draft: true
rating:
slug: "{{ .File.ContentBaseName }}"
tags:
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---

<!--more-->
