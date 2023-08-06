---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "ECAD Tools"
layout: single
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
excerpt: "Building Open Hardware is difficult. This site is a collection of tools that make designing, collaborating on, and distributing Open Hardware easier."
sidebar:
  nav: "ecad"
---

## Design

### KiCAD

here i am talking about things

## Automation

### [KiBot](https://github.com/INTI-CMNB/KiBot)
lots of exports, gerbers, images, 
[example for feeders](https://github.com/opulo-inc/feeder/blob/main/.github/workflows/export-ecad.yaml)

### [KiKit](https://github.com/yaqwsx/KiKit)
Mainly for panelization, can also export

```
kikit panelize 
  --layout 'grid; rows: 2; cols: 3;'
  --tabs 'full'
  --cuts 'vcuts'
  --source 'tolerance: 10mm'
  --post 'millradius: 0.5mm;'
  input.kicad_pcb output.kicad_pcb
```

## Sharing

### [KiCanvas](https://kicanvas.org/)
Embedded support soon
[example](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fopulo-inc%2Ffeeder%2Ftree%2Fmain%2Fpcb%2Fmobo)

### [Tracespace](https://tracespace.io/view/)


