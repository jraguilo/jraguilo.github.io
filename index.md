---
layout: page
title: Welcome To My Site!
---
{% include JB/setup %}

Hi! I am John Rey T. Aguilo and I am a junior software developer in Southern California. 

I am always eager to expand my programming knowledge, and am currently seeking a position as a junior developer. I have worked with a variety of programming languages including:

    * Operating Systems: Windows, Unix/Linux, Android
    * Tools: Eclipse, Visual Studio, Git, Mercurial
    * Programming Experience: Java, C/C++, C#, Python, Javascript, jQuery, PHP, HTML5, SQL
    * Frameworks: Laravel PHP, Bootstrap
    
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

