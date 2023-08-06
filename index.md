---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Open Source Hardware Tools"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
excerpt: "Building Open Hardware is difficult. This site is a collection of tools that make designing, collaborating on, and distributing Open Hardware easier."
intro: 
  - excerpt: 'Open source software has an incredibly mature development and distribution ecosystem. This site is broken into three broad subsections around the tools needed to support the **other** aspects of an open hardware project: ECAD, MCAD, and communication.'
feature_row:
  - image_path: assets/ecad.jpg
    alt: "placeholder image 1"
    title: "ECAD"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "ecad"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/mcad.png
    alt: "placeholder image 2"
    title: "MCAD"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "mcad"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Communication"
    excerpt: "Tools for community discussion, sharing updates, and general publication"
    url: "comm"
    btn_label: "See Tools"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/opulo.png
    alt: "placeholder image 2"
    title: "Used in Practice"
    excerpt: "The tools used on this site aren't just ideas; these are systems that are used every day by open source hardware companies."
    url: "https://www.opulo.io/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="center" %}
