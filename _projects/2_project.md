---
layout: page
title: Flappy Bird
description: Flappy Bird is a mobile game created by Dong Nguyen, where players control a bird by tapping the screen to keep it flying while avoiding obstacles like green pipes. The objective is to navigate the bird through as many gaps as possible without hitting the pipes or falling.
img: assets/img/flappy-bird.png
importance: 2
category: fun
giscus_comments: true
---

**Gameplay**

The objective of Flappy Bird is straightforward: players control a small, pixelated bird that continuously moves to the right. By tapping the screen, players make the bird flap its wings and gain a bit of altitude. The bird will fall due to gravity when the screen is not tapped. The challenge lies in navigating the bird through gaps between sets of vertically aligned pipes without crashing into them or falling to the ground.

**Controls:** The game uses a single control mechanism – tapping the screen. Each tap makes the bird flap and rise slightly, requiring precise timing to keep the bird in motion and avoid obstacles.
**Obstacles:** The green pipes, reminiscent of those in the Super Mario series, come in pairs with gaps that the bird must fly through. The placement and spacing of these pipes create varying levels of difficulty as players progress.

**Scoring**

Players earn one point for each set of pipes they successfully pass through. The game tracks the highest score achieved, providing a competitive element as players strive to beat their own records and those of others. There are no levels or stages; the gameplay is continuous and only ends when the bird collides with an obstacle or falls to the ground.

**Graphics and Sound**

Flappy Bird features simple, 8-bit-style graphics with a nostalgic aesthetic. The bird and pipes are designed with minimal detail, and the background consists of a repeating landscape of blue skies and green ground. The sound effects include a subtle flapping noise, a point tallying sound, and a distinct crashing sound when the bird hits an obstacle.

**Legacy**

Despite its brief period of availability, Flappy Bird left a lasting impact on the mobile gaming industry. It inspired numerous clones and similar games, and its success demonstrated the potential for simple, minimalist game designs to achieve massive popularity. The game's viral nature and sudden removal have become a significant part of its lore.

In summary, Flappy Bird is a minimalist mobile game known for its simple controls, challenging gameplay, and significant cultural impact. Its rise and fall from app stores are memorable chapters in the history of mobile gaming.

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
