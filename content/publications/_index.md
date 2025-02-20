---
title: Publications
cms_exclude: true

# View.
view: citation

sections:
  - block: markdown
    content:
      title: "Published Papers"
      text: ""
  - block: collection
    content:
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation 

  - block: markdown
    content:
      title: "Submitted Papers"
      text: ""
  - block: collection
    content:
      filters:
        folders:
          - submitted-papers
        exclude_featured: false
    design:
      view: citation 

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
