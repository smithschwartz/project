---
layout: detail
title: Work
permalink: /work/

<!-- images:
  - image_path: /images/visual-design/eudie-bday.jpg
    title: Birthday Invite

  - image_path: /images/visual-design/owl-rat.jpg
    title: Owl Rat
    link: /owl-rat

  - image_path: /images/visual-design/GADG_invitation.jpg
    title: Give A Day Global Fundraiser Invitation
    link: /fundraiser-invite
    
  - image_path: /images/visual-design/newsletter-icon-toaster.png
    title: Newsletter
    link: /newsletter-icon

  - image_path: /images/visual-design/sunset.jpg
    title: Sunset
    link: /sunset

  - image_path: /images/visual-design/sunset.jpg
    title: Sunset
    link: /sunset -->
---

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.title }}
      <a href="{{ post.url }}">
        <img src="{{ post.image_path }}" alt="{{ image.title}}"/>
      </a>
    </li>
  {% endfor %}
</ul>