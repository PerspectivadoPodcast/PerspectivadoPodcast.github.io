---
layout: page
title: "Episódios"
permalink: /episodes/
order: 1
---
{% assign sorted_pages = site.pages | sort:"order" %}
{% for node in sorted_pages %}
  <li><a href="{{node.url}}">{{node.title}}</a></li>
{% endfor %}
