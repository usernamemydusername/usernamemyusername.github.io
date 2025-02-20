---
title: ''
cms_exclude: true
types: landing


# View.
view: citation

sections:
  - block: markdown
    content:
      title: "Published Papers"
      text: ""
  - block: collection
    content:
      title: "Publications"
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
      title: "Submitted Papers"
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
