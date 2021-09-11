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
                <img src='../assets/images/{{ author.short_name }}.jpg' alt='{{ author.short_name }}' /> 
                <figcaption><strong><a href="{{ author.url }}">{{ author.name }}</a></strong>
                <br> {{ author.position }} </figcaption>
        </figure> 
</li>
{% endfor %}
</ul>

## Join our team

**Undergraduates**: USC undergraduate students interested in working in the lab can email Sahana. We are not accepting new students in Fall 2021. Check back in Spring 2022 for openings. 
