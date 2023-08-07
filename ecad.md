---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# <span class="badge badge-primary">Github</span><span class="badge badge-secondary">Github</span><span class="badge badge-success">Github</span><span class="badge badge-danger">Github</span><span class="badge badge-info">Github</span>

title: "ECAD Tools"
layout: single
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
sidebar:
  nav: "ecad"
---

## Design

### KiCAD
<span class="badge badge-success">Open Source</span>

With ECAD software, there's really only one serious option: KiCAD. KiCAD is a powerful, professional PCB design package. It has a vast plugin system, and being open source means it has a ton of automation potential. Lots of the other tools on this page rely on the fact that KiCAD is the EDA of choice.

## Automation

### [KiBot](https://github.com/INTI-CMNB/KiBot)
<span class="badge badge-success">Open Source</span><span class="badge badge-primary">Github CI</span>

KiBot is an export tool for KiCAD designs. KiBot is capable of exporting gerbers of your board, 3D models, images, stencils, and even run ERC/DRC a final time before export.

KiBot is great for automating the export of gerber files on release, or when run manually in GitHub. It can also help with exporting images of PCBs for documentation purposes. For example, Opulo feeders have a [CI workflow](https://github.com/opulo-inc/feeder/blob/main/.github/workflows/export-ecad.yaml) that automatically exports all feeder PCBs for easy community use and reference.

### [KiKit](https://github.com/yaqwsx/KiKit)
<span class="badge badge-success">Open Source</span><span class="badge badge-primary">Github CI</span>

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
<span class="badge badge-success">Open Source</span><span class="badge badge-info">Free Service</span>

Embedded support soon
[example](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fopulo-inc%2Ffeeder%2Ftree%2Fmain%2Fpcb%2Fmobo)

### [Tracespace](https://tracespace.io/view/)
<span class="badge badge-info">Free Service</span>


