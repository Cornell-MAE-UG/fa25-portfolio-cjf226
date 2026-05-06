---
layout: default
title: Cole Finnan - Portfolio
permalink: /projects/
---

In MAE2250, Introduction to Mechanical Design, we were challenged with creating a mechanical prototype to help combat the issue of the invasive Spotted Lanternfly, a pest that has been ruining crops in northestern US farms for some years now. This project involved identifying a problem, creating a prototype, and iterating upon it until we reached our final prototype. Below, you can view several milestones in our product's design.

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>