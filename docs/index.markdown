---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: CPF - the easy way to harmonize panel data.
layout: splash
classes: wide
header:
  overlay_color: "#5e616c"
  overlay_filter: 0.8
  overlay_image: /assets/images/map.webp
  actions:
    - label: "<i class='fas fa-download'></i> Download now"
      url: "/download/"
excerpt: >
  Comparative Panel File (CPF) is an open science project to harmonise the world’s major and longest-running household panel surveys from seven countries.<br/>
  <small><a href="/platform/">Latest release: v1.52</a></small>
intro: 
  - excerpt: 'CPF provides an open-source code to construct a comparative dataset based on the original data from the household panel surveys.<br/>
The project aims to support the community of sociologists, demographers and other researchers interested in comparative life course studies.<br/>
The multilevel panel data covering long periods and several general population surveys allow analysing individual trajectories, time trends, contextual effects and country differences. '

feature_row:
  - image_path: /assets/images/data.jpg
    alt: "data"
    title: "Global Data"
    excerpt: "CPF combines data from seven countries, includes 2.7 million observations from almost 360 thousand respondents."
    url: "/data/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/platform.jpeg
    alt: "platform"
    title: "Open Science Platform"
    excerpt: "We encourage open access and community-based development - anyone can contribute to the project."
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/working.png
    alt: "working with cpf"
    title: "Working with CPF"
    excerpt: "The CPF provides free of charge and full access to the programming code. Try it yourself!"
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}


