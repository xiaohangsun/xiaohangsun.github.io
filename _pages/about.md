---
layout: onepage
permalink: /
title: ""
author_profile: false
---

<section id="bio">

  <div class="bio-header">
    <img src="/images/profile.png" alt="Xiaohang Sun" class="profile-photo">

    <div class="bio-intro">
      <h1>Xiaohang Sun</h1>

      <p class="position">
        PhD Student in Political Science<br>
        Pennsylvania State University
      </p>

      <p class="profile-links">
        <a href="/cv/">CV</a>
        <a href="mailto:xqs5214@psu.edu">Email</a>
        <a href="https://github.com/xiaohangsun">GitHub</a>
      </p>
    </div>
  </div>

  <div class="bio-text">
    <p>
     My name is Xiaohang Sun. I am a PhD student in Political Science at Penn State. I study elections and civil conflicts in developing countries. My recent projects focus on political representation and the Maoist insurgency in India. Before joining Penn State, I earned dual bachelor’s degrees in international politics and economics from Shandong University, China, in 2024. I then pursued a master’s degree in international relations at Nanyang Technological University, Singapore.
    </p>
  </div>

</section>

<section id="research">
  <h2>Research</h2>

  <div class="research-subsection">
    <h3>Publications</h3>

    <p class="muted">
      Publications will be added here.
    </p>
  </div>

  <div class="research-subsection">
    <h3>Working Papers</h3>

    <p class="muted">
      Working papers will be added here.
    </p>
  </div>

  <div class="research-subsection">
    <h3>In Progress</h3>

    <div class="research-item">
      <h4>Political Representation and the Maoist Insurgency in India</h4>

      <p class="research-meta">
        In progress
      </p>
    </div>

  </div>
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
