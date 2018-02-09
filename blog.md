---
title: Blog
layout: default
---

<div class="content-wrapper">
  {% for post in site.posts %}
    <section class="subsection">
      <div class="row">
        <div class="col" align="center">
            <h2>{{ post.title }}</h2>
            <p>{{ post.content }}</p>
        </div>
      </div>
    </section>
  {% endfor %}
</div>
