---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: CPF - the easy way to harmonize panel data.
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: 0.8
  overlay_image: /assets/images/map.webp
  actions:
    - label: "<i class='fas fa-download'></i> Download now"
      url: "/download/"
excerpt: >
  Comparative Panel File (CPF) is an open science project to harmonise the world’s major and longest-running household panel surveys from seven countries.<br/>
  <small><a href="https://www.cpfdata.com/platform/">Latest release: v1.52</a></small>
intro: 
  - excerpt: 'CPF provides an open-source code to construct a comparative dataset based on the original data from the household panel surveys.<br/>
The project aims to support the community of sociologists, demographers and other researchers interested in comparative life course studies.<br/>
The multilevel panel data covering long periods and several general population surveys allow analysing individual trajectories, time trends, contextual effects and country differences. '

feature_row:
  - image_path: /assets/images/mm-customizable-feature.png
    alt: "customizable"
    title: "Super customizable"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/docs/configuration/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-responsive-feature.png
    alt: "fully responsive"
    title: "Responsive layouts"
    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-free-feature.png
    alt: "100% free"
    title: "100% free"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
