---
layout: page
title: Repositories
permalink: /repositories/
---

# GitHub Repositories

Here are some of my public repositories. Click on a repository to view more details:

<ul>
  {% for repository in site.github.public_repositories %}
    <li><a href="{{ repository.html_url }}">{{ repository.name }}</a>: {{ repository.description }}</li>
  {% endfor %}
</ul>
