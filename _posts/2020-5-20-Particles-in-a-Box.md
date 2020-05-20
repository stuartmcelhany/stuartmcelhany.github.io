---
layout: post
title: Particles in a Box
thumbnail: /images/particlesinabox/particlesinabox.gif
---

Simulation of particles in a box.

<video width="480" controls="controls" muted plays-inline autoplay>
  <source src="{{ site.baseurl }}/images/particlesinabox/collision.mp4">
</video>

This python script uses a class called particle which contains member variables for position, velocity, and size. Collision detection is handled using the `numpy` linear algebra library, which computes the tangent line upon a collision. The angle of collision is determined using the two-dimensional elastic collision equation.

[GitHub](https://github.com/stuartmcelhany/particles-in-a-box)
