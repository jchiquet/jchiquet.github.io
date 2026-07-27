---
layout: page
title: research
permalink: /research/
description: Funded research projects, past and current
nav: true
nav_order: 2
---

{% for group in site.data.projects %}
<h2 class="category">{{ group.heading }}</h2>

<ul class="list-group list-group-flush">
  {% for entry in group.entries %}
  <li class="list-group-item">
    <div class="row">
      <div class="col-xs-2 col-sm-2 col-md-2 text-center">
        <span class="badge font-weight-bold text-uppercase align-middle" style="min-width: 75px;">{{ entry.dates }}</span>
      </div>
      <div class="col-xs-10 col-sm-10 col-md-10 mt-2 mt-md-0">
        {% if entry.url %}
        <h6 class="title font-weight-bold ml-1 ml-md-4">
          <a href="{{ entry.url }}" target="_blank" rel="external nofollow noopener">{{ entry.title }}</a>
        </h6>
        {% else %}
        <h6 class="title font-weight-bold ml-1 ml-md-4">{{ entry.title }}</h6>
        {% endif %}

        {% if entry.subtitle %}
        <p class="ml-1 ml-md-4" style="font-style: italic;">{{ entry.subtitle }}</p>
        {% endif %}

        <p class="ml-1 ml-md-4" style="font-size: 0.9rem;">
          <strong>{{ entry.funding }}</strong>
          {% if entry.leader %} &middot; Led by {{ entry.leader }}{% endif %}
          {% if entry.partners %} &middot; {{ entry.partners }}{% endif %}
          {% if entry.involvement %} &middot; {{ entry.involvement }}{% endif %}
        </p>

        {% if entry.description %}
        <p class="ml-1 ml-md-4">{{ entry.description }}</p>
        {% endif %}
      </div>
    </div>
  </li>
  {% endfor %}
</ul>
{% endfor %}
