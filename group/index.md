---
title: Group
nav:
  order: 3
---

# 🎓 Group

## Faculty

{% include list_portrait.html data="members" component="portrait" filters="role: pi" %}

{% include section.html %}

## Students

{% include list_portrait.html data="members" component="portrait" filters="role: phd" style="small" %}
{% include list_portrait.html data="members" component="portrait" filters="role: ms" style="small" %}

{% include section.html background="images/assets/bg_deep_neural_network.webp" dark=true %}

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

{% include list_portrait.html data="members" component="portrait" filters="role: alumni" style="small" %}
