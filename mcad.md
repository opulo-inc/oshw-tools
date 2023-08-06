---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# <span class="badge badge-primary">Github CI</span><span class="badge badge-secondary">Web Service</span><span class="badge badge-success">Open Source</span><span class="badge badge-danger">Github</span><span class="badge badge-info">Github</span>

title: "MCAD Tools"
layout: single
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
excerpt: "Building Open Hardware is difficult. This site is a collection of tools that make designing, collaborating on, and distributing Open Hardware easier."
sidebar:
  nav: "mcad"
---

## Design

Design tools

### FreeCAD
<span class="badge badge-success">Open Source</span><span class="badge badge-primary">Github CI</span>

FreeCAD is the most mature, stable, and fully-featured open source mechanical cad package. It has the traditional user experience of other desktop CAD software instead of being software-defined like most other open MCAD suites.

FreeCAD can be easy to learn, but feature trees are notoriously fragile due to the [Topological Naming Problem](https://wiki.freecad.org/Topological_naming_problem). The most consistent way to deal with this issue is to use a Direct Modeling methodology, as opposed to a Parametric one. The main [difference between the two](https://3space.com/parametric-vs-direct-modeling/) is that Direct Modeling does not go back in the feature tree, only ever adding on new cuts and extrudes. It is also possible to have parametric designs in FreeCAD with [careful use of datum planes](https://wiki.freecad.org/Topological_naming_problem#Solution).

This being said, this issue is actively being addressed by the FreeCAD community, and the [open-core](https://en.wikipedia.org/wiki/Open-core_model) company [Ondsel](https://ondsel.com/blog) based on the FreeCAD project.

### [OpenSCAD](https://openscad.org/)
<span class="badge badge-success">Open Source</span>


### [CADQuery](https://cadquery.readthedocs.io/en/latest/)
<span class="badge badge-success">Open Source</span>

### Blender
<span class="badge badge-success">Open Source</span>

can only run CI in the way that it can render an existing .blend file, doesnt seem to be able to edit that .blend file at all

## Automation

MCAD automation tools are mostly geared towards exporting as STLs or STEPs for 3D printing, or rendering an image for viewing/BOM usage. Open CAD packages like FreeCAD, OpenSCAD, and CADQuery take the most advantage of this, handling all exports using their CLI interfaces. Proprietary tools can take advantage of automatic rendering by first exporting to an interchange format. See bulk exporting for [Fusion360](https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/How-to-export-specific-bodies-in-a-file-to-a-STEP-file-from-Fusion-360.html) and [Solidworks](https://help.solidworks.com/2023/english/WhatsNew/c_wn2023_import_export_assembly_step.htm?id=4dca041efcda481ca1e9f214d4725333#:~:text=You%20can%20export%20large%20SOLIDWORKS,assemblies%20as%20atomic%20STEP%20files.).

### FreeCAD STL Export
<span class="badge badge-success">Open Source</span><span class="badge badge-primary">Github CI</span>

### OpenSCAD STL Rendering
<span class="badge badge-success">Open Source</span><span class="badge badge-primary">Github CI</span>

[OpenSCAD CLI Manual](https://en.wikibooks.org/wiki/OpenSCAD_User_Manual/Using_OpenSCAD_in_a_command_line_environment)

```
openscad 
  -o part.png
  --colorscheme BeforeDawn
  --imgsize 512,512
  --quiet --render --projection=o --viewall --hardwarnings
  ./part.scad
```

### Blender .blend Rendering

[CLI rendering in Blender](https://docs.blender.org/manual/en/latest/advanced/command_line/render.html)

## Sharing

### 3dviewer.net
<span class="badge badge-info">Free Service</span>


### Onsdel
<span class="badge badge-info">Free Service</span>


[example](https://lens.ondsel.com/share/64ce90f8113f02d63fdbff2b)