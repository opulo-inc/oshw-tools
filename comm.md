---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# <span class="badge badge-primary">Github CI</span>
#<span class="badge badge-secondary">Web Service</span>
#<span class="badge badge-success">Open Source</span>
#<span class="badge badge-danger">Paid Service</span>
#<span class="badge badge-info">Free Service</span>

title: "Communication Tools"
layout: single
header:
  overlay_color: "#000"
  overlay_filter: "0.65"
  overlay_image: /assets/feature.jpg
  caption: "Photo credit: **Tobias Netzer**"
sidebar:
  nav: "comm"
---

## Docs

### [Github Pages](https://pages.github.com/)
<span class="badge badge-primary">Github CI</span><span class="badge badge-info">Free Service</span>

Regardless of the static site generator you choose, using Github Pages as the hosting service for your documentation is a great choice. It is free to deploy, completely automatic after your CI script is set, and there's tons of documentation around getting started. Plus, managing your documentation in git means it's incredibly easy to manage docs release alongside product updates.

### MKDocs
<span class="badge badge-success">Open Source</span><span class="badge badge-primary">Github CI</span>

MKDocs is by far the easiest and most straightforward to get beautiful documentation on the web. Accepting garden-variety Markdown as the copy format, it's dead simple to write for, and the results look spectacular. MKDocs also is [very easily deployable](https://github.com/opulo-inc/docs/blob/main/.github/workflows/ci.yaml) using Github Pages, so a simple `git push origin main` will deploy your doc instructions to production. Fixing a bug on the site can literally be a less than a minute ordeal.

### [AutoBOM](https://github.com/opulo-inc/lumenpnp/blob/main/.github/workflows/export-bom.yaml) (Opulo's BOM Generator)
<span class="badge badge-success">Open Source</span><span class="badge badge-primary">Github CI</span>

AutoBOM is a series of Python scripts and CI builds developed by Opulo that automatically exports a standalone downloadable webpage Bill of Materials based on a GitHub repo. AutoBOM expects to find an up-to-date `bom.csv` file in the repo's root directory, and that source files are made with FreeCAD and KiCAD. The BOM will even include rendered images of all FreeCAD files and KiCAD PCBs included in the `bom.csv`. You can see an example by downloading the BOM.zip file attached to the most recent release [here](https://github.com/opulo-inc/feeder/releases/).

## Discussion

### [Discord](https://discord.com/)
<span class="badge badge-info">Free Service</span>

Discord is effectively a nice UI wrapped around the basics of IRC. Many communities have flocked to Discord as a place for conversation over the past 5 years, and in response Discord recently released a number of community-specific features that make this even easier. Some pithy features are gated behind a paywall, but the basic communication functionality is fantastic for building an engaged community. Given that it's real-time text communication, discussions can happen much faster than in something like a forum.

### [Discourse](https://www.discourse.org/)
<span class="badge badge-success">Open Source</span><span class="badge badge-info">Free Service</span>

Discourse is the best way to build your own forum. Although conversation might happen a bit slower in a forum rather than a Discord server, the results of discussions are highly searchable, and a forum setting is more familiar to some folks than a real-time chat app.

## Mods

### [Github](https://github.com/) - Dedicated Mods Repo
<span class="badge badge-info">Free Service</span>

through the repo and a pr, give example of [Voron mods page](https://mods.vorondesign.com/)

or through wiki, permissions are a thing

both generally need approval of some kind, unless you let anyone merge

### [Notion](https://www.notion.so/) - Community Mod Page
<span class="badge badge-danger">Paid Product</span>

[opulo mods page](https://mods.opulo.io/)
