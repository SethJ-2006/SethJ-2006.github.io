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
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Built multiple prototypes and a published jam game."
    year: 1
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI"]
    text: "Designed mechanics, levels, and player feedback loops."
    level_label: "Beginner"
  - name: "Project Management"
    icon: "fa-brands fa-microsoft"
    badges: ["Office 365", "Miro"]
    text: "Made use of project management software for group project work."
    level_label: "Experienced"
  - name: "Pixel Art"
    icon: "fa-solid fa-palette"
    badges: ["Libresprite"]
    text: "Created pixel art sprites to be used in Unity project."
    level_label: "Beginner"
---

{% include feature_row id="intro" type="center" %}



{% include skills skills=page.skills %}
