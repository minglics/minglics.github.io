---
title: "News"
layout: archive
permalink: categories/news
author_profile: true
sidebar_main: true
classes: wide
---


{% assign posts = site.categories.News %}

{% for post in posts %} {% include archive-single-category-news-page.html type=page.entries_layout %} {% endfor %}

