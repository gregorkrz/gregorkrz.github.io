---
layout: page
title: HitPF
description: End-to-end hit-level particle flow reconstruction for future colliders
img: assets/img/HitPF.png
importance: 2
category: work
related_publications: true
image_caption: A sample event display, colored by the true particles (left), particles predicted by HitPF (middle), and particles predicted by the baseline Pandora (right). HitPF is able to better reconstruct nearby photon showers (A) and link calorimeter clusters with the correct tracks (B). Figure from the paper.

---

{% include figure.liquid loading="eager" path=page.img class="img-fluid rounded z-depth-1" caption=page.image_caption %}

HitPF is an end-to-end, Geometric Algebra Transformer-based particle flow reconstruction pipeline for that works directly on detector hits and tracks. By learning reconstruction directly from raw hits rather than hand-engineered intermediate objects, the approach aims to push the precision of event reconstruction beyond what classical particle flow algorithms achieve. By decoupling reconstruction performance from detector-specific tuning, this framework enables rapid iteration during the detector design phase of future collider experiments.

Run the algorithm yourself on any event [on Hugging Face](https://huggingface.co/spaces/gregorkrzmanc/HitPF_demo) and see the [paper](https://arxiv.org/pdf/2603.04084) for more info.
