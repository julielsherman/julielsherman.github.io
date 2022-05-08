---
layout: allposts
title: My Piano Video Lessons
nav-menu: yes
description: null
image: assets/images/tania-miron-Xr9rHbY43Po-unsplash.jpg
author: null
show_tile: yes
---
{% assign sortedcats = site.categories | sort %}

<div class="col-xs-6 col-sm-3 patickaborder">
    <h5>Rubriky</h5>
        <ul>
            {% for category in sortedcats %}
                <li><a href="{{ site.url }}{{ category | first }}/index.html">{{ category | first }}</a></li>
            {% endfor %}
        </ul>
</div>
