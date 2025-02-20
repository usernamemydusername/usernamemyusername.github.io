---
title: 'Publications'
cms_exclude: true
types: landing


# View.
view: citation

sections:
  - block: collection
    id: publication
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      columns: 1 
  - block: collection
    id: submitted-papers
    content:
      title: Submitted Papers
      filters:
        folders:
          - submitted-papers
        exclude_featured: false
    design:
      view: citation 
      columns: 1 

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
