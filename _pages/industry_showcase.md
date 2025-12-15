---
title: Industrial Showcases
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: https://cvis2021.weebly.com/uploads/5/6/3/0/56308869/background-images/236520036.jpg
permalink: /industrial-showcase
toc: true
toc_label: "On This Page"
toc_icon: "list"
---

<div class="sponsors-wrapper" markdown="1">

We are proud to showcase our industry partners who support CVIS 2025.

Interested sponsors are encouraged to contact <a href="mailto:{{ site.email }}">{{ site.email }}</a>

## Platinum Sponsors

<div class="sponsor-grid">
  {% for sponsor in site.data.sponsors.platinum %}
    <div class="sponsor-item">
      <a href="{{ sponsor.url }}" target="_blank" rel="noopener noreferrer">
        <img src="{{ sponsor.image_path | relative_url }}" alt="{{ sponsor.alt }}" title="{{ sponsor.title }}" class="sponsor-logo platinum">
      </a>
    </div>
  {% endfor %}
</div>

### EAIGLE

<div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 2em 0;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/gPRro0XTMXw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Gold Sponsors

<div class="sponsor-grid">
  {% for sponsor in site.data.sponsors.gold %}
    <div class="sponsor-item">
      <a href="{{ sponsor.url }}" target="_blank" rel="noopener noreferrer">
        <img src="{{ sponsor.image_path | relative_url }}" alt="{{ sponsor.alt }}" title="{{ sponsor.title }}" class="sponsor-logo gold">
      </a>
    </div>
  {% endfor %}
</div>

## Silver Sponsors

<div class="sponsor-grid">
  {% for sponsor in site.data.sponsors.silver %}
    <div class="sponsor-item">
      <a href="{{ sponsor.url }}" target="_blank" rel="noopener noreferrer">
        <img src="{{ sponsor.image_path | relative_url }}" alt="{{ sponsor.alt }}" title="{{ sponsor.title }}" class="sponsor-logo silver">
      </a>
    </div>
  {% endfor %}
</div>

</div>

