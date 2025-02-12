---
layout: single
title: Digital Orrery
excerpt: "A digital orrery using custom vector maths I made in unity"
classes: wide
collection: projects
author_profile: true
tagline: "A research project into common vector maths."
header:
  overlay_image: assets\images\projects\digital-orrery\digital-orrery-banner.png
  teaser: assets\images\projects\digital-orrery\digital-orrery-teaser.png
---

This is a digital orrery I created in Unity using C*. This was my first dive into vector maths, from dot and cross products to transformation matrices to spherical rotation using quaternions. This culminated in using a custom transform, fully programmed by me along with sphere collisions for the planets and custom scripts to spawn and alter planets and orbits in real time.

The link to the github repo can be found [here](https://github.com/EthanMunday/EMMaths)

{% capture fig_img %}
![orrery-in-engine](\assets\images\projects\digital-orrery\digital-orrery-engine.png)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>The orrery in engine.</figcaption>
</figure>

{% capture fig_img1 %}
![orrery-showcase](\assets\images\projects\digital-orrery\digital-orrery-axis.png)
{% endcapture %}

<figure>
  {{ fig_img1 | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Multi-axial orbiting.</figcaption>
</figure>

 Looking at all the aspects of this project, I am quite proud of the feats I have accomplished, however many improvements could be added and things could be simplified, such as adding an in-game editor for the sandbox, implementing better camera controls and increasing the performance of the orrery using spacial partitioning.