---
title: Publications
cms_exclude: true

# View.
view: citation
sections:
  - block: collection
    content:
      title: "Published Papers"
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation 
  - block: collection
    content:
      title: "Submitted Papers"
      text: ""
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