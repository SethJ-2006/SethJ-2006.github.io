---
title: "Portfolio"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/Screenshots/3d_screenshot_island.png
  actions:
    - label: "Download CV"
      url: "https://ulster-my.sharepoint.com/:b:/r/personal/mcardle-s17_ulster_ac_uk/Documents/CRE136/CV_Download.pdf?csf=1&web=1&e=WPYimb"
      target: "_blank"


excerpt: "Welcome to my Portfolio website."
intro: 
  - excerpt: 'A list of my current skills are described below.' 
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
    text: <a href="https://sethj-2006.github.io/gallery/" rel="noopener noreferrer">See Examples</a>
    level_label: "Beginner"
---
{% include button url="/about-me/" label="Who am I?" class="btn--primary" %}
{% include feature_row id="intro" type="center" %}



{% include skills skills=page.skills %}
