---
layout: default
---

{% assign monate = "Januar,Februar,März,April,Mai,Juni,Juli,August,September,Oktober,November,Dezember" | split: "," %}
{% assign gruppen = site.posts | group_by_exp: "post", "post.date | date: '%Y-%m'" %}
{% for gruppe in gruppen %}
{% assign erster = gruppe.items | first %}
{% assign mi = erster.date | date: "%-m" | minus: 1 %}
<h2 class="release-month">{{ monate[mi] }} {{ erster.date | date: "%Y" }}</h2>
<ul class="release-list">
  {% for post in gruppe.items %}
  <li>
    <a class="release-title" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    {% if post.description %}<p class="release-desc">{{ post.description }}</p>{% endif %}
  </li>
  {% endfor %}
</ul>
{% endfor %}
