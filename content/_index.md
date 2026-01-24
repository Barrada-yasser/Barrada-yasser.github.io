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
  
  - block: markdown
    id: education
    content:
      title: '🎓 Formation'
      text: |-
        ### Licence Concepteur et Développeur d'Applications
        **INSTA Paris 5ème** | *2025-2026*  
        Formation en alternance (Bac+3) - Spécialisation développement d'applications

        ### BTS Développement de l'Intelligence Artificielle  
        **BTS Casablanca, Maroc** | *2023-2025*  
        Formation intensive en IA et Machine Learning (Bac+2)

        ### Baccalauréat Sciences Physiques
        **Maroc** | *2023*
    design:
      columns: '1'
      spacing:
        padding: ['60px', '0', '30px', '0']
  
  - block: markdown
    id: skills
    content:
      title: '💻 Compétences Techniques'
      text: |-
        ### IA & Machine Learning
        - **Deep Learning:** TensorFlow, PyTorch, YOLOv8
        - **Computer Vision:** OpenCV, Détection d'objets, Segmentation
        - **NLP & GenAI:** RAG, FAISS, Sentence-Transformers, LLMs
        - **Multi-Agents:** CrewAI, Claude API, Agents autonomes

        ### Développement
        - **Backend:** Python, FastAPI, Flask
        - **Frontend:** React.js, JavaScript, HTML/CSS
        - **Cloud:** AWS (Lambda, S3, DynamoDB)
        - **Databases:** MongoDB, PostgreSQL

        ### Data Science
        - **Outils:** pandas, numpy, scikit-learn, BigData
        - **Visualisation:** Matplotlib, Seaborn
    design:
      columns: '2'
      spacing:
        padding: ['30px', '0', '30px', '0']
  
  - block: markdown
    id: experience
    content:
      title: '💼 Expérience Professionnelle'
      text: |-
        ### Stagiaire Développeur IA
        **TCI Consulting, Maroc** | *Avril - Mai 2025*

        Développement d'un système IA de détection des comportements à risque en milieu urbain

        **Réalisations :**
        - Détection multi-objets temps réel avec **YOLOv8**
        - Segmentation sémantique avancée des scènes urbaines
        - Interface web de visualisation avec alertes
        - **Technologies:** YOLOv8, Python, OpenCV, TensorFlow, FastAPI

        **Résultats :**  
        ✅ FPS : 30+ sur vidéo HD  
        ✅ Précision de détection : 89%  
        ✅ Système déployé en environnement de test
    design:
      columns: '1'
      spacing:
        padding: ['30px', '0', '30px', '0']
  
  - block: markdown
    id: contact
    content:
      title: '📧 Contact'
      text: |-
        ### Restons en contact !

        **Email :** barradayasser2004@gmail.com  
        **Téléphone :** +33 7 43 63 40 47  
        **Localisation :** Cergy, Île-de-France

        **Réseaux :**  
        [LinkedIn - yasser-barrada](https://linkedin.com/in/yasser-barrada) | [GitHub - Barrada-yasser](https://github.com/Barrada-yasser)

        ---

        💼 **Disponibilité :** Stage développeur IA/ML à partir de février 2025  
        📍 **Mobilité :** Île-de-France et remote
    design:
      columns: '1'
      spacing:
        padding: ['30px', '0', '60px', '0']
---
