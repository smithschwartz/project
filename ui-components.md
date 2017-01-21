---
layout: page
title: UI Components
permalink: /ui-components/

images:
  - image_path: /images/sunset.jpg
    title: Sunset
    link: /sunset

  - image_path: /images/sunset.jpg
    title: Sunset
    link: /sunset

  - image_path: /images/sunset.jpg
    title: Sunset
    link: /sunset
    
  - image_path: /images/sunset.jpg
    title: Sunset
    link: /sunset

  - image_path: /images/sunset.jpg
    title: Sunset
    link: /sunset

  - image_path: /images/sunset.jpg
    title: Sunset
    link: /sunset
---

<ul class="m-gallery">
  {% for image in page.images %}
    <li>
      <a href="{{ image.link }}">
        <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
      </a>
    </li>
  {% endfor %}
</ul>