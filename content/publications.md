---
title: 'Publications'
date: 2023-10-24
type: landing

design:
  spacing: '4rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: collection
    content:
      title: Journal Papers 
      text: ""
      filters:
        folders:
          - publication/journal-papers
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Conference Papers　
      text: ""
      filters:
        folders:
          - publication/conference-papers
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Book
      text: ""
      filters:
        folders:
          - publication/book
        exclude_featured: false
    design:
      view: citation
  - block: resume-awards
    content:
      title: Awards
      username: admin
---