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
      text: |
        Étudiant en développement IA/ML de 21 ans à INSTA Paris, passionné par l'innovation technologique et les défis techniques. Spécialisé en systèmes multi-agents, deep learning et computer vision, je transforme des concepts complexes en solutions concrètes.
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
      title: '💼 Mes Projets'
      subtitle: ''
      text: |-
        Découvrez une sélection de mes réalisations en intelligence artificielle et machine learning.
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
    sections:
  - block: resume-biography-3
    content:
      username: me
      ...
  - block: markdown
    content:
      title: '💼 Mes Projets'
      ...
  - block: collection
    id: projects
    ...
  - block: resume-education
    id: education
    content:
      title: 🎓 Formation
      username: me
    design:
      spacing:
        padding: ['60px', '0', '60px', '0']
---
