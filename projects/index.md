---
title: 项目
nav:
  order: 2
  tooltip: 开发的软件系统等
---

# {% include icon.html icon="fa-solid fa-wrench" %}项目

IMCT渲染组实验室的项目主要有……等。我们和……等企业积极合作，共同开发的项目有……等。

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## 科研项目

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## 合作项目

{% include list.html component="card" data="projects" filter="!group" style="small" %}
