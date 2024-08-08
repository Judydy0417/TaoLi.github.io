---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<nav>
  <ul>
    {% for link in site.data.navigation.main %}
      <li>
        <a href="{{ link.url }}" {% if link.download %} download {% endif %}>
          {{ link.title }}
        </a>
      </li>
    {% endfor %}
  </ul>
</nav>
