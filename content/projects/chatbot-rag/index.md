---
title: "Chatbot Support Étudiant avec RAG"
summary: "Assistant académique intelligent basé sur RAG pour répondre aux questions des étudiants instantanément"
tags:
  - NLP
  - RAG
  - LLM
  - FAISS
  - Chatbot
date: '2025-06-01'

image:
  caption: ''
  focal_point: ''
  preview_only: true

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/Barrada-yasser/chatbot-rag
url_code: 'https://github.com/Barrada-yasser/chatbot-rag'
---

## 🎯 Problématique

**Projet de Fin d'Études BTS (2025)**  
Les étudiants ont besoin d'accéder rapidement à des informations académiques dispersées dans de nombreux documents PDF. Répondre manuellement à chaque question est chronophage pour les enseignants.

## 💡 Solution

Chatbot intelligent utilisant **RAG (Retrieval-Augmented Generation)** pour fournir des réponses précises et contextuelles basées sur la documentation académique officielle.

## 🔧 Architecture Technique

- **Ingestion de documents :** Transformation de 100+ pages PDF en base vectorielle
- **Embeddings :** Sentence-Transformers (all-MiniLM-L6-v2)
- **Base vectorielle :** FAISS pour recherche sémantique rapide
- **LLM :** Gemini Flash (Google) pour génération de réponses
- **Stockage conversations :** MongoDB pour amélioration continue
- **Interface :** Web chat responsive

## 📊 Performances

- **Temps de réponse : <2 secondes**
- **Précision des réponses : 87%** (évaluée par enseignants)
- **100+ pages de cours** indexées
- **Base vectorielle : 5000+ chunks** de texte
- **Capacité : 50+ utilisateurs simultanés**

## 🛠️ Stack Technique

- **RAG Framework :** LangChain
- **Embeddings :** Sentence-Transformers
- **Vector DB :** FAISS
- **LLM :** Gemini Flash (Google Generative AI)
- **Base de données :** MongoDB (historique conversations)
- **Backend :** Python, FastAPI
- **Frontend :** React, TailwindCSS

## 🎯 Impact Académique

Déployé en environnement de test au sein de l'établissement, le chatbot a réduit de 70% le temps de recherche d'informations pour les étudiants et a libéré du temps précieux pour les enseignants.

## 🎓 Apprentissages

Maîtrise complète de l'architecture RAG, optimisation d'embeddings pour recherche sémantique, gestion de conversations contextuelles, et importance de la qualité du preprocessing de documents pour la performance du système.
