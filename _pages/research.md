---
title: "Research"
layout: archive
permalink: categories/researches
author_profile: true
sidebar_main: true
classes: wide
---


{% assign posts = site.categories.research | reverse %}
{% for post in posts %} 
    {% include archive-project-list.html %} 
{% endfor %}

