---
layout: onepage
permalink: /
title: ""
author_profile: false
---

<section id="bio">
...
</section>

<section id="research">
...
</section>

<section id="teaching">
  <h2>Teaching</h2>

  {% for post in site.teaching reversed %}
    <div class="simple-entry">
      <h3>{{ post.title }}</h3>

      {% if post.venue %}
        <div class="muted">{{ post.venue }}</div>
      {% endif %}

      {% if post.date %}
        <div class="muted">{{ post.date | date: "%Y" }}</div>
      {% endif %}

      {% if post.excerpt %}
        <p>{{ post.excerpt }}</p>
      {% endif %}
    </div>
  {% endfor %}

</section>

<section id="resources">
  <h2>Resources</h2>

  <p class="muted">
    Resources will be added here in the future.
  </p>
</section>

<section id="contact">
...
</section>
