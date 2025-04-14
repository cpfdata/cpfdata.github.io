---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: CPF - the easy way to harmonize panel data.
layout: splash
classes: wide
author_profile: false
header:
  overlay_color: "#5e616c"
  overlay_filter: 0.2
  overlay_image: /assets/images/head_bckgr_1.png
  actions:
    - label: "<i class='fas fa-download'></i> Download now"
      url: "/download/"
excerpt: >
  Comparative Panel File (CPF) is an open science project to harmonise the world’s major and longest-running household panel surveys from seven countries.<br/>
  <small><a href="/platform/">Latest release: v1.52</a></small>
intro: 
  - excerpt: 'CPF provides an open-source code to construct a comparative dataset based on the original data from the household panel surveys.<br/>
The multilevel panel data covering long periods and several general population surveys allow analysing individual trajectories, time trends, contextual effects and country differences. '

entries_layout: grid
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
    url: "/platform/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/working.png
    alt: "working with cpf"
    title: "Working with CPF"
    excerpt: "The CPF provides free of charge and full access to the programming code. Try it yourself!"
    url: "/working-with-cpf/"
    btn_class: "btn--primary"
    btn_label: "Learn more" 

gallery:
  - url: https://nidi.nl/en/
    image_path: /assets/images/nidi.svg
    alt: "nidi"
    title: "Netherlands Interdisciplinary Demographic Institute"
  - url: https://www.uni-koeln.de/en/
    image_path: /assets/images/cologne.png
    alt: "cologne"
    title: "University of Cologne"
  - url: https://www.tilburguniversity.edu/
    image_path: https://cdn.brandfetch.io/id-OjnWo8f/theme/dark/logo.svg?c=1dxbfHSJFAPEGdCLU4o5B
    alt: "Tilburg University"
    title: "Tilburg University"
  - url: https://www.lissdata.nl/
    image_path: /assets/images/liss.png
    alt: "LISS Panel"
    title: "LISS Panel"
  - url: https://www.lissdata.nl/
    image_path: /assets/images/norface.png
    alt: "Norface Network"
    title: "Norface Network"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

<div markdown="1" style="display: inline-block">

<h3 class="archive__subtitle">Recent Updates</h3>

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
{%- for post in posts -%}
  {% include archive-single.html type=entries_layout %}
{%- endfor -%}
{% include paginator.html %}

</div>
</div>

### Supported by
{: .text-center}
<div style="width: 70%; margin-left: auto; margin-right: auto;" markdown="1">

{% include gallery %}
</div>
