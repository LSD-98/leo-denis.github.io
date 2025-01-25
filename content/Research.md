---
title: 'Research'
date: 2025-01-22
type: landing

design:
  # Section spacing
  spacing: '4rem'

# Page sections
sections:
  - block: collection
    id: working_papers
    content:
      title: Working Papers
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 1
  - block: collection
    content:
      title: Other publications
      filters:
        folders:
          - publication
    design:
      view: citation
---