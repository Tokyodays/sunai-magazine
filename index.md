---
layout: default
title: Home
---

# SunAi Magazine へようこそ

AIとクリエイティビティ、そして精密加工技術の交差点を探求するマガジンです。

## 最新の記事

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date_to_string }}</small>
    </li>
  {% endfor %}
</ul>

## 全てのコンテンツ

<ul>
  {% for page in site.pages %}
    {% if page.title and page.url != "/" %}
      <li>
        <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>