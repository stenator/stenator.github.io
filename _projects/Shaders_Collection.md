---
layout: page
title: Shaders Collection
#description: a project with a background image and giscus comments
img: assets/img/3.jpg
importance: 1
category: work
#giscus_comments: true
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.


<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid 
       loading="eager" 
       path="/assets/img/projects/myproject/Lullaby_01.jpg" 
       title="Image 1" 
       class="img-fluid rounded z-depth-1" 
    %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid 
       loading="eager" 
       path="/assets/img/Portefolio/Shaders/Lullaby_02.jpg" 
       title="Image 2" 
       class="img-fluid rounded z-depth-1" 
    %}
  </div>
</div>
<div class="caption">
  Two images side by side — for example, shader graph on the left and result on the right.
</div>

<div class="row mt-4">
  <div class="col-sm">
    <video controls class="img-fluid rounded z-depth-1">
      <source src="/assets/video/Portefolio/Shaders/Lullaby_transition.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

<div class="caption">
  Demo video of the effect/material/tool in action.
</div>
