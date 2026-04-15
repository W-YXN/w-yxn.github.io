---
# Leave the homepage title empty to use the site title
title: ""
date: 2026-04-15
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
          I am an undergraduate researcher in human-computer interaction (HCI) and extended reality (XR), currently pursuing a BEng in Mechatronics and Robotic Systems at Xi’an Jiaotong-Liverpool University, with expected graduation in July 2026.
          
            
          My research lies at the intersection of HCI, XR, and 3D user interfaces, with a particular focus on text entry, computational approaches, and multimodal interaction techniques for spatial computing. I am especially interested in designing robust and expressive interaction methods for immersive environments under real-world constraints.
          
            
          Currently, I am a <strong>Visiting Researcher</strong> at the ICD Lab, Tohoku University, leading a project on gaze-assisted text entry in VR. In parallel, I work as a <strong>Research Assistant</strong> with the FIT-AWE Lab at HKUST (Guangzhou), and as a <strong>Research Scientist Intern</strong> at the Institute of Software, Chinese Academy of Sciences.
          
            
          I have co-authored research published in top-tier venues including <strong>CHI, IEEE TVCG, ISMAR, SUI, and PACM CGIT</strong>.
          
            
          Before focusing on HCI, I developed a strong foundation in robotics and embedded systems through RoboMaster and ROS2-based multi-robot development. This engineering background continues to shape my research perspective, bridging the gap between hardware sensing, computational modeling, and human-centered design.
          
            
          I am actively seeking future Ph.D. and research opportunities in HCI, XR, and interactive computing. Please feel free to reach out via email at contact#xinan-yan.com (replace '#' with '@').
          

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
    id: papers
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
