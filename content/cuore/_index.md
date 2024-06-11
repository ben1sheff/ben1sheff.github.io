---
title: 'cuore'
date: 2023-10-24
type: landing
url: cuore/

design:
  # Section spacing
  spacing: '5rem'

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

# Page sections
sections:
  - block: collection
    id: cuore
    content:
      title: CUORE Projects
      text: From 2014 to 2017, I worked with the  (CUORE) collaboration at Berkeley, designing testing jigs for light detectors and for transition edge sensor (TES) development, created for use in a cryostat at temperatures as low as 10 mK.
      filters:
        folders:
          - cuore
    design:
      view: article-grid
      fill_image: false
      columns: 3
---