---
title: Group
nav:
  order: 3
---

# 🎓 Group

## Faculty

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}

## Students

{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}

{% include section.html background="images/bg_deep_neural_network.webp" dark=true %}

Join us in pushing the boundaries of innovation and discovery at our lab, where collaborative minds and cutting-edge research come together to make a meaningful impact.

{%
  include button.html
  link="join"
  text="Join Our Team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filters="role: alumni" %}
