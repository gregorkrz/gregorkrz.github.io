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

{% include figure.liquid loading="eager" path=page.img class="img-fluid rounded z-depth-1" caption=page.image_caption %}

We use Lorentz-equivariant Geometric Algebra Transformers to learn jet clustering algorithms that remain infrared- and collinear-safe, with an eye towards reconstructing semi-visible jets, where part of the jet's energy escapes into invisible or weakly-interacting particles. Learning the clustering directly lets the model adapt to these harder topologies. The models outperform anti-kt, the usual jet clustering algorithm used at the Large Hadron Collider (LHC) experiments.

{% cite Krzmanc2025IRCSafe %}
