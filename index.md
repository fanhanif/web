cat > index.md << 'EOF'
---
layout: default
title: Home
---

# Selamat Datang di Fanha

Minimalis. Cepat. Bermanfaat.

## Produk Digital
- [Ebook Prompt & Tools AI](https://link-ebook-ai.com)
- [Ebook Doa Sehari-hari](https://link-ebook-doa.com)

## Artikel Terbaru
<ul>
  {% for post in site.posts limit:5 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
EOF
