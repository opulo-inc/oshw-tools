---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# <span class="badge badge-primary">Github</span><span class="badge badge-secondary">Github</span><span class="badge badge-success">Github</span><span class="badge badge-danger">Github</span><span class="badge badge-info">Github</span>

title: "Design Tools"
layout: single
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
sidebar:
  nav: "design"
---

## Electrical

### [KiCAD](https://www.kicad.org/)
<span class="badge badge-success">Open Source</span>

With ECAD software, there's really only one serious option: KiCAD. KiCAD is a powerful, professional PCB design package. It has a vast plugin system, and being open source means it has a ton of automation potential. Lots of the other tools on this page rely on the fact that KiCAD is the EDA of choice.

### [WireViz](https://github.com/wireviz/WireViz)
<span class="badge badge-success">Open Source</span>

![](/assets/wireviz.png)

WireViz is a fantastic way to document your cables and wire harnesses. Using a simple YAML file, you can define complex cable harness assemblies in a git-trackable filetype, and easily export beautiful graphical output for an engineering drawing or assembly technician.

## Mechanical

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
