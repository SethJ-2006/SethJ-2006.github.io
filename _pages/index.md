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


excerpt: "Enthusiastic, resilient, and capable - I'll give any work my all."
intro: 
  - excerpt: 'A list of my current skills are described below.' 
skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Created multiple prototypes in both 2D and 3D."
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
    text: <a href="https://sethj-2006.github.io/gallery/" rel="noopener noreferrer">Click Here for Examples</a>
    level_label: "Beginner"
feature_row:
  - image_path: /assets/images/gallery/Feral_Title_Logo.png
    alt: "Logo for my group project game, Feral."
    title: "Feral - 2D Group Project"
    excerpt: "A 2D Platformer created as part of a group."
    url: /projects/2d-games/
    btn_label: "Learn more"
    btn_class: "btn--primary"
  - image_path: /assets/images/gallery/Sprite-GDD_Action_Card.png
    alt: "Icon for physical board game"
    title: "Nyaight on the Town - Physical Board Game"
    excerpt: "A standard boardgame created for a university project."
    url: /projects/board-games/
    btn_label: "Learn more"
    btn_class: "btn--primary"
---
<div style="text-align: center; border: 2px solid grey; padding: 2px;">
  {% include button url="/about-me/" label="Learn more about me." class="btn--primary" %}
</div>

{% include skills skills=page.skills %}

<br>
{% include feature_row id="intro" type="center" %}
<br>
