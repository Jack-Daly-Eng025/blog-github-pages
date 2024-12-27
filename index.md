---
layout: Home
title: My Blog for 2025
---

# Welcome to My Blog

This is a space for sharing my thoughts, ideas, and projects. Feel free to explore the posts and connect with me!

## Latest Posts

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="meta">
      <small>Posted on {{ post.date | date: "%B %d, %Y" }}</small>
    </p>
    <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
    <a href="{{ post.url }}" class="read-more">Read More</a>
  </article>
  <hr>
{% endfor %}

---

## About Me

Hi, I'm Jack, a writer, coder, and creator. This blog is where I share my journey for 2025. You can find my work on [GitHub](https://github.com/Jack-Daly-Eng025/).

---

## Subscribe

Stay updated with the latest posts by subscribing to the [RSS feed](feed.xml).

