---
layout: page
title: TalkZone
description: TalkZone is ultimately designed to create a better video-calling experience. (October 2021)
img: assets/img/talkzone.png
importance: 6
category: fun
---

<div>

    <p>Tell me this doesn’t sound familiar to you. You’re in a FaceTime call, Zoom call, Google hangout, WeChat, or Skype on your phone or tablet with someone, let’s say your grandma for example. She tries to show you a picture on her phone or wave a piece of writing in front of you. “It’s hard to see,” you reply. Even though this is a simple example, isn’t it a pain to video call somebody again and again on a small phone or tablet screen? Wouldn’t you prefer to have a nice and decent conversation with them on a larger screen instead like a TV? That way it would make it seem like they're actually in the room with you—like an almost life-size display. And it sure would be easier to see what grandma’s trying to show you.</p>

    <p>But wait. Can’t I already do that by hooking up a HDMI cable between my laptop and the TV? Yes, you’re right, but think about the extra steps of having to get up and fetch the HDMI cable and then connect the two devices together and then set it up on the TV. A pain, right? What if I told you an app could do this step by simply pressing one button? A lot easier, right?</p>

    <p>That’s exactly one of the features of <i>TalkZone</i>. <i>TalkZone</i> enables you to video call somebody from your own TV for a better video-calling experience. It also contains some of the typical characteristics of a social networking app (e.g. instant-messaging and posting) in a more EASY-TO-USE and SIMPLIFIED setting without a gazillion buttons, unlike Facebook, Twitter, or any other "advanced" social media app.</p>

    <p><b>Additional charges will apply as necessary for international phone calls, depending on your mobile plan. <i>TalkZone</i> will not be held responsible.</b></p>

    <p>Get it on the Google Play Store <a href="https://play.google.com/store/apps/details?id=com.anubhav.talkzone2">here</a>!</p>

    <p>See the source code <a href="https://github.com/asen4/TalkZone-2.0">here</a> available on GitHub!</p>

    <p>See a gallery of screenshots from the app below!</p>

</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/1.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/2.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/3.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/4.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/5.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/6.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/7.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/talkzone/8.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

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
