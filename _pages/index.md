---
layout: splash
author_profile: true
excerpt: "Where you'll find everything data-related to MotoGP"
header:
  overlay_image: /assets/images/DP26.jpg
  overlay_filter: 0.5 
  caption: "Photo credit: **Getty Images**"
intro: 
  - excerpt: 'Welcome to my site where you’ll find my MotoGP data analyses. Each piece is crafted with great affection and passion, not just for the sport, but also for data and programming. Dive in and explore the exciting intersection of MotoGP and data science!'
feature_row:
  - image_path: assets/images/ducati.png
    title: "Analyses"
    excerpt: "Here you can find my **latest** analyses"
    url: "analyses/"
    btn_label: "Activity"
    btn_class: "btn--primary"
  - image_path: assets/images/pedrosa.png
    alt: "placeholder image 2"
    title: "About me"
    excerpt: "Get to know me a little more in-depth"
    url: "about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/git.png
    title: "Like what you see?"
    excerpt: "Consider giving the Github repository a star!"
    url: "https://github.com/IUrreta/MotoGPace"
    btn_label: "Repository"
    btn_class: "btn--primary"
permalink: /
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}