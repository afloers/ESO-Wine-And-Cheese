---
layout: layout
title: "Upcoming ESO Wine & Cheese seminars"
---

<section class="content">

Upcoming Topics
===============

**Fall 2019**
If you want to give a talk in one of the seminars listed below, please contact the current ESO W&C organizers.

We have currently scheduled the following Wine & Cheese seminars:

<ul class="listing">
  {% assign upcoming = (site.posts | where: "category" , "upcoming") %}
  {% for post in upcoming reversed %}
  <li>
  <span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
</section>
