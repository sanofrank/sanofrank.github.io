---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
period: "{{ dateFormat "2006" now }}"
startDate: {{ dateFormat "2006-01" now}}
endDate:
tags: [""]
category: "portfolio"
---

