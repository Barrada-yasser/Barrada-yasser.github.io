---
title: ''
summary: ''
date: 2022-10-24
type: landing
design:
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
        about: À propos
        education: Formation
        interests: Compétences
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
      title: '💼 Mes Projets'
      text: ''
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: ''
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2
---
