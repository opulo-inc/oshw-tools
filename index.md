---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Midscale Manufacturing"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
excerpt: "Midscale is the volume of manufacturing between prototyping and mass production. It's the chasm that keeps many projects from becoming a successful enterprise. This site aims to help you cross that chasm."
intro: 
  - excerpt: 'This site is broken into five broad subsections around the tools needed to support the aspects of a midscale, open hardware project: design, manufacturing, documentation, and certification.'
feature_row:
  - image_path: assets/ecad.jpg
    alt: "placeholder image 1"
    title: "Design"
    excerpt: "Tools and software used for easing the development of open source hardware"
    url: "design"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/mfg.png
    title: "Manufacturing"
    excerpt: "Tools and software for actually manufacturing your open source design"
    url: "mfg"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/comm.png
    title: "Documentation"
    excerpt: "Tools for formal docs, community discussion, sharing design files, and automatically exporting."
    url: "docs"
    btn_label: "See Tools"
    btn_class: "btn--primary"
  - image_path: /assets/certs.jpeg
    title: "Certification"
    excerpt: "Information around getting your product certified [NOT LEGAL ADVICE]"
    url: "certs"
    btn_label: "See Info"
    btn_class: "btn--primary"
  

---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
