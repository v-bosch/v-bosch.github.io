---
layout: page
title: Glasser HCP-MMP1 Viewer
description: 
img: assets/img/glasser.png
importance: 1
category: work
#related_publications: einstein1956investigations, einstein1950meaning
---

<!--This tool allows you to explore the HCP-MMP1 Atlas [(Glasser et al., 2016)](https://www.nature.com/articles/nature18933). Simply hover over different regions of the atlas to see the name of each region. 

*This interface is designed for use on larger screens, so please note that it may not not work well on your mobile device.*-->


<style>
  .glasser-embed {
    width: min(1180px, calc(100vw - 32px));
    margin-left: 50%;
    transform: translateX(-50%);
  }

  .glasser-embed iframe {
    display: block;
    width: 100%;
    height: 600px;
    border: 0;
    border-radius: 14px;
    background: #f6f7f9;
  }

  @media (max-width: 900px) {
    .glasser-embed iframe { height: 720px; }
  }
</style>

<div class="glasser-embed">
  <iframe
    src="{{ '/assets/plotly/glasser_gui.html' | relative_url }}"
    title="Glasser HCP-MMP1 Viewer"
    scrolling="no"
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>
