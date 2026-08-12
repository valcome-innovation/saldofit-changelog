---
layout: default
---

# Saldofit Changelog

Alle Neuigkeiten und Verbesserungen in Saldofit — ein Eintrag pro Release.

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url | relative_url }})**{% if post.description %} — {{ post.description }}{% endif %}
{% endfor %}
