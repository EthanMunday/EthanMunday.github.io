---
layout: single
title: Procedural Desert
excerpt: "A procedural desert I created using UE5"
classes: wide
collection: projects
author_profile: true
tagline: "Experimenting with Unreal Engine 5 and Unreal C++."
header:
  overlay_image: assets/images/projects/procedural-desert/desert-image.png
  teaser: assets/images/projects/procedural-desert/desert-teaser.png
---

A small but visually impressive project I created was a procedural desert using Unreal Engine 5 using C++. This was done using a procedural mesh component and required me to generate a long list of vertices, triangles and UV coordinates in order to create a smooth and changeable mesh.

The link to the github repo can be found [here](https://github.com/EthanMunday/DesertEnvironment)
{: .notice--info}

{% capture fig_img %}
![desert-showcase](\assets\images\projects\procedural-desert\desert-teaser.png)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>The desert in game.</figcaption>
</figure>


{% capture fig_img1 %}
![desert-visualisation](\assets\images\projects\procedural-desert\desert-visualiser.png)
{% endcapture %}

<figure>
  {{ fig_img1 | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Example of vertex generation in engine.</figcaption>
</figure>
