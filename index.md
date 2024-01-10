---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Midscale Manufacturing Resources"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
excerpt: "Building hardware is difficult. This site is a collection of tools and information that make designing, collaborating on, and distributing hardware at a Midscale easier."
intro: 
  - excerpt: 'This site is broken into five broad subsections around the tools needed to support the aspects of a midscale, open hardware project: ECAD, MCAD, manufacturing, certification, and communication.'
feature_row:
  - image_path: assets/ecad.jpg
    alt: "placeholder image 1"
    title: "ECAD"
    excerpt: "Tools and software used for easing the development of open source ECAD"
    url: "ecad"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/mcad.png
    alt: "placeholder image 2"
    title: "MCAD"
    excerpt: "Tools and software used for easing the development of open source MCAD"
    url: "mcad"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/mfg.png
    title: "Manufacturing"
    excerpt: "Tools and software for actually manufacturing your open source design"
    url: "mfg"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/certs.jpeg
    title: "Certification"
    excerpt: "Information around getting your product certified in the ways it's required. NOT LEGAL ADVICE."
    url: "certs"
    btn_label: "See Info"
    btn_class: "btn--primary"
  - image_path: /assets/comm.png
    title: "Communication"
    excerpt: "Tools for community discussion, sharing updates, and general publication"
    url: "comm"
    btn_label: "See Tools"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
