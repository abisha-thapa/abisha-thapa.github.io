---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in **AI in Education** at the University of Memphis, where I research the intersection of artificial intelligence and learning sciences. My work focuses on **large language models (LLMs)**, **transformer-based architectures**, and **knowledge tracing** to model and understand student learning behaviors using large-scale educational data.

## Research Interests
- Large Language Models (LLMs) in educational contexts
- Knowledge tracing and student learning modeling
- Transformer architectures for sequential learning data

## Background

Prior to my PhD, I worked as a Software Engineer with experience spanning **healthcare analytics**, **full-stack development**, and **Agile delivery** of data-driven systems. This background informs my approach to building practical, scalable AI solutions for real-world educational settings.

## News

{% for post in site.posts limit:5 %}
- **{{ post.date | date: "%b %Y" }}** — [{{ post.title }}]({{ post.url }})
{% endfor %}
