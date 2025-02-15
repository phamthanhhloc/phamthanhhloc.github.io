---
layout: page
title: Formation Control of Multi-Robot Systems Using Consensus Protocols
description: Multi-robot Systems - Formation Control
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

This pioneering project by a dedicated team of five master’s students, including myself, delves into the development and implementation of **consensus protocol-based** strategies for the robust coordination and formation control of multi-robot systems. Focusing on rendezvous and formation control, we crafted a software framework utilizing graph theory for dynamic robot swarm control. My contributions spanned from conceptualization to implementation, including algorithm development, simulation and laboratory testing, and analytical evaluation. This project not only honed my skills in robotics and software development but also highlighted my ability to collaborate effectively and drive innovation in complex multi-robot systems.

## Methodology

- Developed and implemented advanced **consensus protocols** for multi-robot coordination, emphasizing rendezvous and formation control.
- **Flocking** behaviors were designed based on **Reynolds Rules** including speration and obstacle avoidance behaviors.
- Utilized graph theory for intricate network modeling, enabling structured swarm control in both distributed and semi-distributed settings.
  
The system was developed in Python and implemented within the **Robot Operating System (ROS2)** framework. Preliminary testing and system tuning were carried out in the **Sphero** and **CrazySim** simulation environment, with further validation performed in laboratory environment using **crazyflies** robots.

## Results
Video results from simulation and real robot demonstrate the protocols’ efficacy in achieving precise formation control and obstacle avoidance, underscoring the potential of consensus protocols in enhancing distributed robotic systems in real-world scenarios.



## Impact and Future Work
Our research significantly advances the understanding and application of consensus protocols in swarm robotics, with potential implications for autonomous exploration, synchronized tasks, and efficient spatial organization. The project sets a foundation for future exploration into hardware implementations and real-world applications, promising substantial contributions to robotics and distributed control systems.



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
        {% include figure.liquid loading="eager" path="assets/gif/flocking.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/gif/Rendezvous.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/gif/FormationControl.gif" title="example image" class="img-fluid rounded z-depth-1" %}
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
