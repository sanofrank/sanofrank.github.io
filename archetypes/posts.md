---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
period: "{{ dateFormat "2006" now }}"
tags: [""]
category: "post"
---

