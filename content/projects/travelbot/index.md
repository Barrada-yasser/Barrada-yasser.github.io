---
title: "TravelBot IA - Assistant Voyage Multi-Agents"
summary: "Assistant voyage intelligent basé sur une architecture multi-agents, réduisant le temps de recherche de 95%"
tags:
  - GenAI
  - Multi-Agents
  - CrewAI
  - Claude API
  - NLP
date: '2024-12-01'

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Links
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/Barrada-yasser/travelbot
url_code: 'https://github.com/Barrada-yasser/travelbot'
---

## 🎯 Problématique

La planification de voyages nécessite généralement plusieurs heures de recherche manuelle sur différentes plateformes, avec une comparaison fastidieuse des options disponibles.

## 💡 Solution

Architecture multi-agents innovante utilisant **CrewAI** avec 5 agents spécialisés qui collaborent pour automatiser entièrement le processus de recherche et de planification de voyages.

## 🔧 Fonctionnalités

- **Recherche de vols en temps réel** via API Amadeus (400+ compagnies)
- **Architecture multi-agents coordonnée** avec 5 agents spécialisés :
  - Agent recherche de vols
  - Agent comparaison de prix
  - Agent optimisation d'itinéraires
  - Agent recommandations personnalisées
  - Agent coordination et synthèse
- **Interface conversationnelle naturelle** via WhatsApp (Twilio)
- **Traitement du langage naturel** avec Claude Sonnet 4

## 📊 Résultats

- ⏱️ **Temps de recherche réduit de 3h à 2 minutes (-95%)**
- ✈️ Accès à **400+ compagnies aériennes**
- 🤖 **5 agents IA** travaillant en collaboration
- 💬 Interface **WhatsApp** intuitive

## 🛠️ Stack Technique

- **Framework Multi-Agents :** CrewAI
- **LLM :** Claude Sonnet 4 (Anthropic API)
- **Backend :** Flask, Python
- **APIs :** Amadeus (vols), Twilio (WhatsApp)
- **Déploiement :** AWS Lambda

## 🎓 Apprentissages

Ce projet m'a permis de maîtriser l'orchestration d'agents autonomes, la gestion d'APIs externes complexes, et la création d'interfaces conversationnelles naturelles. La coordination entre agents a été un défi passionnant qui a considérablement amélioré mes compétences en architecture logicielle.
