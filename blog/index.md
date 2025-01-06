---
title: 博客
nav:
  order: 4
  tooltip: 工作记录、进展追踪
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}博客

这里记录了渲染组相关的工作、活动等事宜，也记录了相关的通知和公告等等内容。

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
