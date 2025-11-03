---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are based at the London Centre for Nanotechnology.

{% include section.html %}

## Principal Investigator
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

## Postdoctoral Researcher
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}

## PhD Candidates
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

## Alumni
{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

If you are interested in joining out team, please go to our [Join Us](join) page.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
