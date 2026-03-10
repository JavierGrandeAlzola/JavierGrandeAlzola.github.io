---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
        
  - block: markdown
    content:
      title: '👋 About Me'
      subtitle: ''
      text: |-
        I am Javier, an Electronics and Robotics Engineer passionate about hardware design, industrial automation, and microcontroller programming. 
        
        Welcome to my professional portfolio. Here you will find my latest projects, technical developments, and my professional journey.
    design:
      columns: '1'
---