---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
comments: true
draft: true
author: "Yoga"
toc: true
kategori: []
type: post
thumbnail: "/{{ .Name }}/img/thumbnail.webp"
description: "{{ replace .Name "-" " " | title }}"
---

<!--more-->

![{{ .Name }}](/{{ .Name }}/img/thumbnail.webp)
