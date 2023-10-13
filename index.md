---
title: FIReVision
subtitle: A Photorealistic Infrared (IR) Simulator for Wildland Fire Robotics
layout: page
show_sidebar: false
hide_footer: false
hero_height: is-large
hero_image: /img/homepage_slideshow.gif
hero_link: https://castacks.github.io/firevision_sim/getting_started.html
hero_link_text: Get Started

# hero_link2: /current-members/
# hero_link_text2: See Our Team
---


# About FIReVision

Wildfires are growing in severity and frequency due to climate change. 
Advances in technology, including AI and robotics, has great potential to scale our effectiveness to wildfire response. 
However, development of advanced technology for wildfires faces a high barrier to entry because it is difficult to safely test robots in hazardous wildfires.
To address this issue, we propose a photorealistic wildland fire robotics simulator named \emph{FIReVision} built upon AirSim/Colosseum and Unreal Engine 5. 
The simulated environment features fires and smoke in a forest environment, with wildland fire crew and vehicles.
Importantly, in addition to the existing set of robotics sensors in AirSim, we propose improvements to the photorealistic fidelity of the thermal infrared sensor tuned to real-world fire thermal data.

Test

<div>
    <div style="float: center; width: 100%">
    <div class="video-wrapper"><iframe src="https://www.youtube.com/embed/02Y727bU7ss" frameborder="0" allowfullscreen></iframe></div>
    </div>
    <!-- <div style="float: right; width: 48%;">
    <div class="video-wrapper"><iframe src="https://www.youtube.com/embed/nHVOW_jl2m8" frameborder="0" allowfullscreen></iframe></div>
    </div> -->
</div>


# Features
- thermal IR simulation tuned from real world data
- light-based thermal emission
- smoke, fires, dynamic fire crew, and fire vehicles in a forest environment
- integration with Colosseum/AirSim for quadrotor simulation and robot sensor data simulation

# Get Started

Download the [standalone executable environment](https://drive.google.com/file/d/1r0-4Zqqx3nZmpTfzIfuOZheGTIQbczCU/view) to try it out!

<!-- This project is part of the [AirLab](https://theairlab.org) from the [Robotics Institute](https://www.ri.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/).

# Highlights
{% assign posts = site.posts | where:"categories","highlights" %}
<div class="columns is-multiline">
    {% for post in posts %}
    <div class="column is-4-desktop is-6-tablet">
        {% include post-card.html %}
    </div>
    {% endfor %}
</div> -->
