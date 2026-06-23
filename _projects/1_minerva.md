---
layout: page
title: Cross-Domain Transfer with Particle Physics Foundation Models
description: Transferring jet foundation models to MINERvA neutrino interactions
img: assets/img/minerva-cc1pi0-event-display.png
importance: 1
category: work
related_publications: true
image_caption: Reconstructed picture of a CC1π⁰ event from MINERvA Open Data. The π⁰ decays into two photons sharing the same vertex.
---

{% include figure.liquid loading="eager" path=page.img class="img-fluid rounded z-depth-1" caption=page.image_caption %}

Foundation models trained on collider jet data learn representations of jets that turn out to be useful outside their original domain. In this project, we study how well representations learned from jet physics transfer to neutrino interaction data from the MINERvA experiment, probing how much structure these models share across very different detector and physics regimes. Using foundation models trained on high-energy jets at the medium-energy MINERvA experiment leads to faster training and better performance achieved with the same amount of data.

Explore a sample of MINERvA events used in the study in the [interactive event viewer](https://d1to0n5578l1po.cloudfront.net/event_viewer.html).

{% cite Krzmanc2026CrossDomain %}
