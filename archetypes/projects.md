---
date: '{{ .Date }}'
draft: true
slug: '{{ .File.ContentBaseName }}'
tags:
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---
