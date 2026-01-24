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
      text: |
        Étudiant en développement IA/ML de 21 ans, actuellement en formation Concepteur et Développeur d'Applications à INSTA Paris. Spécialisé en systèmes multi-agents, deep learning et computer vision, j'ai développé plusieurs projets impactants incluant TravelBot (réduction de 95% du temps de recherche) et un système de détection de pneumonie avec 88,62% de précision.
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
      title: '📚 Mes Projets'
      subtitle: ''
      text: |-
        Passionné par l'IA et le machine learning, je développe des solutions innovantes qui résolvent des problèmes concrets. De la détection de maladies par deep learning aux assistants intelligents multi-agents, mes projets démontrent ma capacité à transformer des concepts complexes en applications fonctionnelles.

        Découvrez ci-dessous une sélection de mes réalisations techniques.
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Projets Récents
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2
  - block: collection
    id: news
    content:
      title: Actualités
      subtitle: ''
      text: ''
      page_type: blog
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
