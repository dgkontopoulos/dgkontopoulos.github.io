---
layout: archive
title: "<h1>Publications</h1>"
permalink: /publications/
author_profile: true
---

<script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!---
<h2><b><font color = 'orange'>In press</font></b></h2><hr>

{% for post in site.publications reversed %}
  {% if post.pubtype == 'in-press' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<br>
-->


<!---<h2><b><font color = 'orange'>Preprints</font></b></h2><hr>-->

{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


<br>

<h2><b><font color = 'orange'>Peer-reviewed</font></b></h2><hr>

{% for post in site.publications reversed %}
  {% if post.pubtype == 'peer-reviewed' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
