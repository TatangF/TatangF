<div align="center">

# Salut, moi c'est Ferol TATANG FOMEKON 👋

### Ingénieur IA — Spécialiste Systèmes Agentiques (MCP · RAG · Orchestration multi-agents)

*Je conçois et j'exploite en autonomie une plateforme IA agentique en production réelle depuis 2022.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ferol--tatang-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ferol-tatang)
[![Email](https://img.shields.io/badge/Email-Tatang.ferol%40yahoo.fr-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:Tatang.ferol@yahoo.fr)
[![Portfolio](https://img.shields.io/badge/Plateforme-profmathscpge--ai.fr-1F2A44?style=flat-square&logo=vercel&logoColor=white)](https://profmathscpge-ai.fr)

</div>

---

## 🧭 En bref

Je ne fais pas que suivre les tendances IA, je les mets à l'épreuve du réel. Depuis 2022, je conçois, déploie et fais tourner **en production continue** une plateforme agentique — pas un POC, pas un notebook, un système que de vrais utilisateurs utilisent chaque jour.

Ma conviction : l'IA générative ne vaut que si elle est **industrialisée comme n'importe quel système critique** — typage strict, tests robustes, CI/CD, monitoring. L'innovation sans rigueur ne survit pas au premier pic de charge.

- 🤖 **Systèmes agentiques** — architecture multi-agents, orchestration d'outils, function calling
- 🔌 **MCP (Model Context Protocol)** — conception de serveurs MCP custom pour standardiser le routage agent ↔ outils
- 📚 **RAG en production** — pipelines LCEL, chunking sémantique, bases vectorielles, recherche hybride
- ⚙️ **LLMOps & MLOps** — CI/CD, monitoring, gestion de secrets, résilience système
- 🎓 Diplômé **MSc Big Data & IA** (ESTIA, 2023)

---

## 🚀 Projet phare : PROF_MathsCPGE

**Plateforme web & mobile de tutorat mathématique alimentée par l'IA**, destinée aux élèves de Lycée et CPGE — conçue, développée et exploitée en autonomie complète depuis 2022.

- 🧩 **Serveur MCP custom** exposant des outils dédiés au tutorat (`chercher_exercice`, `obtenir_correction`, `obtenir_indice`, `obtenir_progression`) — découple la logique métier de l'API Claude et standardise le routage des appels agents
- ⚡ Architecture **streaming SSE** + approche **probe-first** pour optimiser le Time-To-First-Token
- 🏗️ Industrialisation CI/CD sur Railway avec gestion des secrets et alerting automatisé pour la supervision de la disponibilité
- 📱 Application mobile React Native / Expo (iOS & Android en cours)

**Stack :** `Node.js` `Express` `MongoDB Atlas` `API Anthropic Claude` `MCP` `Railway` `React Native`

🔗 [profmathscpge-ai.fr](https://profmathscpge-ai.fr)

---

## 🔬 Projet open source : EnterpriseRAG-Ollama

**Pipeline RAG production-grade, 100% local** — conçu pour être portable sur tout environnement d'entreprise, sans dépendance à une API cloud tierce.

- Stack 100% locale (Ollama, Chroma) pour répondre à des contraintes de gouvernance des données et de coût zéro-API-externe — transposable en environnement on-premise ou air-gapped
- Typage strict Pydantic sur l'ensemble des contrats de données inter-composants (`RAGQuery` / `RAGResponse` / `SourceDocument`)
- Hiérarchie d'exceptions métier dédiée pour un debugging et un monitoring de niveau production
- Architecture d'agent extensible : le RAG est encapsulé comme un outil typé, permettant d'ajouter de nouveaux outils sans régression sur la logique de routage

**Stack :** `Python` `LangChain` `LCEL` `Ollama` `Chroma` `Pydantic` `pytest`

🔗 [github.com/TatangF/EnterpriseRAG-Ollama](https://github.com/TatangF/EnterpriseRAG-Ollama)

---

## 🛠️ Tech Stack

**Agents IA & Orchestration**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-6E56CF?style=flat-square)
![Claude](https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**RAG & Recherche**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Chroma](https://img.shields.io/badge/Chroma-FF6F00?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Backend & Cloud**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

**Data & MLOps**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Ferol's GitHub stats](https://github-readme-stats.vercel.app/api?username=TatangF&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TatangF&layout=compact&hide_border=true)

</div>

---

## 🌱 En ce moment

- Je fais monter en robustesse mes pipelines RAG et mes architectures multi-agents en conditions réelles de production
- Je documente et open-source les briques réutilisables issues de mon travail sur PROF_MathsCPGE
- Toujours en apprentissage continu : chaque nouveauté du monde agentique est confrontée à la réalité du terrain avant d'être adoptée

## 📫 Me contacter

**[LinkedIn](https://www.linkedin.com/in/ferol-tatang)** · **[Email](mailto:Tatang.ferol@yahoo.fr)** · **[profmathscpge-ai.fr](https://profmathscpge-ai.fr)**

<div align="center">
<sub>Disponible pour des missions freelance en ingénierie IA — systèmes agentiques, RAG, LLMOps</sub>
</div>
