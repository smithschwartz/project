---
layout: detail
title: Work
permalink: /work/
---

<div class="m-work m-body">
  <div class="m-detail--container">
  {% for post in site.posts %}
    <div class="m-work--card">
      <a href="{{ post.url }}">
        <div class="m-work--image-container">
          <img class="m-work--card-image" src="{{ post.image_path }}" alt="{{ image.title}}"/>
        </div>
      </a>
      <a class="m-work--details" href="{{ post.url }}">
        <div class="m-work--card-date">{{ post.date | date_to_long_string }}</div>
        <h2 class="m-work--card-title">{{ post.title }}</h2>
        <div class="m-work--card-dek">{{ post.dek }}</div>
      </a>
    </div>
  {% endfor %}
  </div>
</div>