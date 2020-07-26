---
title: "{{ replace .Name "-" " " | title }}"     #文章标题
description: {{ replace .Name "-" " " | title }}
keywords:
    - post
    - blog
date: {{ .Date }}  #文章建立时间
lastmod: {{ .Date }}  #文章最近修改
draft: true     #是否为草稿，false则不是草稿、会发布
slug: {{ replace .Name "-" " " | title }}    #文章别名，用来做永久链接，下方会详细说明
---

