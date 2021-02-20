---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a
  href="{{author.googlescholar}}">my Google Scholar profile</a></u> or
  <u><a href="https://dblp.org/pid/d/MassimilianoDiPenta.html">DBLP Page</a></u>.
{% endif %}

{% include base_path %}

<ul>
<li><a href="#journals">Journal papers</a></li>
<li><a href="#conferences">Conference papers</a></li>
<li><a href="#chapters">Book Chapters</a></li>
</ul>

<hr/>

<h2>Journal papers</h2>
<a name="journals"/>

{% for post in site.journals reversed %}
  {% include archive-single.html %}
  {% endfor %}

<hr/>

<h2>Conference papers</h2>
<a name="conferences"/>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<hr/>

<h2>Book chapters</h2>
<a name="chapters"/>
{% for post in site.chapters reversed %}
  {% include archive-single.html %}
{% endfor %}
