---
layout: page
permalink: /repositories/
title: code and repos
description: 'Most of my public code is available on my github page. Some selected projects are pinned :pushpin: :star: here.'
nav: true
nav_order: 3
---

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    <div class="repo p-2 text-center">
      <a href="https://github.com/{{ user }}">
        <img class="only-light w-100" alt="{{ user }}" src="{{ '/assets/img/github-stats/stats-' | append: user | append: '-light.svg' | relative_url }}">
        <img class="only-dark w-100" alt="{{ user }}" src="{{ '/assets/img/github-stats/stats-' | append: user | append: '-dark.svg' | relative_url }}">
      </a>
    </div>
  {% endfor %}
</div>
{% endif %}

## Selected GitHub Repositories

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% assign slug = repo | replace: '/', '-' %}
    <div class="repo p-2 text-center">
      <a href="https://github.com/{{ repo }}">
        <img class="only-light w-100" alt="{{ repo }}" src="{{ '/assets/img/github-stats/pin-' | append: slug | append: '-light.svg' | relative_url }}">
        <img class="only-dark w-100" alt="{{ repo }}" src="{{ '/assets/img/github-stats/pin-' | append: slug | append: '-dark.svg' | relative_url }}">
      </a>
    </div>
  {% endfor %}
</div>
{% endif %}

<p class="text-muted" style="font-size: 0.85rem;">
  Cards are static images refreshed weekly by a
  <a href="https://github.com/jchiquet/jchiquet.github.io/blob/master/.github/workflows/github-stats.yml">GitHub Action</a>,
  not fetched live -- so they keep working even when third-party rendering
  services are unavailable.
</p>
