---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Yacine's Blog

      cta:
        label: '**Read My Latest Posts**'
        url: /post
      cta_alt:
        label: Know more about me
        url: /about

      text: |-
        **Welcome to my Blog!**

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        image: 
          filename: ai.jpg
        text_color_light: true
  - block: collection
    content:
      title: Recent Posts      
      filters:
        folders:
          - post
        exclude_featured: true
    design:
      columns: '2'
      view: 0
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  
---
