---
layout: default 
---

# Welcome to HILA 383: The Inquisition {#history}

### recent posts {#history}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/383S2018{{ post.url }}">{{ post.title }}</a>  
      <br>
      {{ post.date | date: '%B %d, %Y' }}

      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
