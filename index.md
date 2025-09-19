---
layout: default
title: Home
---

# Selamat datang di Fanha

Ini adalah blog tentang privacy, digital minimalism, dan produk digital.

## Artikel Terbaru
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%d %B %Y" }})</li>
  {% endfor %}
</ul>

## Produk Digital
- [Ebook Prompt & Tools AI](https://link-checkout-ai.com)
- [Ebook Doa Sehari-hari](https://link-checkout-doa.com)
