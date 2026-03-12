---
title: "Portfolio"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/placeholder.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1ePqrAcar-abcMBgLCd7uo0HUbZDd929t/preview"
      target: "_blank"


excerpt: "You can add text here."
  intro: 
  - excerpt: 'You can also add text like this....'
  feature_row:
  - image_path: /assets/images/placeholder.png
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/placeholder.png
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/placeholder.png
    alt: "placeholder image 4"
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  skills:
  - name: "Unity"
      icon: "fab fa-fw fa-unity"
      badges: ["C#", "3D Greybox", "2D Level Design"]
      text: "Built multiple prototypes."
  - name: "Game Art"
      badges: ["Libresprite", "Probuilder"]
      text: "Created basic sprite art to use in Unity projects.
      level_label: "Beginner"
      url: /gallery/
      btn_label: "See Examples"
      btn_class: "btn--primary"
  - name: "Game Design"
      icon: "fas fa-fw fa-gamepad"
      badges: ["Game Mechanics", "Levels", "UI"]
      text: "Designed mechanics, levels, and player feedback loops."
      level_label: "Beginner"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include skills skills=page.skills %}
