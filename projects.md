---
title: Projects
date: 2015-05-29T22:49:48+00:00
author: Mark
layout: default
guid: https://markswoodprojects.com/projects
---

{% for post in site.categories.Projects %}

- ![{{ post.title }}]({{post.image}})[{{ post.title }}]({{ post.url }})
  {: .project-list}

  {% endfor %}
