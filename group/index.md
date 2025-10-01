---
title: Group
nav:
  order: 3
---

# 🎓 Group

## Faculty

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html %}

## Students

{% include list.html data="members" component="portrait" filter="role == 'phd'" style="small" %}
{% include list.html data="members" component="portrait" filter="role == 'ms'" style="small" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" style="small" %}
