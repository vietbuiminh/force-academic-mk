---
layout: splash
title: "Research"
header:
  overlay_color: "#222222" #"#5e616c"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banners/IMG_0342.JPG
  actions:
  #  - label: "Get started"
  #    url: "/test/"
  caption: "Whitewater River Valley, Minnesota, USA"
excerpt: I'm interested in how climate and deglaciation dictate process and morphology of landscapes across timescales, from thousand-year deglacial climate change to modern, anthropogenic shifts.

overlay_color: "#000"
overlay_filter: "0.5"
overlay_image: /assets/images/DSC2877.JPG
actions:
- label: "Get Started"
url: "/test/"
permalink: /test/

feature_row:
- image_path: /assets/images/DSC2877.JPG
  title: "Remote sensing, Arctic Fans, and periglaical sediment transport"
  excerpt: "Arctic Fans in the Aklavik Range."
  url: "/research"
  btn_label: "Learn More"
  btn_class: "btn--primary"
- image_path: /assets/images/DSC2877.JPG
  title: "Paleoclimate and Paleosedimentation using Lakes"
  excerpt: "NSF proposal to look at lakes in Richardson mountains"
  url: "/research"
  btn_label: "Learn More"
  btn_class: "btn--primary"
- image_path: /assets/images/DSC2877.JPG
  title: "Kettle Lake Formation Lab experiments"
  excerpt: "Undergraduate project running lab experiments to study kettle lakes."
  url: "/research"
  btn_label: "Learn More"
  btn_class: "btn--primary"

feature_row2:
- image_path: /assets/images/Beaver_HouseSedimentation_1938.jpg
  title: "Plow vs Ice Age"
  excerpt: "Paper in Geology, project featured in Science Magazine"
  url: "/about"
  btn_label: "Explore"
  btn_class: "btn--primary"
- image_path: /assets/images/DSC2877.JPG
  title: "Post-glacial meltwater rerouting in the Upper Mississippi River"
  excerpt: "Using sediment cores to study glacial drainage reorganization during ice retreat."
  url: "/research"
  btn_label: "Explore"
  btn_class: "btn--primary"
- image_path: /assets/images/banners/UpsalaMountainsClouds.JPG
  title: "Collaborator projects, fluvial systems, and geochronology"
  excerpt: "Thioois is the first row."
  url: "/research"
  btn_label: "Learn More"
  btn_class: "btn--primary"

---

<p style="font-size: 1.5rem; font-weight: bold">Current Projects</p>
{% include feature_row id="feature_row" %}

<!-- Other content -->



**Past Projects**

{% include feature_row id="feature_row2" %}

Trying to add a carousel below

<div class="carousel">
  <div><img src="/assets/images/DSC2877.JPG" alt="Gallery 1"></div>
  <div><img src="/assets/images/DSC2877.JPG" alt="Gallery 2"></div>
  <div><img src="/assets/images/DSC2877.JPG" alt="Gallery 3"></div>
</div>

// /assets/js/slick-init.js
$(document).ready(function(){
$('.carousel').slick({
dots: true,
infinite: true,
speed: 500,
slidesToShow: 1,
autoplay: true,
autoplaySpeed: 3000
});
});

