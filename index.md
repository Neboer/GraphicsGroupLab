---
---

# 东北大学IMCT渲染实验室

渲染组是东北大学IMCT实验室下设的一个科研团队，主要研究方向是……。我们有学生团队x人，获得xx奖项……，我们的科研领域覆盖……等领域，成果有……。

此外，我们的成员们参与开发……，大家的方向涵盖……，主要的贡献有……。

实验室的主要成员是……

{%
  include button.html
  type="docs"
  text="ICMT官网"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="渲染组项目"
  link="greenelab/lab-website-template"
%}

{% include section.html %}

## IMCT渲染组

渲染组是东北大学IMCT实验室下设的一个科研团队，我们有学生团队x人，获得xx奖项……

## 杰出成果

{% capture text %}

我们的成果涵盖……等领域，在……等知名杂志上刊登文章，取得的成果有……，我们的学术工作主要面向……

{%
  include button.html
  link="research"
  text="看看我们发表的论文"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="我们的研究工作"
  text=text
%}

{% capture text %}

我们的研究工作主要覆盖……，涉及……，目前团队的研究方向包含……，合作的企业有……

{%
  include button.html
  link="projects"
  text="看看我们做的项目"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="我们开发的项目"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

渲染组是一支有活力的团队，我们有硕士研究生……位，博士研究生……位，已经毕业的成员大多都在各界活跃，大家在一起其乐融融，好不开心！

{%
  include button.html
  link="team"
  text="打个招呼！"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="我们的团队成员"
  text=text
%}
