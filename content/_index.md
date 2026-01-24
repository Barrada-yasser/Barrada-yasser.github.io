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
        interests: Domaines d'expertise
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
        <div style="max-width: 900px; margin: 0 auto;">
          <div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 25px; border-radius: 12px; margin-bottom: 20px; color: white; box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);">
            <h3 style="margin: 0 0 10px 0; color: white; font-size: 22px;">🎓 Licence Concepteur et Développeur d'Applications</h3>
            <p style="margin: 5px 0; font-size: 16px; opacity: 0.95;"><strong>INSTA Paris 5ème</strong> | <em>2025-2026</em></p>
            <p style="margin: 15px 0 0 0; line-height: 1.6;">Formation en alternance (Bac+3) - Spécialisation développement d'applications</p>
          </div>
          
          <div style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); padding: 25px; border-radius: 12px; margin-bottom: 20px; color: white; box-shadow: 0 4px 15px rgba(245, 87, 108, 0.4);">
            <h3 style="margin: 0 0 10px 0; color: white; font-size: 22px;">🤖 BTS Développement de l'Intelligence Artificielle</h3>
            <p style="margin: 5px 0; font-size: 16px; opacity: 0.95;"><strong>BTS Casablanca, Maroc</strong> | <em>2023-2025</em></p>
            <p style="margin: 15px 0 0 0; line-height: 1.6;">Formation intensive en IA et Machine Learning (Bac+2)</p>
          </div>
          
          <div style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); padding: 25px; border-radius: 12px; color: white; box-shadow: 0 4px 15px rgba(79, 172, 254, 0.4);">
            <h3 style="margin: 0 0 10px 0; color: white; font-size: 22px;">📚 Baccalauréat Sciences Physiques</h3>
            <p style="margin: 5px 0; font-size: 16px; opacity: 0.95;"><strong>Maroc</strong> | <em>2023</em></p>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['60px', '0', '30px', '0']
  
  - block: markdown
    id: skills
    content:
      title: '💻 Compétences Techniques'
      text: |-
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 25px; max-width: 1200px; margin: 0 auto;">
          
          <div style="background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); border-left: 5px solid #667eea; transition: transform 0.3s;">
            <h3 style="color: #667eea; margin-top: 0; display: flex; align-items: center; gap: 10px;">
              <span style="font-size: 28px;">🤖</span> IA & Machine Learning
            </h3>
            <div style="line-height: 1.8;">
              <p style="margin: 10px 0;"><strong style="color: #667eea;">Deep Learning:</strong> TensorFlow, PyTorch, YOLOv8</p>
              <p style="margin: 10px 0;"><strong style="color: #667eea;">Computer Vision:</strong> OpenCV, Détection d'objets, Segmentation</p>
              <p style="margin: 10px 0;"><strong style="color: #667eea;">NLP & GenAI:</strong> RAG, FAISS, LLMs, CrewAI</p>
              <p style="margin: 10px 0;"><strong style="color: #667eea;">Multi-Agents:</strong> Claude API, Agents autonomes</p>
            </div>
          </div>
          
          <div style="background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); border-left: 5px solid #f5576c; transition: transform 0.3s;">
            <h3 style="color: #f5576c; margin-top: 0; display: flex; align-items: center; gap: 10px;">
              <span style="font-size: 28px;">💻</span> Développement
            </h3>
            <div style="line-height: 1.8;">
              <p style="margin: 10px 0;"><strong style="color: #f5576c;">Backend:</strong> Python, FastAPI, Flask</p>
              <p style="margin: 10px 0;"><strong style="color: #f5576c;">Frontend:</strong> React.js, JavaScript, HTML/CSS</p>
              <p style="margin: 10px 0;"><strong style="color: #f5576c;">Cloud:</strong> AWS (Lambda, S3, DynamoDB)</p>
              <p style="margin: 10px 0;"><strong style="color: #f5576c;">DevOps:</strong> Git/GitHub, Docker</p>
            </div>
          </div>
          
          <div style="background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); border-left: 5px solid #4facfe; transition: transform 0.3s;">
            <h3 style="color: #4facfe; margin-top: 0; display: flex; align-items: center; gap: 10px;">
              <span style="font-size: 28px;">📊</span> Data Science
            </h3>
            <div style="line-height: 1.8;">
              <p style="margin: 10px 0;"><strong style="color: #4facfe;">Outils:</strong> pandas, numpy, scikit-learn, BigData</p>
              <p style="margin: 10px 0;"><strong style="color: #4facfe;">Databases:</strong> MongoDB, PostgreSQL</p>
              <p style="margin: 10px 0;"><strong style="color: #4facfe;">Visualisation:</strong> Matplotlib, Seaborn</p>
            </div>
          </div>
          
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['30px', '0', '30px', '0']
  
  - block: markdown
    id: experience
    content:
      title: '💼 Expérience Professionnelle'
      text: |-
        <div style="max-width: 950px; margin: 0 auto;">
          <div style="background: white; padding: 35px; border-radius: 15px; box-shadow: 0 8px 25px rgba(0,0,0,0.1); border-left: 6px solid #10b981;">
            <div style="display: flex; justify-content: space-between; align-items: start; flex-wrap: wrap; gap: 15px; margin-bottom: 20px;">
              <div>
                <h3 style="color: #10b981; margin: 0; font-size: 24px;">💼 Stagiaire Développeur IA</h3>
                <p style="color: #6b7280; margin: 8px 0 0 0; font-size: 16px;"><strong>TCI Consulting</strong> | Maroc</p>
              </div>
              <span style="background: #10b981; color: white; padding: 8px 20px; border-radius: 25px; font-size: 14px; font-weight: 600; white-space: nowrap;">Avril - Mai 2025</span>
            </div>
            
            <p style="margin: 20px 0; line-height: 1.7; font-size: 16px; color: #374151;">Développement d'un système IA de détection des comportements à risque en milieu urbain avec analyse vidéo en temps réel</p>
            
            <div style="background: #f9fafb; padding: 20px; border-radius: 10px; margin: 20px 0;">
              <h4 style="margin: 0 0 15px 0; color: #10b981;">🎯 Réalisations clés :</h4>
              <ul style="margin: 0; padding-left: 20px; line-height: 2;">
                <li>Détection multi-objets temps réel avec <strong>YOLOv8</strong></li>
                <li>Segmentation sémantique avancée des scènes urbaines</li>
                <li>Interface web de visualisation avec système d'alertes</li>
              </ul>
            </div>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 15px; margin-top: 25px;">
              <div style="background: #ecfdf5; padding: 20px; border-radius: 10px; text-align: center;">
                <p style="margin: 0; color: #10b981; font-weight: bold; font-size: 24px;">⚡ 30+ FPS</p>
                <p style="margin: 8px 0 0 0; font-size: 13px; color: #6b7280;">Détection temps réel</p>
              </div>
              <div style="background: #ecfdf5; padding: 20px; border-radius: 10px; text-align: center;">
                <p style="margin: 0; color: #10b981; font-weight: bold; font-size: 24px;">🎯 89%</p>
                <p style="margin: 8px 0 0 0; font-size: 13px; color: #6b7280;">Précision détection</p>
              </div>
              <div style="background: #ecfdf5; padding: 20px; border-radius: 10px; text-align: center;">
                <p style="margin: 0; color: #10b981; font-weight: bold; font-size: 24px;">🤖 YOLOv8</p>
                <p style="margin: 8px 0 0 0; font-size: 13px; color: #6b7280;">Technologie IA</p>
              </div>
            </div>
            
            <div style="margin-top: 25px; padding-top: 20px; border-top: 2px solid #e5e7eb;">
              <p style="margin: 0; font-size: 14px; color: #6b7280;">
                <strong style="color: #374151;">Technologies:</strong> YOLOv8, Python, OpenCV, TensorFlow, FastAPI
              </p>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['30px', '0', '30px', '0']
  
  - block: markdown
    id: contact
    content:
      title: '📧 Contact'
      text: |-
        <div style="max-width: 800px; margin: 0 auto;">
          <div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 40px; border-radius: 15px; color: white; text-align: center; box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);">
            <h3 style="color: white; margin: 0 0 30px 0; font-size: 28px;">✉️ Restons en contact !</h3>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin: 30px 0;">
              <div style="background: rgba(255,255,255,0.15); padding: 20px; border-radius: 10px; backdrop-filter: blur(10px);">
                <p style="margin: 0; font-size: 14px; opacity: 0.9;">📧 Email</p>
                <p style="margin: 8px 0 0 0; font-weight: 600;">barradayasser2004@gmail.com</p>
              </div>
              <div style="background: rgba(255,255,255,0.15); padding: 20px; border-radius: 10px; backdrop-filter: blur(10px);">
                <p style="margin: 0; font-size: 14px; opacity: 0.9;">📱 Téléphone</p>
                <p style="margin: 8px 0 0 0; font-weight: 600;">+33 7 43 63 40 47</p>
              </div>
              <div style="background: rgba(255,255,255,0.15); padding: 20px; border-radius: 10px; backdrop-filter: blur(10px);">
                <p style="margin: 0; font-size: 14px; opacity: 0.9;">📍 Localisation</p>
                <p style="margin: 8px 0 0 0; font-weight: 600;">Cergy, Île-de-France</p>
              </div>
            </div>
            
            <div style="margin-top: 35px; padding-top: 30px; border-top: 1px solid rgba(255,255,255,0.3);">
              <p style="margin: 0 0 15px 0; font-size: 16px;">Retrouvez-moi aussi sur :</p>
              <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
                <a href="https://linkedin.com/in/yasser-barrada" style="color: white; text-decoration: none; background: rgba(255,255,255,0.2); padding: 10px 25px; border-radius: 25px; font-weight: 600; transition: all 0.3s;">
                  💼 LinkedIn
                </a>
                <a href="https://github.com/Barrada-yasser" style="color: white; text-decoration: none; background: rgba(255,255,255,0.2); padding: 10px 25px; border-radius: 25px; font-weight: 600; transition: all 0.3s;">
                  💻 GitHub
                </a>
              </div>
            </div>
            
            <div style="margin-top: 35px; padding: 25px; background: rgba(255,255,255,0.1); border-radius: 10px; backdrop-filter: blur(10px);">
              <p style="margin: 0; font-size: 18px; font-weight: 600;">💼 Disponibilité</p>
              <p style="margin: 10px 0 0 0; font-size: 16px;">Stage développeur IA/ML à partir de février 2025</p>
              <p style="margin: 5px 0 0 0; font-size: 14px; opacity: 0.9;">📍 Mobilité : Île-de-France et remote</p>
            </div>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['30px', '0', '60px', '0']
---
