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

{% include figure.liquid loading="eager" path=page.img class="img-fluid rounded z-depth-1 d-block mx-auto" caption=page.image_caption %}

HitPF is an end-to-end, Geometric Algebra Transformer-based particle flow reconstruction pipeline for that works directly on detector hits and tracks. By learning reconstruction directly from raw hits rather than hand-engineered intermediate objects, the approach aims to push the precision of event reconstruction beyond what classical particle flow algorithms achieve. By decoupling reconstruction performance from detector-specific tuning, this framework enables rapid iteration during the detector design phase of future collider experiments.

Run the algorithm yourself on any event on Hugging Face, and check out the paper for more info.

<a href="https://huggingface.co/spaces/gregorkrzmanc/HitPF_demo" target="_blank" class="d-inline-block px-4 py-2 mt-2 mb-2 mr-2" style="background: linear-gradient(135deg, #f6d365, #fda085); color: #fff; border-radius: 50px; font-weight: 600; text-decoration: none; box-shadow: 0 4px 10px rgba(253, 160, 133, 0.4);">🤗 Try the live demo</a>
<a href="https://arxiv.org/pdf/2603.04084" target="_blank" class="d-inline-block px-4 py-2 mt-2 mb-2" style="background: linear-gradient(135deg, #ff7e5f, #feb47b); color: #fff; border-radius: 50px; font-weight: 600; text-decoration: none; box-shadow: 0 4px 10px rgba(255, 126, 95, 0.4);">📄 Read the paper</a>
