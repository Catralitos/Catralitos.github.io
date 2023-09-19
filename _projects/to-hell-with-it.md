---
layout: page
title: To Hell With It
description: To Hell With It is a top-down action-adventure game developed in Unity for the LGBTQ+ Horror Jam 2023.
img: assets/img/To Hell With It (1).png
importance: 2
category: Game Programming
giscus_comments: true
---

To Hell With It is a game where players have until the end of their third day to gather enough resources for a big final battle. To do this, they must explore a town, its inhabitants that have their own routines, and can give them different quests throughout the 3 days.

Players gather resources and manage their limited inventory to save up for the huge final battle. Weapons have a set number of uses before breaking, and healing items are only good once. So being frugal is essential.

The game was developed for the LGBTQ+ Horror Jam 2023, by a team of two programmers (including myself), two artists, and a writer. I programmed essentially everything but the enemy and NPC AI.

We wanted to do a game inspired by Majora's Mask and Deadly Premonition, and so my biggest challenge programming wise, was to do a quest system that would be as robust as we wanted and could integrate a day/night cycle and routines.

I started researching tutorials for quest systems in Unity, but they were all too rudimentary. Just simple counters of items collected and enemies killed. We wanted different dialogues through the quest, for certain events to happen after a step of the quest, rewards per step, and to integrate time into it, so different quests/steps/dialoques could be available at different times of the in-game day.

I stumbled upon a Unity open-source project, that sadly was incomplete and lacked documentation in the areas we most wanted to research. This one: [https://github.com/UnityTechnologies/open-project-1](https://github.com/UnityTechnologies/open-project-1).
But their quest system was the closest to what we wanted. So I spent roughly over a week reverse-engineering the project.
Copying components one by one into our project, understandingg how they worked, how they connected to other controllers and so one, until I had something working. And then I adapted the code to our more specific needs.

This project taught me a lot about Scriptable Objects, and how to manage the game without singletons (which I was used to) and using Scriptable Object events instead. I also got to work with asset tables and Localized Strings.

The final quest system, has quests made of steps, all Scriptable Objects. Steps have dialogue before and after the step is complete, possible reward, various kinds of validity checks (if the player has an item, killed enemies, etc...), and can make an event trigger at the end of the step. We also adapted it so steps/quests are only available at certain days/times of day.

In addition to all that, I did a basic combat system. To add a survival horror feel to the game I was ispired by Resident Evil 4. Usually the player just aims where they're moving, and to aim more carefully, they must come to a halt, the same for using healing items. There's a radial inventory menu inspired by Secret of Mana, that is limited to 8 items.

The code is available at [https://github.com/Catralitos/Hell-Game](https://github.com/Catralitos/Hell-Game) and the game is playable at [https://catralitos.itch.io/to-hell-with-it](https://catralitos.itch.io/to-hell-with-it).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (2).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (3).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (4).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (5).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (6).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (7).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (8).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/To Hell With It (9).png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
