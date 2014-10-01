---
layout: page
title: Welcome To My Blog!
---
{% include JB/setup %}

Hi! I am John Rey Tadeo Aguilo and I'm a junior software developer in Southern California. 

I am always eager to expand my programming knowledge, and am currently seeking a position as a junior developer. I have worked with a variety of programming languages including:

Languages - Java, C++, C#, Python, Javascript
Frameworks - Android, .Net, Laravel, JQuery

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

