---
layout: page
title: Snake
description: Snake is a classic arcade game where players control a growing line that resembles a snake, navigating it around the screen to consume food items. Each item eaten causes the snake to grow longer, and the objective is to avoid colliding with the screen's edges or the snake's own body.
img: assets/img/snake.png
importance: 3
category: fun
---

This game is my own modified version of the original game Snake. Unlike the original game, there are two different types of fruit that will appear on the screen — apples and blueberries. Each fruit consumed will increase the length of the snake by a different amount (i.e., blueberries = +2 and apples = +4). There are also various obstacles (i.e., yellow squares) placed at random locations on the screen. (They refresh with each round.) If the snake hits an obstacle, it will head in a completely new direction. Be wary!

**Gameplay**

In Snake, the player controls a line, or "snake," that moves around a screen, collecting items (often depicted as food) to grow longer. The objective is to consume as many items as possible without running into the snake's own body or the edges of the screen. The game continues until the snake crashes into itself or a boundary, ending the session.

**Controls:** Typically, the snake is controlled using arrow keys on a keyboard, a joystick, or touch controls on a mobile device. The snake moves in a continuous direction until the player changes its course by pressing the corresponding control.
**Growth and Score:** Each item the snake consumes causes it to grow longer, which increases the game's difficulty as avoiding collisions becomes more challenging. The player's score increases with each item consumed, rewarding skillful navigation and planning.

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

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
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
