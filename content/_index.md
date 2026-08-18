---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |
        I am a master student at Graduate School of Economics, University of Osaka.

        [CV を見る →](https://www.dropbox.com/xxxxxxx/resume.pdf)
      headings:
        about: ''
        education: ''
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: working-papers
    content:
      title: Working Papers
      filters:
        folders:
          - publications
        publication_type: 'article'
      count: 0
      order: desc
    design:
      view: plain-title
---