---
layout: page
title: News & Updates
permalink: /news/
---

<div class="full-news-page">
  <ul class="news-list">
    {% for item in site.data.news %}
      <li style="margin-bottom: 1.5em; list-style: none; border-bottom: 1px ghostwhite solid; padding-bottom: 1em;">
        <span style="display: block; font-weight: bold; color: #333; font-family: 'PT Sans Narrow', sans-serif; font-size: 1.1rem;">
          {{ item.date }}
        </span>
        <span style="display: block; margin-top: 5px; color: #555;">
          {{ item.content }}
        </span>
      </li>
    {% endfor %}
  </ul>
</div>

<div style="margin-top: 3em;">
  <a href="{{ site.url }}/" class="btn btn-small">← Back to Home</a>
</div>
