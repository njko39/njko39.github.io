---
layout: page
title: Portfolio
permalink: /portfolio
---
I mostly made outfits, accessories, weapons and props!

Click on image to see more renders!

<!-- Category buttons -->
<div id="myBtnContainer">
  <button class="btn active" onclick="filterSelection('all')"> Show all</button>
  <button class="btn" onclick="filterSelection('Outfits')"> Outfits</button>
  <button class="btn" onclick="filterSelection('Props')"> Props</button>
<!--  <button class="btn" onclick="filterSelection('Characters')"> Characters</button> -->
</div>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column Outfits">
    <div class="content">
      <a href="{{ site.github.url }}/3d/vintage-outfit"><img src="https://drive.google.com/thumbnail?id=1GriVJKLM38HS-1aEtZSo0UuimxedzgAD&sz=w1000" alt="Vintage Shirt and Skirt" style="width:100%"></a>
      <!--<h4>Title</h4>-->
      <!--<p>Lorem ipsum dolor..</p>-->
    </div>
  </div>
  <div class="column Outfits">
    <div class="content">
      <img src="https://drive.google.com/thumbnail?id=1FTuwvvwM1WdgddXLC9zX-vIJXschTthZ&sz=w1000" style="width:100%">
    </div>
  </div>
  <div class="column Outfits">
    <div class="content">
      <img src="https://drive.google.com/thumbnail?id=1GhKjscS4bWZVcPrqx05TpZDUdgUenlsJ&sz=w1000" style="width:100%">
    </div>
  </div>

  <div class="column Props">
    <div class="content">
      <img src="https://drive.google.com/thumbnail?id=1TixlzfbAwLZNnZL2hNa9uAVrDc3OYpah&sz=w1000" alt="Ramen" style="width:100%">
    </div>
  </div>
  <div class="column Props">
    <div class="content">
      <img src="https://drive.google.com/thumbnail?id=1HpMmwEVrH-sE1CHsRMwvEOPtS6ud5omI&sz=w1000" alt="Pearl Necklace" style="width:100%">
    </div>
  </div>
  <div class="column Props">
    <div class="content">
      <img src="https://drive.google.com/thumbnail?id=13o0Q_icYh0fPvv6mAwbzZifg5P7zbx2g&sz=w1000" alt="Cat" style="width:100%">
    </div>
  </div>

<!-- characters - empty now -->
<!--
<div class="row">
  <div class="column Characters">
    <div class="content">
      <img src="/w3images/Characters1.jpg" alt="Characters" style="width:100%">
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column Characters">
    <div class="content">
      <img src="/w3images/Characters2.jpg" alt="Characters" style="width:100%">
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column Characters">
    <div class="content">
      <img src="/w3images/Characters3.jpg" alt="Characters" style="width:100%">
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
</div> 
  -->
<!-- END GRID -->


{% include portfolio.html %}