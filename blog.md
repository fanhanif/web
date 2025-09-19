cat > blog.md << 'EOF'
---
layout: default
title: Blog
---

# Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%d %B %Y" }})</small>
    </li>
  {% endfor %}
</ul>
EOF
