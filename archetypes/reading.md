---
date: "{{ .Date }}"
draft: false
layout: book
params:
  author: ""
  dateFinished: "{{ .Date }}"
  genres:
  rating: ""
slug: "{{ .File.ContentBaseName }}"
tags: ["reading"]
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---

<!--more-->
