---
layout: default
title: CookZ Image Guides
---

# CookZ Image Guides

Jump to:
- [CookZ](#cookz)
- [CookZPlants](#cookzplants)

---

<a id="cookz"></a>
## CookZ

{% assign cookz_images = site.static_files | where_exp: "file", "file.path contains '/images/cookz/'" %}

{% for image in cookz_images %}

<a href="{{ site.baseurl }}{{ image.path }}" target="_blank">
    <img src="{{ site.baseurl }}{{ image.path }}" style="margin-bottom:20px;">
</a>

---

{% endfor %}

<a id="cookzplants"></a>
## CookZPlants

{% assign plant_images = site.static_files | where_exp: "file", "file.path contains '/images/cookzplants/'" %}

{% for image in plant_images %}

<a href="{{ site.baseurl }}{{ image.path }}" target="_blank">
    <img src="{{ site.baseurl }}{{ image.path }}" style="margin-bottom:20px;">
</a>

---

{% endfor %}