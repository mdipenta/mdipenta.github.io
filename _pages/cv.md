---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

#TEST

Education
======
* Laurea Degree in Computer Engineering, 1999
* Ph.D in Computer Engineering, University of Sannio, Italy, 2003

Work experience
======
* 2019-present: Full Professor
 * University of Sannio, Italy

* 2011-2019: Associate Professor
 * University of Sannio, Italy

* 2004-2011: Assistant Professor
 * University of Sannio, Italy

 * 2003-2004: Postdoc
 * University of Sannio, Italy

Research Interests
======
* Software maintenance and evolution
* Mining software repositories
* Empirical software engineering
* DevOps
* Search-based software engineering
* Software testing

Publications
======

###Journal papers
  <ul>{% for post in site.journals %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
###Conference papers
  
    <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
###Book chapters
  
      <ul>{% for post in site.chapters %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* TBA
