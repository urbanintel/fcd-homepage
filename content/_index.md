---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: fcdance-intro.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: collection
    content:
      title: Portfolio
      text: ""
      count: 5
      filters:
        folders:
          - portfolio
        publication_type: 'article-grid'
    design:
      view: card
      columns: '1'
    
#  - block: collection
#    content:
#      title: Latest News
#      subtitle:
#      text:
#      count: 5
#      filters:
#        author: ''
#        category: ''
#        exclude_featured: false
#        publication_type: ''
#        tag: ''
#      offset: 0
#      order: desc
#      page_type: post
#    design:
#      view: card
#      columns: '1'
  

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="찾아오는곳 →" %}}
    design:
      columns: '1'
---
