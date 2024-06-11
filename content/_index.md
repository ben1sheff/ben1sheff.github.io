---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
  #         parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: markdown
    content:
      title:  ''
      subtitle: ''
      text: |
        ## Certificates:
        #### <a href="https://www.kaggle.com/learn">Kaggle</a>
        - Intro to Machine Learning 
        - Intermediate Machine Learning
        - Feature Engineering 
        - Data Cleaning
        - Intro to Deep Learning
        - Computer Vision
    design:
      columns: '1'

  - block: resume-skills
    id: skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false

  - block: resume-awards
    id: fellowships
    content:
      title: Fellowships and Awards
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        # featured_only: false
    design:
      view: citation
  - block: markdown
    id: talks
    content:
      title: Talks
      text: |
        Assorted talks as an invited seminar speaker or speaker at a conference:
        - _Neutrinos for TeV Neutralinos_ – Invited HEP/Astro seminar speaker, 	Apr 2023
        - _Neutrinos for TeV Neutralinos_ – American Physical Society 4 Corners Meeting,	Oct 2023
        - _Higgsino Dark Matter Theory and its Experimental Probes_ – Phenomenology 2022 Symposium, May 2022
        - _The Race to Find Split Higgsino Dark Matter_ – The XXVIII International Conference on Supersymmetry and the Unification of Fundamental Interactions (SUSY), virtual, Aug 2021
        - _A Standard Model Explanation for the “ATOMKI Anomaly”_ – joint talk by B. Sheff, Y. G. Kolomensky, A. Aleksejevs, PRISMA+ Colloquium, virtual, June 2021
        - _Higgsino Dark Matter in Electron Electric Dipole Moments_ – Phenomenology 2021 Symposium, virtual, May 2021
        - _Higgsino Dark Matter in Electron Electric Dipole Moments_ – International Workshop on Interconnections between Particle Physics and Cosmology (PPC), virtual, May 2021
        - _A Standard Model Explanation for the “ATOMKI Anomaly”_ – joint talk by B. Sheff, Y. G. Kolomensky, A. Aleksejevs,  LANL T-2 Seminar, virtual, Apr 2021
        - _Higgsino Dark Matter in Electron Electric Dipole Moments_ – Phenomenology in Illinois, Kentucky, Indiana, Michigan, and Ohio (PIKIMO 10), virtual, 	Apr 2021
        - _A Mundane Explanation for the “ATOMKI Anomaly”_ – Fall Meeting of the APS Division of Nuclear Physics, virtual Oct 2020
        - _Electron Electric Dipole Moment and SUSY_ – The Obscure Universe: Neutrinos and Other Dark Matters (TASI), virtual, June 2020
    design:
      columns: 1
    # design:
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  
  
  
  # - block: cta-cardwebsite
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic  like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
