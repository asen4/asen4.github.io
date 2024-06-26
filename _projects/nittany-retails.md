---
layout: page
title: Nittany Retails
description: A retail app for students to buy and sell goods that they don't need anymore.
img: assets/img/nittany-retails.png
importance: 8
category: fun
---

<div>

    <p>Given the massive student population at Penn State University (PSU), there’s definitely a need for more tools and resources to ease and support students as they juggle school, work, sports, activities, and more. This is especially true for first-year students who are currently navigating the initial transition to campus and coping with the stress. The administration has already developed many helpful mobile applications like <i>Penn State Go</i>, the <i>Engagement App</i>, and <i>CATA+</i> to name a few. While such tools come in useful for students on a regular basis, however, I feel there’s substantial room for improvement in this respect.</p>

    <p>Take the weekly football games from last fall as an example. Oftentimes, I used to see someone sending out a message to sell their tickets on social media platforms like <i>GroupMe</i>, <i>Facebook</i>, and <i>Snapchat</i> to name a few. But most times, such communication is ineffective because not every student uses or knows an “online marketplace” exists on these applications, especially incoming freshman students who aren’t familiarised with these norms. Similarly, I have seen many students post similar messages regarding group events and conventions held frequently around campus, saying things like “I have a ticket to the concert tomorrow, but I’m not going. If anyone wants it or knows someone who would want it, you are welcome to have it. Just let me know.” And what’s more is that most students follow similar techniques to sell their unwanted textbooks and course materials at the end of the semester, sometimes being unsuccessful because they were unable to reach the “right” audience.</p>

    <p>And so, I was hoping to launch this initiative of developing mobile apps to better specific aspects of student life here, starting with a specialised retail marketplace app. An all-in-one convenience, the app will enable one to submit requests and trade unwanted clothes, textbooks, and any other goods with other students here at PSU — all while earning some money too! It’s a win-win for everyone: you get rid of your old stuff and make someone else happy, while getting some cha-ching in return!</p>

</div>

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

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
