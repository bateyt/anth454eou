---
layout: page
title: ANTH 454
tagline: Anthropological History & Theory
---
{% include JB/setup %}

# Welcome!

Hello, and welcome to the website for my ANTH 454 class at Easter Oregon University. What's this course about? Well, the official description in the EOU Course Catalog (2014-2015) is as follows:

> Senior level seminar examining the development of anthropological ideas and concepts. Includes key theories and individuals in the past, as well as important contemporary themes and issues in cultural anthropology, and the other subdisciplines. 

<br>
-----

## Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

