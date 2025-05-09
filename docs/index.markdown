---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: CPF - the easy way to harmonize panel data.
layout: splash
classes: wide
author_profile: false
header:
  overlay_color: "#0092ca"
  overlay_filter: 0.4
  overlay_image: /assets/images/head_bckgr_2.png
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
    excerpt: "CPF combines data from 7 countries, 2.7 million observations from almost 360,000 respondents."
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
  - url: https://nwo.nl/
    image_path: /assets/images/nwo.png
    alt: "NWO"
    title: "NWO"
  - url: https://www.lissdata.nl/
    image_path: /assets/images/norface.png
    alt: "Norface Network"
    title: "Norface Network"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

<!-- modify this form HTML and place wherever you want your form -->
<section id="cta" class="wrapper style3" markdown="1">


## Subscribe to our Mailing List!
{: .text-center}

<form
  action="https://formspree.io/f/mjkyjgkd"
  method="POST"
class="container"
>
<div class="row">

  <div class="col-5 col-6-narrow col-12-mobilep">

      <input type="text" name="name" id="name" placeholder="Your Name">
  </div>

  <div class="col-5 col-6-narrow col-12-mobilep">
      <input type="email" name="email" id="email" placeholder="Your E-mail">
  </div>

  <!-- your other form fields go here -->
  <div class="col-2 col-12-narrow col-12-mobilep">

    <input type="submit" class="button alt" value="Send"> 
  </div>

</div>

</form>

</section>


<div markdown="1" style="display: flow-root">

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

<div class="container">
    <div class="row sponsors">
      <section class="col-2 col-4-narrower">
        <a href="https://nidi.nl/en/" class=""><img src="/assets/images/nidi.svg" alt=""></a>
      </section>
      <section class="col-2 col-4-narrower">
        <a href="https://www.uni-koeln.de/en/" class="image"><img src="/assets/images/cologne.png" alt=""></a>
      </section>
      <section class="col-2 col-4-narrower">
        <a href="https://www.tilburguniversity.edu/" class="image"><img src="https://cdn.brandfetch.io/id-OjnWo8f/theme/dark/logo.svg?c=1dxbfHSJFAPEGdCLU4o5B" alt=""></a>
      </section>
      <section class="col-2 col-4-narrower">
        <a href="https://www.lissdata.nl/" class="image"><img src="/assets/images/liss.png" alt=""></a>
      </section>
      <section class="col-2 col-4-narrower">
        <a href="https://nwo.nl/" class="image"><img src="/assets/images/nwo.png" alt=""></a>
      </section>
      <section class="col-2 col-4-narrower">
        <a href="https://www.norface.net/" class="image"><img src="/assets/images/norface.png" alt=""></a>
      </section>
    </div>
  </div>
</div>
