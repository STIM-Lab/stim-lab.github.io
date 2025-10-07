---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/vascular_splash.jpg
  actions:
    - label: "University of Houston"
      url: "https://www.ece.uh.edu/"
  caption: "Mouse brain microvessels imaged using KESM"
excerpt: "**Developing instruments and algorithms to build whole-organ tissue models at sub-cellular resolution**"
intro: 
  - excerpt: '**Mathematical science shows what is. It is the language of unseen relations between things.** --Ada Lovelace'
  - excerpt: '**Luck is statistics taken personally.** --Penn Jillette'
feature_row:
  - image_path: assets/images/teasers/2025_tvote_isbi.jpg
    image_caption: "Retinal fundus images reconstructed using tensor voting"
    alt: "retinal fundus image processed using tensor voting"
    title: "IEEE ISBI 2025"
    excerpt: |-
      **Closed-Form GPU-Accelerated Tensor Voting With Refinement**  
      *Helya Goharbavang, et al.*
    url: "https://doi.org/10.1109/ISBI60581.2025.10980718"
    btn_label: "DOI"
    btn_class: "btn--primary"

  - image_path: /assets/images/teasers/2025_rsf_isbi.png
    alt: "reconstructed microvessels"
    image_caption: "Mouse microvessels reconstructed using active contours"
    title: "IEEE ISBI 2025"
    excerpt: |-
      **Segmentation of Microvascular Networks Embedded in Gigavoxel 3D Images Using RSF Level Sets With OpenVDB**  
      *Meher Niger, et al.*
    url: "https://doi.org/10.1109/ISBI60581.2025.10980653"
    btn_label: "DOI"
    btn_class: "btn--primary"

  - image_path: /assets/images/teasers/2025_qdots_plos.jpg
    title: "PLOS ONE"
    excerpt: |-
      **Fast Photostable Expansion Microscopy Using QDots and Deconvolution**  
      *Dilani Gunawardhana, et al.*
    image_caption: "Mouse astrocytes labeled using quantum dots"
    url: "https://doi.org/10.1371/journal.pone.0325155"
    btn_label: "Open Access"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/images/teasers/2025_holography.jpg
    alt: "chemical holography instrumentation"
    title: "IEEE Photonics Journal"
    excerpt: |-
      **Enabling Chemical Holography: A Comprehensive Framework and Implementation**  
      *Shihao Ran, David Mayerich, Rohith Reddy*
    url: "https://doi.org/10.1109/JPHOT.2025.3567016"
    btn_label: "Open Access"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/images/teasers/2025_jbo_cover.jpg
    alt: "placeholder image 2"
    title: "Journal of Biomedical Optics"
    excerpt: |-
      **Multimodal optical coherence tomography and two-photon light-sheet fluorescence microscopy for embryo imaging**  
      *Md Mobarak Karim, Ruijiao Sun, Behzad Khajavi, Manmohan Singh, Yogeshwari S. Ambekar, Alexander W. Schill, David Mayerich, Kirill Larin*
    url: "https://doi.org/10.1117/1.JBO.30.6.060501"
    btn_label: "DOI"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

# Recent Publications
{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}