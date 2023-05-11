---
layout: default
---

i made a quick blog to have some place to put notes and things i wanna publish to the world.

don't expect anything quality! mostly just either dev, language, or bl rambles~

## Pages

- [My profile (over at yuukun.dev) ↗️](https://yuukun.dev)
- [Yuu's Japanese to Thai Transliteration Rules ↗️](https://github.com/kagiura/ja-th)
  - [HTML/Website Version (WIP)](/ja-th)
- Full list of Twitter design works (Twitter moments replacement):
  - [2022-2023](/design-works/22)
  - [2021](/design-works/21)

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.date | date: "%B %-d, %Y" }} {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
