---
layout: page
title: CPU Takeover
description: CPU Takeover is a twin-stick bullet hell game developed in Unity for 🎆 Bullet Hell Jam 🎆 2021.
img: assets/img/CPUTakeover (5).png
importance: 2
category: Game Programming
giscus_comments: true
---

CPU Takeover is a bullet-hell, top-down, twin-stick shooter where the player must destroy an evil virus, hacking the computer system.

To do this, they must attack it while surviving its attacks and the waves of enemies it spawns.

Luckily enemies drop powerups to aid the player. And due to a bug in the code, having near misses with bullets will freeze time and delay the spawning of more enemies.

This was made as part of the Bullet Hell Jam 2021 where the theme was "10 seconds", hence that's why the boss switches attacks/spawns enemies every 10 seconds.

In this game, I was the lead programmer, doing everything except for the bullet patterns/spawns and the work on the menus.

I made it so the game could use both the keyboard and mouse or a controller, using Unity's "new" Input System.
This included a dash, highlighted by a line renderer.

To spawn enemies, there were roughly 20 set locations where turrets could spawn. I made a class with a while cycle that found available positions randomly and spawned the turrets, as well as the orbiter enemies. The increase in the number of enemies spawned per round was determined by a radical exponent function.

I used a state machine system I learned in Gamedev Técnico to program the enemies, though this was ultimately very simple, as the enemies had a maximum of two states: Shooting or Idle (not-shooting).

The code is available at [https://github.com/Catralitos/BulletHellJam](https://github.com/Catralitos/BulletHellJam) and the game is playable at [https://carlosmvs.itch.io/cpu-takeover](https://carlosmvs.itch.io/cpu-takeover).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CPUTakeover (2).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CPUTakeover (1).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CPUTakeover (3).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CPUTakeover (4).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CPUTakeover (6).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

