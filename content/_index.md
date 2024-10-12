---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: My Story 📕
      text: |
        I am an undergraduate student pursuing a degree in Mechatronics at Xi'an Jiaotong-Liverpool University. My research interests lie at the intersection of human-computer interaction (HCI) and computer science, with a particular emphasis on spatial computing, interaction paradigms, and computational interaction. 

        My academic journey has afforded me the opportunity to work under the guidance of renowned researchers, including [Prof. Hai-Ning Liang](https://cma.hkust-gz.edu.cn/people/hai-ning-liang/) during my tenure at XJTLU. I am currently engaged in research at the Institute of Software, Chinese Academy of Sciences, under the supervision of [Prof. Jin Huang](https://people.ucas.ac.cn/~huangjin).

        Throughout my academic career, I have had the opportunity to work with respected experts in the field, including Prof. Dominic Kao at Purdue University and Prof. Wenge Xu at Birmingham City University. [These experiences](/experience/) have enhanced my comprehension of human-computer interaction (HCI) and extended reality (XR) technologies.

        In addition to my research interests in HCI, I have a robust foundation in robotics, having participated in the [RoboMaster](https://www.robomaster.com/en-US) robotics competition, hosted by [DJI](https://www.dji.com/). In this capacity, I contributed to the design and development of robots, thereby developing my skills in hardware design and ROS2. My [GitHub profile](https://github.com/W-YXN) provides an overview of my robotics-related projects (in my organization page).

        I will be completing my undergraduate studies in June 2026 and am actively seeking research assistant or doctoral opportunities in the fields of HCI, XR, and interaction technologies. I would be delighted to discuss **any** potential collaborations or opportunities with you.
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
