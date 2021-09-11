---
title: "People"
permalink: "/people/"
layout: page
---


We are researchers in the [Levitt Lab](https://www.chla.org/research/levitt-laboratory) at the Children's Hospital Los Angeles.  

<ul class="list-unstyled list-inline text-center">

{% for author in site.authors %}
<li>
        <figure class="figure">
                <img src='../assets/images/{{ author.short_name }}.jpg' alt='{{ author.short_name }}' height="200" width="200"/> 
                <figcaption><strong><font color="blue"><p style="font-size: 40px">{{ author.name }}</p></font></a></strong>
                <br> <strong>{{ author.studyrole }} </strong><br> {{ author.position }} <br> {{ author.bio }} </figcaption>
        </figure> <br>
        
</li>
{% endfor %}
</ul>

## Join our team

**Undergraduates**: USC undergraduate students interested in working in the lab can email us with their CV. We are not accepting new students in Fall 2021. Check back in Spring 2022 for openings. 
