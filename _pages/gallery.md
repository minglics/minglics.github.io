---
title: "Gallery"
layout: archive
caption: "2022"
permalink: categories/gallery
author_profile: true
sidebar_main: true
classes: wide
---

{% assign images = site.categories.gallery %}
{% assign count = 0 %}
{% for post in images %} 
    {% include card.html %} 
    {% assign count = count | plus: 1 %}
{% endfor %}