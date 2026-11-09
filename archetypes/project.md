---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
startDate: {{ .Date | time.Format "2006-01-02" }}
endDate:
draft: true
summary: ""
tags: []
skills: []
image: "images/astronaut-cute.png"
projectType: research
---

{{ "{{< project-dates >}}" }}

## Overview
