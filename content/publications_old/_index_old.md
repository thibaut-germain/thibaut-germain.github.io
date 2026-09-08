---
title: Publications
summary: My publications
type: landing
#cms_exclude: true

# View.
#view: citation

sections:
  - block: collection
    id: papers
    content:
      title: Featured Publications
      hide_if_empty: true
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 1
      show_read_more: true
  - block: collection
    content:
      title: Publications
      text: ''
      count: 0
      show_more: false
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
      group_by_year: true
      citation_symbol: "▸"

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
