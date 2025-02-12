---
layout: single
title: Riichi Mahjong
excerpt: "My first C++ command prompt project"
classes: wide
collection: projects
author_profile: true
tagline: "My first challenge in C++ game programming."
header:
  overlay_image: assets/images/projects\riichi-mahjong/mahjong-banner.png
  teaser: assets/images/projects/riichi-mahjong/mahjong-teaser.png
---

One of my modules from university tasked me with making a simple console-based C++ game. Naturally, the first game I gravitated towards was mahjong to challenge myself with its complex mechanics and non-linear game structure. I managed to re-create most of the mechanics to the best of my current ability and learnt a lot about the mechanics of C++ whilst doing so.

{% capture fig_img %}
![mahjong-showcase](\assets\images\projects\riichi-mahjong\mahjong-showcase.png)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>A screenshot of my program in action</figcaption>
</figure>

If you would like to play the game or inspect the source code, you can do so [here](https://github.com/EthanMunday/RichiMajong)
{: .notice--info}

In my program, I used a few professional programming techniques such as object-oriented programming, overloading and dynamic memory allocation. For being my first major project using the language, I am quite happy with my result.