---
# Page title
title: 联系我们
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: 联系我们
      text: |
        ## 实验室地址
        北京市海淀区中关村大街59号中国人民大学信息楼500        
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
          style: |
            .fullscreen {
              position: relative;
              width: 100%;
              height: 0;
              padding-top: 56.25%; /* 16:9 Aspect Ratio */
              background-size: cover;
              background-repeat: no-repeat;
              background-position: center;
            }
      spacing:
        padding: ['20px', '0', '20px', '0']
---


