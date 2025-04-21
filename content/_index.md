---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-04-20
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
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/jdnm_cv.pdf
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
          parallax: false

  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: working_papers
    content:
      title: Work in progress
      text: ""
      filters:
        folders:
          - working_papers
        exclude_featured: false
    design:
      view: citation

  - block: markdown
    id: teaching
    content:
      title: 'Teaching'
      subtitle: 'See my CV for the list of all classes I taught'
      text: |-
          - [Econometric Software: introduction to Stata (Univ. of Bordeaux - Mageval 1)](https://github.com/jdnmiguel/stata_class)
          - Microeconomics (Univ. of Bordeaux - Undergraduate level)
          - Causal Inference I (Univ. of Bordeaux - Master Development Economics)
          - [Introduction to Machine Learning for economists (Univ. of Bordeaux - Master 2 Public Policy Evaluation)](https://github.com/jdnmiguel/Applied-ML)
          - Economic issue in Africa (Graduate level - Univ. Montaigne Bordeaux)
    design:
      columns: '1'
---

