---
layout: page
title: Development of a novel web-based speech assessment app
description: A new multimodal assessment of speech in neurological diseases
importance: 1
category: work
related_publications: simmatis2023analytical, simmatis2022reliability
---

This project is focused on designing a new technology for analyzing speech in people with neurological impairments. The first question you might ask is, well, why do we care about speech in neurological diseases? Because speech is such a tightly controlled sensorimotor process, it can provide a very valuable window into the function of large tracts of the central nervous system at once. 

The audio signal produced by speech, far from being a simple waveform, actually consists of multiple interacting components that reflect a variety of contributions of the sensorimotor system, includig the respiratory system, the laryngeal and velopharyngeal apparatuses, and the oral articulators. The rhythmicity, force generation, and timing of each/all of these systems reflect motor control processes, either in health or, of interest for this project, in neurological diseases. With the preceding description, it is quite clear how diseases that affect the sensorimotor system (such as Parkinson's disease, Lou Gehrig's disease/ALS, multiple sclerosis, etc.) can all affect speech output in unique ways.

The central problem with present technical gold standards of speech assessment is that they can be cumbersome, and so they have to stay in the lab. However, this makes it quite difficult to implement them in practice - patients essentially need to be part of research studies to even use them, to say nothing of how this precludes their use in clinical practice. Home-based systems have been available for a few years now, but they all have their own limitations, such as poor data quality or limited ability to test diverse speech tasks.

Our project seeks to overcome these hurdles, by implementing (1) multimodal audio/video data collection, and (2) robust, high-quality data collection methodologies. 


<!--
img: assets/img/12.jpg

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
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
-->