---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Here is a list of my main publications. You can find the complete list on <a href="{{(https://scholar.google.com/citations?user=_Vg1IrUAAAAJ&hl=pt-BR})}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
