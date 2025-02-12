---
layout: single
title: Custom Unity Navmesh
excerpt: "A custom navmesh I created from scratch in unity"
classes: wide
collection: projects
author_profile: true
tagline: "A research project into A* and navmesh generation."
header:
  overlay_image: assets\images\projects\custom-navmesh\custom-navmesh-banner.png
  teaser: assets\images\projects\custom-navmesh\custom-navmesh-teaser.png
---

This is a tool for Unity that allows for 2D navmesh generation based on a square grid of tiles. This required a lot of research into triangle maths such as Constrained Delaunay Triangulation and pathfinding through the A* algorithm. The end result of this project as seen here and on the front page is an environment capable of dynamically creating navmeshes and allowing AI agents with different behaviours to roam around with suitably accurate pathfinding.


The link to the github repo can be found [here](https://github.com/EthanMunday/AIMazeSolver/tree/game-ai)

{% capture fig_img %}
![navmesh-showcase](\assets\images\projects\custom-navmesh\custom-navmesh-generation.png)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>The final generated navmesh across an array of obstacles.</figcaption>
</figure>

{% include video id="1ifRyVQr_Q0td_5Tu_UjG9uOuG5ZYkHsS" provider="google-drive" %}
{% capture fig_img1 %}
{% endcapture %}

<figure>
  {{ fig_img1 | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>A stress test consisting of around 400 agents navigating around my name.</figcaption>
</figure>


This project helped to develop my C# skills greatly, alongside my understanding of AI and Navigation technology. In future efforts, I will expand this knowledge with the implementation of Local Clearance Triangulation on the Navmesh and Reciprocal Velocity Obstacles on the AI agents. 