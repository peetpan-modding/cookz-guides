---
layout: default
title: CookZ Guides
---

# CookZ Guides

## cookz

{% assign cookz_images = site.static_files | where_exp: "file", "file.path contains '/images/cookz/'" %}

{% for image in cookz_images %}

![{{ image.name }}]({{ image.path }})

[Download Full Resolution]({{ image.path }})

---

{% endfor %}

## cookzplants

{% assign plant_images = site.static_files | where_exp: "file", "file.path contains '/images/cookzplants/'" %}

{% for image in plant_images %}

![{{ image.name }}]({{ image.path }})

[Download Full Resolution]({{ image.path }})

---

{% endfor %}