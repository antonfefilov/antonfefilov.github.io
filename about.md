---
layout: page
title: About
permalink: /about/
---

<ul class="social-media-list">
  {% if site.github_username %}
  <li>
    Github:
    <a href="https://github.com/{{ site.github_username }}" target="_blank">
      <span class="username">{{ site.github_username }}</span>
    </a>
  </li>
  {% endif %}

  <li>
    LinkedIn:
    <a href="https://www.linkedin.com/in/anton-fefilov-168807b4/" target="_blank">
      <span class="username">Anton Fefilov</span>
    </a>
  </li>
 
  {% if site.stackoverflow_cv_username %}
  <li>
    StackOverflow:
    <a href="https://careers.stackoverflow.com/{{ site.stackoverflow_cv_username }}" target="_blank">
      <span class="username">{{ site.stackoverflow_cv_username }}</span>
    </a>
  </li>
  {% endif %}
</ul>
