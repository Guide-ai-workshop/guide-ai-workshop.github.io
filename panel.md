---
layout: home
title: Panel Discussion
nav_exclude: false
permalink: /:path/panel
seo:
  type: Workshop
  name: Homepage
---

<img src="/assets/images/workshop_logo.png" height="100">

# Panel Discussion

## Subject: The Role of Data Management Research for Responsible AI

## Participants

{% assign instructors = site.staffers | where: 'role', 'Steven' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign instructors = site.staffers | where: 'role', 'Felix' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign instructors = site.staffers | where: 'role', 'Panel' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

<!--- - Sudeepa Roy (Duke University)
- Boris Glavic (University of Illinois at Chicago)
- Felix Naumann (Hasso Plattner Institute, University of Potsdam)
- Steven Whang (KAIST)
- Fatemeh Nargesian (University of Rochester)
--->
