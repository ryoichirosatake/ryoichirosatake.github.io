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
        (ここに一言自己紹介が入ります)

        [CV を見る →](https://www.dropbox.com/xxxxxxx/resume.pdf)
      headings:
        about: ''
        education: ''
        interests: ''
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
      view: citation

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publications
        publication_type: 'article-journal'
      count: 0
      order: desc
    design:
      view: citation
---