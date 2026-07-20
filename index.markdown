---
layout: default
title: Home
---

# Welcome to DevOps Nexus

Your gateway to mastering DevOps, Cloud Computing, and Networking.

## Latest Posts

{%- if site.posts.size > 0 -%}
  <ul class="post-list">
    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    {%- for post in site.posts limit: 3 -%}
    <li>
      <span class="post-meta">{{ post.date | date: date_format }}</span>
      <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </h3>
      {{ post.excerpt }}
    </li>
    {%- endfor -%}
  </ul>
  <p><a href="{{ '/blog.html' | relative_url }}">View all posts →</a></p>
{%- endif -%}

## About Me

Hi, I'm **Vikas Kumar** - a passionate developer and tech enthusiast based in Delhi, India. My commitment revolves around creating software that positively impacts users' lives.

[Read more about me →]({{ '/about/' | relative_url }})
