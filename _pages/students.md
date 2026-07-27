---
layout: page
title: students
permalink: /students/
description: past and current graduated students
nav: true
display_categories: ['PhD student (current)', 'PhD student (alumni)', 'Post-Doc']
horizontal: true
---

<div class="projects">
  {% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
    {% for category in page.display_categories %}
      <h2 class="category">{{category}}</h2>
      {% assign categorized_projects = site.projects | where: "category", category %}
      {% assign sorted_projects = categorized_projects | sort: "importance" %}
      <!-- Generate cards for each project -->
      {% if page.horizontal %}
        <div class="container">
          <div class="row row-cols-1 row-cols-md-2">
          {% for project in sorted_projects %}
            {% include projects_horizontal.liquid %}
          {% endfor %}
          </div>
        </div>
      {% else %}
        <div class="grid">
          {% for project in sorted_projects %}
            {% include projects.liquid %}
          {% endfor %}
        </div>
      {% endif %}
    {% endfor %}

  {% else %}
  <!-- Display projects without categories -->
    {% assign sorted_projects = site.projects | sort: "importance" %}
    <!-- Generate cards for each project -->
    {% if page.horizontal %}
      <div class="container">
        <div class="row row-cols-1 row-cols-md-2">
        {% for project in sorted_projects %}
          {% include projects_horizontal.liquid %}
        {% endfor %}
        </div>
      </div>
    {% else %}
      <div class="grid">
        {% for project in sorted_projects %}
          {% include projects.liquid %}
        {% endfor %}
      </div>
    {% endif %}

  {% endif %}

</div>


- [David Baker](https://www6.inra.fr/mia-paris/content/download/4166/39960/version/1/file/CV_complet_Baker.pdf)
- [Édith Lefloch](https://www.linkedin.com/in/edith-le-floch-0b55403a/?originalSubdomain=fr)
