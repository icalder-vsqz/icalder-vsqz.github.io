---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

*Journal articles*
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}</ul>

*Conference proceedings*
======
<ul>{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}</ul>

