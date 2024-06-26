---
layout: page
title: Smart Planner
description: An all-in-one place to view the deadlines of all your upcoming assignments. (July 2022)
img: assets/img/smart-planner.jpeg
importance: 7
category: fun
---

<div>

    <p>If you’re currently a school student, undergraduate student, or even graduate student, tell me this situation doesn’t sound familiar to you. As your professor finishes their lecture, you take a quick glance at the homework board to see the due dates for upcoming assignments. Seeing so much work to do this weekend, you take between, say, thirty seconds to a minute furiously scribbling down the due dates into your handy-dandy planner. As you head over to your next class, you see the homework board and realize you have more work to do. Groaning, you take between a minute to one and a half minutes copying down the due dates into your planner. At the next class, you spend between thirty seconds to a minute writing down the due dates. The cycle repeats again and again, where, by the end of the day, you wasted nearly between three to six minutes writing down the due dates into your planner. Don’t you think that time could be better used somewhere else? Maybe you could chat with your friends or ask the professor a question. Wouldn't it be better if these reminders were automatically written for you in a safe place everyday? To make matters worse, you enter your chemistry class Monday morning and realize you forgot to do your homework because you had forcibly crammed the due date into the bottom corner of your planner. “How careless of you! It’s so tiny that it’s barely even legible. It’s no wonder you forgot to do it,” your professor answers in response to your dilemma. Don't you hate this feeling that lingers when you miss the deadline?</p>

    <p>Unless you’re like a few select people who can memorize the due dates and keep track of everything in your head, then I have news for you. Get Smart Planner! This is an app that enables you to stay organized and seamlessly keep track of all your upcoming assignments. Instead of having to write assignment deadlines on the homework board everyday, professors have the ability to create assignment reminders in the app in just 1-2 minutes. Students can look at these reminders whenever they wish throughout the day. Any user can also give comments and ratings to other users, regardless of whether they’re professors or students. Know how others feel about you! Say goodbye to outdated paper daily planners, and say hello to <i>Smart Planner</i>! Happy planning — and studying!</p>

    <p>Get it on the Google Play Store <a href="https://play.google.com/store/apps/details?id=com.anubhav.assignmentsfeed">here</a>!</p>

    <p>See the source code <a href="https://github.com/asen4/SmartPlanner">here</a> available on GitHub!</p>

    <p>See a gallery of screenshots from the app below!</p>

</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/1.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/2.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/3.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/4.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/5.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/6.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/7.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/smart-planner/8.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
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
