---
title: Research
type: landing

sections:
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

  - block: collection
    id: talks
    content:
      title: Upcoming Talks
      filters:
        folders:
          - events
        exclude_past: true
      count: 0
      order: asc
    design:
      view: card
---