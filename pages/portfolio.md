---
layout: page
title: Portfolio
permalink: /portfolio

---

I mostly made outfits, accessories, weapons and props! I also have [artstation page](https://njko39.artstation.com/)!

Click on image open artstation post with more renders!

<!-- Category buttons -->
<div class="portfolio-filters" id="myBtnContainer">
  <button class="btn active" onclick="filterSelection('all')"> Show all</button>
  <button class="btn" onclick="filterSelection('outfit')"> Clothing</button>
  <button class="btn" onclick="filterSelection('prop')"> Prop</button>
  <button class="btn" onclick="filterSelection('weapon')"> Weapon</button>
  <button class="btn" onclick="filterSelection('3dart')"> 3D Artwork</button>
<!--  <button class="btn" onclick="filterSelection('Characters')"> Characters</button> -->
</div>

<div class="row">
{% for post in site.data.portfolio %}
  <div class="column {{ post.type }}">
      <div class="content">
      <a href="{{ post.link }}" target="_blank"><img src="{{ post.pic }}" alt="{{ post.name }}" style="width:100%"></a>
    </div>
  </div>
{% endfor %}
</div>

{% include portfolio.html %}