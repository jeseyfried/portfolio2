---
title: Jonathan Seyfried
layout: left-profile
date: 2024-12-02
---


## Jonathan Seyfried

This is another new sentence.


{% include figure.html
  class="center"
  width="30%"
  caption="What a nice view"
  image-path="/assets/images/backgrounds/great-lecture.jpg"
%}

This is yet another sentence.

<iframe
  src="{{ '/assets/pdfs/cats-affective-history.pdf' | relative_url }}"
  width="100%"
  height="800"
  style="border:1px solid #ccc;"
  title="Cats PDF">
</iframe>




{% include figure.html
  class="right"
  width="60%"
  caption="What a nice view"
  image-path="/assets/images/jag-draft-2.jpg"
%}

I am a History PhD Candidate focusing on creating more engaging history through emerging technology. This site is built using GitHub Pages, a free platform for web hosting that gives me full control over my content, files, and style.

{% assign essays = site.pages | where: "homepage", true %}
{% include card-list.html cards = essays %}
