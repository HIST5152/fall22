---
layout: home
title: Home
nav_exclude: false
nav_order: 1
permalink: index.html
seo:
  type: Course
  name: Digital History at Temple University
---

# {{ site.tagline }} 💾
 {{ site.description }}


Welcome! 👋

{{ site.staffers }}

## About this site
This will be the primary location for all class-related materials throughout the Fall 2022 semester. The URL is [https://hist5152.github.io/fall22/](https://hist5152.github.io/fall22/). **Be sure to bookmark it!** 

- Find your assignments, readings, and deadlines on the [schedule](/fall22/schedule)!

- Course information, including policies and grading guidelines, are on the [syllabus](/fall22/syllabus)!

- Book times to talk with me via my [calendar](https://outlook.office.com/bookwithme/user/d08776f14406497083a3078045380be8@temple.edu?anonymous&ep=plink)!


Grading and attendance will be recorded via the course Canvas instance.

## Schedule {#schedule}
{% for module in site.modules %} {{ module }} {% endfor %}
