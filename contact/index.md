---
title: 联系我们
nav:
  order: 5
  tooltip: 联系方式
---

# {% include icon.html icon="fa-regular fa-envelope" %}联系我们

如果您对我们团队感兴趣，欢迎联系我们。我们的联系方式在下面给出，请查看。

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="实验室正门"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="办公室走廊"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="东北大学信息楼B栋"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html dark=true %}

{% capture col1 %}
xx老师办公室地址
<br/>
东北大学xx楼x楼xxx
{% endcapture %}

{% capture col2 %}
实验室通讯地址
<br/>
东北大学xxxxxxx
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
