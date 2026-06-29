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

{% include figure.liquid loading="eager" path=page.img class="img-fluid rounded z-depth-1 d-block mx-auto" max-width="60%" caption=page.image_caption %}

Foundation models trained on collider jet data learn representations of jets that turn out to be useful outside their original domain. In this project, we study how well representations learned from jet physics transfer to neutrino interaction data from the MINERvA experiment, probing how much structure these models share across very different detector and physics regimes. Using foundation models trained on high-energy jets at the medium-energy MINERvA experiment leads to faster training and better performance achieved with the same amount of data.

Explore a sample of MINERvA events used in the study in the interactive event viewer, and check out the paper for more info.

<a href="https://d1to0n5578l1po.cloudfront.net/event_viewer.html" target="_blank" class="d-inline-block px-4 py-2 mt-2 mb-2 mr-2" style="background: linear-gradient(135deg, #11998e, #38ef7d); color: #fff; border-radius: 50px; font-weight: 600; text-decoration: none; box-shadow: 0 4px 10px rgba(17, 153, 142, 0.4);">🔭 Explore the event viewer</a>
<a href="https://arxiv.org/abs/2604.12364" target="_blank" class="d-inline-block px-4 py-2 mt-2 mb-2 mr-2" style="background: linear-gradient(135deg, #ff7e5f, #feb47b); color: #fff; border-radius: 50px; font-weight: 600; text-decoration: none; box-shadow: 0 4px 10px rgba(255, 126, 95, 0.4);">📄 Read the paper</a>
<a href="https://github.com/gregorkrz/minerva-ml/" target="_blank" class="d-inline-block px-4 py-2 mt-2 mb-2" style="background: linear-gradient(135deg, #36454f, #1c1c1c); color: #fff; border-radius: 50px; font-weight: 600; text-decoration: none; box-shadow: 0 4px 10px rgba(0,0,0,0.4);">💻 View the code</a>
