<div align="Right">

# Ferol TATANG ♞

### AI Engineer · Architecte Systèmes Agentiques & LLMOps

**IA générative fiable en production** · **Agents IA & MCP (Model Context Protocol)** · **Software Engineering rigoureux**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ferol-tatang)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Tatang.ferol@yahoo.fr)
[![PROF_MathsCPGE AI](https://img.shields.io/badge/PROF__MathsCPGE_AI-2D2560?style=for-the-badge&logo=google-chrome&logoColor=white)](https://profmathscpge-ai.fr)

</div>

---

## 🎯 En bref

Je conçois des architectures d'**IA générative prêtes pour la production** : résilientes, sécurisées et observables. Mon travail porte sur l'orchestration d'agents, le protocole MCP et le LLMOps.

| | |
|---|---|
| **Rôles visés** | AI Engineer · Architecte Data & IA · LLMOps / GenAI |
| **Cœur d'expertise** | Systèmes agentiques multi-LLM · MCP · RAG · LLMOps |
| **Socle technique** | Python · Node.js / TypeScript · APIs · Cloud · Bases vectorielles |

> *Passer du PoC à la production dépend moins de la puissance du modèle que de la rigueur de l'architecture : gouvernance des données, gestion du contexte, résilience du routage et observabilité.*

---

## 🚀 Projets majeurs

### ∑ PROF_MathsCPGE AI — Tutorat intelligent et agentique
[profmathscpge-ai.fr](https://profmathscpge-ai.fr) · SaaS en production · petite équipe (centré sur la partie IA) · code non open source

Plateforme de tutorat en mathématiques, du collège aux classes préparatoires.

- **Architecture agentique via MCP** : 4 outils métiers (`chercher_exercice`, `obtenir_progression`, `obtenir_correction`, `obtenir_indice`).
- **Résilience multi-LLM** : cascade Anthropic Claude → Groq (Llama 3.3 70B) → Google Gemini, avec bascule automatique sur erreur de quota ou de crédit.
- **Optimisation LLMOps** : streaming SSE, Anthropic Prompt Caching, optimisation du TTFT (*Time to First Token*).
- **Sécurité** : prompt système côté serveur, authentification JWT, rate limiting, parcours conforme RGPD.
- **Observabilité** : suivi du fournisseur actif, estimation de la consommation de tokens, logs d'erreurs structurés.

`Node.js` `Express` `MongoDB Atlas` `React Native / Expo` `Stripe` `SSE` `Anthropic API` `MCP`

### 🔎 [EnterpriseRAG-Ollama](https://github.com/TatangF/EnterpriseRAG-Ollama) — Pipeline RAG local et open source

Conçu dans le cadre de l'expérience PROF_MathsCPGE AI.

- **Pipeline RAG** : LangChain, embeddings HuggingFace (`all-MiniLM-L6-v2`), stockage vectoriel ChromaDB, LLM local via Ollama (`llama3.2:3b`).
- **Retrieval** : stratégie MMR (*Maximal Marginal Relevance*) pour diversifier les contextes récupérés, prompt en français.
- **Qualité** : **18 tests automatisés `pytest`** (ingestion, chunking, embedding, retrieval…).

`Python` `LangChain` `ChromaDB` `Ollama` `Pytest`

---

## 🧠 Expertise

### 🤖 IA générative, agents & MCP
* **Orchestration agentique** : architectures multi-agents (LangGraph, CrewAI, AutoGen), agents orientés objectifs, orchestration de LLM.
* **MCP** : conception d'outils métiers exposés à un LLM via Model Context Protocol.
* **RAG** : bases vectorielles, recherche sémantique, récupération MMR.
* **LLMOps & sécurité** : prompt caching, fallback multi-fournisseurs, métriques d'usage, rate limiting, sécurisation en production.

### 🏗️ Architecture logicielle & industrialisation
* **Patterns** : Clean Architecture, DDD, SOLID, architectures événementielles.
* **APIs & streaming** : APIs REST fortement typées, streaming temps réel via SSE.
* **Fiabilité** : tests automatisés, CI/CD, observabilité.

### 📊 Data engineering & cloud
* Architectures Big Data, pipelines de données fiables, traitement temps réel.
* Infrastructure cloud-native, automatisation des déploiements, qualité des données.

---

## 🛠️ Stack technique

| Domaine | Technologies |
|---|---|
| **IA & LLMOps** | `LLM` `MCP` `LangChain` `LangGraph` `CrewAI` `AutoGen` `RAG` `Embeddings` `ChromaDB` `Prompt Caching` |
| **Software Engineering** | `Python` `TypeScript` `Node.js` `Express` `FastAPI` `REST APIs` `SSE` |
| **Data & Cloud** | `MongoDB Atlas` `Docker` `Railway` `CI/CD` `Git` · *Kubernetes (en apprentissage)* |

---

## 🎓 Certifications & formation

| | |
|---|---|
| **IBM RAG and Agentic AI** *(Professional Certificate, 2026)* | LangChain et LangGraph · LangGraph, CrewAI, AutoGen et BeeAI · Build AI Agents using MCP |
| **AI Fluency** *(Anthropic, 2026)* | |
| **Google Data Analytics** *(Professional Certificate, 2025)* | |
| **Docker and Kubernetes Masterclass** | *en cours* |
| **Master 2 Big Data & IA** *(ESTIA, 2023)* | |
| **Master Big Data & Statistiques** *(ESSFAR, Yaoundé, 2022)* | |
| **Licence Mathématiques** *(Université de Yaoundé 1, 2019)* | |

---

## 🧪 R&D & compétitions

- **Université Gustave Eiffel (laboratoire GéoLoc, campus de Nantes)** : séries temporelles multisources (LSTM, CNN 1D).
- **Challenge IA Pau** : **Top 3** — modèle prédictif, OCR (Tesseract).
- **Challenge Biarritz Agglomération** : **Top 4** — Random Forest, application FastAPI & Streamlit.

---

## 🎯 Philosophie technique

1. **Anti-hype** : utiliser un LLM uniquement là où il apporte une valeur réelle.
2. **Prêt pour la prod** : un agent sans fallback, sans garde-fou et sans suivi de consommation n'est qu'un démonstrateur, pas un produit.
3. **Architecture first** : l'IA est un sous-système logiciel, soumis aux mêmes exigences de qualité, de typage et de testabilité que le reste du SI.

---

## 🤝 Collaborons

Ouvert aux opportunités d'**AI Engineer**, d'**Architecte IA / LLMOps**, et aux missions de **conseil et d'expertise MCP & systèmes agentiques**.

📧 [Tatang.ferol@yahoo.fr](mailto:Tatang.ferol@yahoo.fr) · 💼 [LinkedIn](https://linkedin.com/in/ferol-tatang)
