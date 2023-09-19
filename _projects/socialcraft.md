---
layout: page
title: SocialCraft
description: Social Agents In Minecraft - Believable AI NPCs in Minecraft
img: assets/img/MapOverhead.png
importance: 1
category: School Projects
giscus_comments: true
---

Games keep expanding in scope, providing the player with increasingly bigger worlds to explore and fully immerse themselves in. And with bigger worlds, comes the need for designers to populate them with interesting characters, that feel like part of the world and that the player can forge a bond with. However,the effort required to individually author each character to reach this desired depth is unfeasible.

Our research goal is to remove the need for individual authoring and provide a framework where designers dictate how characters should behave, but still do not need to concern themselves with the minutia of the task. We aim to apply a model that allows for a large-scale character network to be deployed, with characters that behave like they are members of society, and have interpersonal relationships with each other.

Socialcraft was my thesis work, and my implementation of that framework, using Minecraft. Deploying the game server and bots on Docker, and also using Node.js, I utilized the prismarine-js and mineflayer APIs to create agents to run in the world. The agents make their decisions according to the logic set up by the framework.

In order to test our framework, we created two villages of agents in Minecraft, one very expressive and sociable, and one not as much. We had our subjects play Minecraft, and follow the lumberjack of the sociable village, who worked with their other village counterpart, for a full day. This allowed the subjects to observe each agent’s behavior and contrast them.

Results were mixed, but promising, with agents doing great in many of the parameters set for believability, but having a lot of technical problems.

Full details as to how the code works can be found in the [thesis document](https://github.com/Catralitos/socialcraft/blob/master/SocialAgentsInMinecraft.pdf).

The code is available at [https://github.com/Catralitos/socialcraft](https://github.com/Catralitos/socialcraft).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MapOverhead.PNG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Socialcraft map.
</div>
