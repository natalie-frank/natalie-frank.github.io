---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
#Publications
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

[comment]: <> {% include base_path %}

[comment]: <> {% for post in site.publications reversed %}
[comment]: <>   {% include archive-single.html %}
[comment]: <> {% endfor %}
