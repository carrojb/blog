---
layout: page
title: ''
permalink: /gallery1/
published: true
---

<!-- The grid: four columns -->
<div class="row">
  <div class="column">
    <img src="https://jonbcarroll.s3.us-east-2.amazonaws.com/_malheur_06.jpg" alt="Nature" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="img_snow.jpg" alt="Snow" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="img_mountains.jpg" alt="Mountains" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="img_lights.jpg" alt="Lights" onclick="myFunction(this);">
  </div>
</div>

<!-- The expanding image container -->
<div class="container">
  <!-- Close the image -->
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>

  <!-- Expanded image -->
  <img id="expandedImg" style="width:100%">

  <!-- Image text -->
  <div id="imgtext"></div>
</div>


