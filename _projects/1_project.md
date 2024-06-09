---
layout: page
title: Angry Birds
description: Angry Birds is a popular mobile game developed by Rovio Entertainment, where players use a slingshot to launch birds at structures to destroy pigs stationed within. The goal is to eliminate all the pigs on each level using a limited number of birds, each with unique abilities.
img: assets/img/angry-birds.png
importance: 1
category: fun
related_publications: true
---

Gameplay

The primary objective of Angry Birds is to eliminate all the pigs on each level using a limited number of birds. Each bird has unique abilities that add strategic depth to the game. For example:

    Red Bird: The basic bird with no special abilities.
    Blue Bird: Splits into three smaller birds mid-flight, useful against glass structures.
    Yellow Bird: Speeds up when tapped, ideal for breaking through wood.
    Black Bird: Explodes, dealing heavy damage to surrounding structures.
    White Bird: Drops explosive eggs, effective against pigs in hard-to-reach places.

Players must carefully aim and time their shots to maximize damage and complete levels with the highest possible score. Scores are based on the number of birds used and the amount of destruction caused.
Story and Characters

The game's story revolves around a group of birds whose eggs have been stolen by green pigs. The pigs hide in various structures, prompting the birds to seek revenge. This simple storyline adds a humorous and lighthearted context to the gameplay.
Levels and Progression

Angry Birds features numerous levels, each with increasing difficulty and complexity. The game also includes special themed episodes and updates that introduce new birds, pigs, and challenges, keeping the gameplay fresh and engaging.
Cultural Impact

Angry Birds has become a cultural phenomenon since its release, spawning multiple sequels, spin-offs, merchandise, and even an animated television series and feature films. Its success is attributed to its accessible gameplay, charming characters, and frequent updates that introduce new content.
Legacy

The game has been praised for its innovative use of physics-based mechanics, intuitive controls, and the engaging puzzle-solving experience it offers. Angry Birds has won numerous awards and is considered one of the most successful mobile games of all time, with billions of downloads across various platforms.

In summary, Angry Birds combines simple, addictive gameplay with strategic depth and charming visuals, making it a beloved classic in the world of mobile gaming.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
