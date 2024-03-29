---
title: "Simulation of European Politics"
layout: splash
permalink: /
date: 2017-04-11 01:48:41 -04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-meu2015.jpg
  caption: "Photo credit: [**MEUS 2015**](http://www.meu-strasbourg.org)"
excerpt: "Bringing Europeans Together Association France, BETA France for short, is a politically independent and non-profit association to support the organisation of European politics simulations in France."
intro: 
  - excerpt: 
    |
      To foster a European identity and consciousness based on plurality, tolerance and cooperation between individuals, as well as strengthening the European civil society by further developing democratic processes on the national and international levels. To establish sustainable administrative structures that ensure the success of the [Model European Union (MEU) event in Strasbourg](http://www.meu-strasbourg.org) and other similar events.

feature_columns:
  - image_path: assets/images/BETA FR BOARD.jpg
    alt: "placeholder image 1"
    title: "The Board"
    excerpt: "Find more about our current Board for the executive year 2017/2017."
    url: "https://france.beta-europe.org/about/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/BETA France logo.png
    alt: "placeholder image 2"
    title: "BETA France"
    excerpt: "BETA France is a French association which organise Model European Union Strasbourg."
    url: "https://france.beta-europe.org/about/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/MEUS17.jpg
    title: "MEU Strasbourg"
    excerpt: "Model European Union Strasbourg is the authoritative simulation of EU politics, taking place every spring in Strasbourg."
    url: "http://www.meu-strasbourg.org"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row4:
  - image_path: /assets/images/26991590_382993795475551_3357006096555076980_n.jpg
    alt: "placeholder image 2"
    title: "Please welcome MEU PARIS!"
    excerpt: 'BETA France is proud to announce its brand new project: Model European Union Paris. The first MEU conference in the French Capital.'
    url: "https://www.facebook.com/ModelEUParis/"
    btn_label: "Learn More"
    btn_class: "btn--inverse"
---

{% include feature_row id="intro"  type="center" %}


{% include feature_row id="feature_columns" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}


<div class="layout--splash__recent--posts">
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
</div>
