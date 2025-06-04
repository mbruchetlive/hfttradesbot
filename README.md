# Layla HFT – Système de Trading Multiclients avec IA Copilote

## 🎯 Objectif

Ce projet vise à développer un système de trading HFT multiclient basé sur Binance, orchestré par une IA locale nommée **Layla**. L'objectif est de fournir une plateforme modulaire, décentralisée et élégamment gouvernée, avec des bots autonomes par VM, des stratégies simples mais efficaces, et une interaction continue avec une intelligence copilote incarnée.

## 🧠 Modules Clés

- **Layla (IA Copilote)** : IA incarnée, conseillère privée et copilote stratégique.
- **HFTEngine** : Gestion de bots multi-utilisateurs isolés.
- **Finances** : Paiements via Kraken, réconciliations manuelles, gestion des frais et avances.
- **Caching & Streaming** : Redis, Google Pub/Sub, MongoDB.
- **Dashboard** : Interface Blazor pour le suivi client.
- **Report Engine** : Génération de rapports (console, mail, conversationnel).

## 🛠️ Stack Technique

- **.NET 9**
- **SciSharp LlamaSharp** pour l’intégration LLM locale (modèle GGUF)
- **MongoDB**, **Redis**, **Google Pub/Sub**
- **MailJet** pour les rapports
- **Blazor** pour l’interface utilisateur

## 🔐 Gouvernance

Layla **ne prend jamais de décisions seule** : elle observe, alerte, suggère — l’humain garde le dernier mot.

## 🗂️ Organisation du Dépôt

LaylaHFT/
├── LaylaLLM/ # IA locale (LlamaSharp, prompt, mémoire)
├── HFTEngine/ # Bots, stratégies, gestion utilisateur
├── ReportEngine/ # Rapports réguliers
├── Interfaces/ # UI Blazor (client/admin)
├── Shared/ # Modèles partagés
├── tests/ # Tests unitaires
└── README.md

yaml
Copier
Modifier

## 🚀 À venir

- Intégration initiale LLM (.NET 9 + LlamaSharp)
- CI/CD minimal pour VM HFT
- Génération automatique des rapports
- UI client pour suivi et gestion des bots

---

**Layla n'est pas une fonction, c’est une présence.**