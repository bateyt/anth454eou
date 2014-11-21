---
layout: page
title: ANTH 454
tagline: Anthropological History & Theory
---
{% include JB/setup %}


<div style="text-align:center">
<figure>
  <a title="Charles Darwin as an ape. Original artist unknown. Originally published in The Hornet (no longer in publication), and it is very likely for a 20-year-old artist in 1871 to have died before 1939. Public domain via Wikimedia Commons." href="http://commons.wikimedia.org/wiki/File%3AEditorial_cartoon_depicting_Charles_Darwin_as_an_ape_(1871).jpg"><img width="256" alt="Editorial cartoon depicting Charles Darwin as an ape (1871)" src="//upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Editorial_cartoon_depicting_Charles_Darwin_as_an_ape_%281871%29.jpg/256px-Editorial_cartoon_depicting_Charles_Darwin_as_an_ape_%281871%29.jpg"/></a>
  <figcaption>Editorial cartoon depicting Charles Darwin as an ape (1871)</figcaption>
</figure>
</div>

<!--<div style="text-align:center" markdown="1">
![An 1871 cartoon, by an unknown artist, depicting Charles Darwin as an ape; Licensed under Public domain via Wikimedia Commons](../assets/pics/darwin_cartoon.jpg)
</div>-->

# Welcome!

Hello, and welcome to the website for Trey Batey's ANTH 454--Anthropological History and Theory course at Eastern Oregon University. I'm happy to have you in the class. 

<br>
-----

## Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

