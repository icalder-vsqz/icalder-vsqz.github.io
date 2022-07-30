---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Journal articles
=======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Conference proceedings
=======
{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
