---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## 导师/Supervisor

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: professor" %}

## 在读博士生/Doctoral candidate

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: professor" %}

## 在读硕士生/Master's candidate

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: professor" %}

## 博士毕业生/Doctoral graduate

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: professor" %}

## 硕士毕业生/Master's graduate

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: professor" %}


<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!professor$)" %} -->

{% include section.html background="images/background.jpg" dark=true %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
