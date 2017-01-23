---
title: index
date: 2017-01-20 17:09:00 Z
Slogan: Slogan lorem ipsum
Tuotanto: Tuotanto lorem ipsum
pic_image: "/uploads/map-marker-black.png"
pic2_image: "/uploads/261037main_04_ViewofAtlantis_1600-1200.jpg"
pic3_image: 
---

Index-siteleaf3

{% for image in site.static_files %}
    {{ image.path }}
    <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
{% endfor %}
