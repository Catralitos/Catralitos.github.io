---
layout: page
title: Senior Unrest
description: Senior Unrest is a puzzle rogue-like game developed in Unity for the 7DRL Challenge 2023.
img: assets/img/Senior Unrest (1).png
importance: 2
category: Game Programming
giscus_comments: true
---

Senior Unrest is a roguelike game that takes place in an old lady's house (or the recollection of her house...). Strange creatures disturb her sleep mercilessly. Her nights quickly become something worthy of a nightmare. Even the rooms seem to morph into new configurations. Is all this really happening or is it just something taken from the old lady's mind?

It was developed for the 7DRL Challenge 2023 and we actually did pretty well. We ended up 42ª out of 182 submissions, so that's the top 24%.

We were inspired by the Gremlins movies and the idea of catching monsters, having more of a puzzle design to the game. For this project, I did essentially all the code, as one of my colleagues wasn't as available as he thought.

The map generation algorithm was adapted from a Youtube tutorial [https://www.youtube.com/watch?v=u2i8Ga4phBA](https://www.youtube.com/watch?v=u2i8Ga4phBA) and it's actually straightforward and worked for us since we didn't want a lot of rooms connected by corridors. Taking a grid, pick the center square, and a random direction. Dig in that direction, and repeat the process until you've dug the amount you want.

Movement is done using co-routines, using a Turn Manager to ensure the enemies move simultaneously with the player. Enemy AI is extremely simple, the Runners just pick the move that puts the furthest away from the player, while the Chasers do the opposite.

While a new level is generated in the background, a shop appears and the player can purchase upgrades.

The code is available at [https://github.com/Catralitos/Senior-Unrest](https://github.com/Catralitos/Senior-Unrest) and the game is playable at [https://catralitos.itch.io/senior-unrest](https://catralitos.itch.io/senior-unrest).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (2).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (3).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (4).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (5).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (6).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (7).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (8).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Senior Unrest (1).jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>