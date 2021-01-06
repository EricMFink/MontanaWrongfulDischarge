---
layout: page
permalink: /sources/
title: Sources

---

# Statute
<ul>
{% for statute in site.statutes %}
<li><a href="{{ site.baseurl }}{{ statute.url }}">{{ statute.title }}</a></li>
{% endfor %}
</ul>

# Cases

<ul>
{% for case in site.cases %}
<li><a href="{{ site.baseurl }}{{ case.url }}">{{ case.title }}</a></li>
{% endfor %}
</ul>

# Articles

<ul>
{% for source in site.sources %}
<li><a href="{{ site.baseurl }}{{ source.url }}">{{ source.title }}</a></li>
{% endfor %}
</ul>

