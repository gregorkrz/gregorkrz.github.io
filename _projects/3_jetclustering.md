---
layout: page
title: Semi-Visible Jet Clustering
description: Learning IRC-safe jet clustering with Geometric Algebra Transformers
img: assets/img/jetclustering.png
importance: 3
category: work
related_publications: true
image_caption: An event display containing two semi-visible jets (left) and a loss potential landscape for one of the particles (right). The particle is pulled towards Jet 1 and pushed away from Jet 2 in the virtual clustering space.
---

{% include figure.liquid loading="eager" path=page.img class="img-fluid rounded z-depth-1 d-block mx-auto" max-width="80%" caption=page.image_caption %}

We use Lorentz-equivariant Geometric Algebra Transformers to learn jet clustering algorithms that remain infrared- and collinear-safe, with an eye towards reconstructing semi-visible jets, where part of the jet's energy escapes into invisible or weakly-interacting particles. Learning the clustering directly lets the model adapt to these harder topologies. The models outperform anti-kt, the usual jet clustering algorithm used at the Large Hadron Collider (LHC) experiments.

<a href="https://ml4physicalsciences.github.io/2025/files/NeurIPS_ML4PS_2025_59.pdf" target="_blank" class="d-inline-block px-4 py-2 mt-2 mb-2" style="background: linear-gradient(135deg, #ff7e5f, #feb47b); color: #fff; border-radius: 50px; font-weight: 600; text-decoration: none; box-shadow: 0 4px 10px rgba(255, 126, 95, 0.4);">📄 Read the paper</a>
