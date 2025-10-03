---
title: Jonathan Seyfried
layout: left-profile
date: 2024-12-02
---


## Jonathan Seyfried

This is a new sentence.

I am a History PhD Candidate focusing on creating more engaging history through emerging technology. This site is built using GitHub Pages, a free platform for web hosting that gives me full control over my content, files, and style.

{% assign essays = site.pages | where: "homepage", true %}
{% include card-list.html cards = essays %}
