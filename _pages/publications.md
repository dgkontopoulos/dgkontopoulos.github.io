---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<center>
	<a title="Word cloud of abstracts from all papers listed below."><img src="../images/publications/wordcloud.png"></a>
	&nbsp;&nbsp;&nbsp;
	<a title="Network of semantically related terms from paper abstracts."><img src="../images/publications/word_network.png"></a>
</center><br>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
