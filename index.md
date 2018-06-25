---
title: Home
---

{% include figure.html file="College_of_Education_University_of_Idaho_Workshop_scene_2273.jpg" alt="intro image here" width="75%" %}

<div class="intro" markdown="1>
<h2>{{ site.title }}</h2>
<h4>{{ site.workshop_date }} | {{ site.workshop_location }}</h4>
</div>

As empirical social scientists, we write code. A lot of code. For many of us, this is means writing code in Stata to do all kinds of things. Clean data, manipulate data, analyze data, table data. You get the point. We battle with code. Marathon battles late at night to get our code the run properly. Sometimes we write code, leave it alone for a long time, and come back to it only to be puzzled why we must re-fight the same battles.

Although writing code of all kinds, but particularly in Stata, is common among empirical social scientists in economics, political science, public administration, and other empirical fields, we spend far too little time on teaching ourselves how to write code well. For something so integral to our work processes, the "learn enough code to be dangerous" mentality seems inadequate. This workshop seeks to change that.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
