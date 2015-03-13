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

  {% if site.twitter_username %}
  <li>
    Twitter:
    <a href="https://twitter.com/{{ site.twitter_username }}" target="_blank">
      <span class="username">@{{ site.twitter_username }}</span>
    </a>
  </li>
  {% endif %}

  {% if site.stackoverflow_cv_username %}
  <li>
    StackOverflow:
    <a href="https://careers.stackoverflow.com/{{ site.stackoverflow_cv_username }}" target="_blank">
      <span class="username">{{ site.stackoverflow_cv_username }}</span>
    </a>
  </li>
  {% endif %}
</ul>
