# 👨‍🔬 Dominique S. Loyer

[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--9713--7109-green.svg)](https://orcid.org/0009-0003-9713-7109)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-blue)](https://scholar.google.com/citations?user=JmRd6U0AAAAJ)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Profile-00CCBB)](https://www.researchgate.net/profile/Dominique-Loyer)
[![Website](https://img.shields.io/badge/Website-dominiqueloyer.github.io-orange)](https://dominiqueloyer.github.io)

---

PhD Candidate in Cognitive Informatics at [Université du Québec à Montréal (UQAM)](https://dic.uqam.ca)

**Research Interests:**
- 🤖 Algorithmic Bureaucracy & Governance
- 🔍 Explainable AI (xAI) & Transparency
- 📊 Recommendation Systems & Collaborative Filtering
- 🌐 Digital Sociology & Information Credibility
- ⚖️ AI Ethics & Accountability

---
### 💖 Support My GITHUB Open Projects

[![GitHub Sponsors](https://img.shields.io/badge/GitHub%20Sponsors-Support-EA4AAA)](https://github.com/sponsors/DominiqueLoyer)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donate-FFDD00)](https://www.buymeacoffee.com/dominiqueloyer)

---
# SysCRED — Système Neuro-Symbolique de Vérification de Crédibilité

[![PyPI version](https://badge.fury.io/py/syscred.svg)](https://badge.fury.io/py/syscred)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18436691.svg)](https://doi.org/10.5281/zenodo.18436691)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DominiqueLoyer/systemFactChecking/blob/main/02_Code/v2_syscred/syscred_colab.ipynb)
[![OWL](https://img.shields.io/badge/OWL-2.0-orange.svg)](https://www.w3.org/OWL/)
[![RDF](https://img.shields.io/badge/RDF-Turtle-blue.svg)](https://www.w3.org/TR/turtle/)

**PhD Thesis Prototype** — Dominique S. Loyer (UQAM)  
*Citation Key: loyerModelingHybridSystem2025*

> [!NOTE]

> **Version stable : v2.4.1 (12 mars 2026) — (dashboard explainers, TREC metrics, GraphRAG)**
>
> - **Fact-Checking** multi-sources (Google Fact Check API)
> - **E-E-A-T** (Experience, Expertise, Authority, Trust)
> - **NER** — Extraction d'entités nommées (spaCy)
> - **GraphRAG** — Réseau Neuro-Symbolique (D3.js)
> - **Métriques** — Precision, Recall, nDCG, MRR
> - **Bias Analysis** — Détection de biais

**Site institutionnel: https://syscred.uqam.ca**

### 🔍 systemFactChecking – Hybrid Information Credibility Verification System
A hybrid fact-checking system combining predicate-logic rules, ontologies (OWL), and neuro-symbolic AI to evaluate the credibility of information sources.

SysCRED est un système hybride de fact-checking combinant :
- **Symbolic AI** : Raisonnement par règles et ontologies (OWL/RDF)
- **Neural AI** : Transformers pour NER, sentiment, cohérence
- **IR Engine** : Recherche d’évidence (BM25, TF-IDF, TREC)
- **GraphRAG** : Mémoire contextuelle par graphe de connaissances
- **E-E-A-T** : Scoring qualité Google (Experience, Expertise, Authority, Trust)
- **Technologies:** Python, NLP, OWL Ontologies, Machine Learning, Neuro-symbolic AI
- **Status:** Active Research (Doctoral Project)

  
- 📂 [Repository](https://github.com/DominiqueLoyer/systemFactChecking)
- 📄 [Modeling Paper](https://doi.org/10.13140/rg.2.2.36348.24961) [![ISBN](https://img.shields.io/badge/ISBN-978--1--0699945--0--9-green)](https://isbnsearch.org/isbn/9781069994509)
- 📄 [Ontology Paper](https://doi.org/10.13140/RG.2.2.22926.47680) [![ISBN](https://img.shields.io/badge/ISBN-978--1--0699945--1--6-green)](https://isbnsearch.org/isbn/9781069994516)
- 📄 [Beamer Presentation - (PDF)](01_Presentations/syscred_presentation.pdf)


[![PyPI version](https://badge.fury.io/py/syscred.svg)](https://badge.fury.io/py/syscred)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18436691.svg)](https://doi.org/10.5281/zenodo.18436691)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DominiqueLoyer/systemFactChecking/blob/main/02_Code/v2_syscred/syscred_colab.ipynb)
[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/DominiqueLoyer/systemFactChecking/blob/main/02_Code/v2_syscred/syscred_kaggle.ipynb)
[![OWL](https://img.shields.io/badge/OWL-2.0-orange.svg)](https://www.w3.org/OWL/)
[![RDF](https://img.shields.io/badge/RDF-Turtle-blue.svg)](https://www.w3.org/TR/turtle/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# restructuration de sysCRED
```bash
systemFactChecking_Sandbox/
├── syscred/                    # ← Package Python unique et propre
│   ├── __init__.py
│   ├── backend_app.py          # API Flask
│   ├── verification_system.py  # Système principal
│   ├── config.py
│   ├── ner_analyzer.py         # ← À restaurer
│   ├── eeat_calculator.py      # ← À restaurer
│   ├── graph_rag.py
│   ├── ontology_manager.py
│   ├── api_clients.py
│   ├── seo_analyzer.py
│   ├── ir_engine.py
│   ├── eval_metrics.py
│   ├── trec_retriever.py
│   ├── trec_dataset.py
│   ├── liar_dataset.py
│   ├── database.py
│   └── static/
│       └── index.html
├── huggingface_space/
│   ├── Dockerfile              # ← Mis à jour
│   └── README.md
├── requirements.txt            # ← Allégé pour Render
├── requirements-full.txt       # ← Version complète pour HF/local
├── Dockerfile                  # Pour Render
├── .env
├── README.md
├── 03_Docs/
├── 99_Archive/                 # ← Anciennes versions archivées
└── ...
```
___
## 📚 Featured Publications

### 🏆 PhD (Examen de synthèse doctoral)
**Le Léviathan Algorithmique : pouvoir, opacité et responsabilité à l'ère de l'intelligence artificielle**  
[![ISBN](https://img.shields.io/badge/ISBN-978--1--0699904--0--2-green)](https://isbnsearch.org/isbn/978-1-0699904-0-2)
[![DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.28011.20002-blue)](https://doi.org/10.13140/RG.2.2.28011.20002)


### 📝 Selected Papers
- **Modeling a Hybrid System for Verifying Information Credibility** (2025)
  [![ISBN](https://img.shields.io/badge/ISBN-978--1--0699945--0--9-green)](https://isbnsearch.org/isbn/9781069994509)
  [![DOI](https://img.shields.io/badge/DOI-10.13140/rg.2.2.36348.24961-blue)](https://doi.org/10.13140/rg.2.2.36348.24961)

- **Hybrid System Ontology for Information Source Verification** (2025)  
  [![ISBN](https://img.shields.io/badge/ISBN-978--1--0699945--1--6-green)](https://isbnsearch.org/isbn/9781069994516)
  [![DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.22926.47680-blue)](https://doi.org/10.13140/RG.2.2.22926.47680)

### 📚 TREC Evaluation System
 **Evaluation of Information Retrieval Models on TREC AP 88-90** (2025)  
[![ISBN](https://img.shields.io/badge/ISBN-978--1--0699904--5--7-green)](https://isbnsearch.org/isbn/9781069990457)
[![Paper DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.22608.62721-blue)](https://doi.org/10.13140/RG.2.2.22608.62721)

> Évaluation comparative de modèles de recherche d'information sur les collections TREC AP 88-90.

**Technologies :** Python • Information Retrieval • BM25 • TF-IDF • Vector Space Models

**Résultats :**
- 📊 Analyse de ~243,000 documents
- 📈 Comparaison BM25 vs. VSM
- 🎯 Métriques MAP, NDCG, Precision@K

📄 [Lire l'article](https://doi.org/10.13140/RG.2.2.22608.62721)

  

📄 [**View all publications →**](https://dominiqueloyer.github.io/papers.html)

---

## 💻 Research Projects

### 🔍 Information Credibility Verification System
A hybrid system combining predicate logic and ML/AI for assessing information source credibility.
- **Technologies:** Python, NLP, Ontologies (OWL), Machine Learning
- **Status:** Active Research
- 📂 [Repository](#) | 📄 [Paper](https://doi.org/10.13140/rg.2.2.36348.24961)

### 🌐 Web Science Ontology
OWL ontology for modeling information verification systems.
- **Technologies:** OWL, RDF, Protégé
- **Status:** Published
- 📂 [Repository](#) | 📄 [Paper](https://doi.org/10.13140/RG.2.2.22926.47680)

### 🔤 Neural Machine Translation (English-Russian)
Neural machine translation system with attention mechanisms.
- **Technologies:** Python, TensorFlow, PyTorch, NMT
- **Status:** Completed
- 📂 [Repository](#) | 📄 [Paper](https://doi.org/10.13140/RG.2.2.17980.55687) [![ISBN](https://img.shields.io/badge/ISBN-978--1--0699904--9--5-green)](https://isbnsearch.org/isbn/9781069990495)


---

## 🛠️ Technical Skills

**Programming Languages:**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**AI/ML Frameworks:**  
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

**Research & Productivity Tools:**  
![Zotero](https://img.shields.io/badge/Zotero-CC2936?style=flat&logo=zotero&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat&logo=obsidian&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 📊 GitHub Statistics

<div align="center">

<!-- Contribution Graph (celui qui fonctionne déjà) -->
[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=DominiqueLoyer&custom_title=Dominique's%20Contribution%20Graph&hide_border=true&border_radius=15&bg_color=0d1117&color=58a6ff&line=58a6ff&point=79c0ff&area_color=79c0ff&title_color=58a6ff&area=true)](https://github.com/DominiqueLoyer)

<!-- Profile Details -->
![Profile Details](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=DominiqueLoyer&theme=radical)

<!-- Stats en grille 2x2 -->
<img width="49%" src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=DominiqueLoyer&theme=radical" />
<img width="49%" src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=DominiqueLoyer&theme=radical" />
<img width="49%" src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=DominiqueLoyer&theme=radical" />
<img width="49%" src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=DominiqueLoyer&theme=radical&utcOffset=-5" />

<!-- Trophies -->




</div>


---

## 🎯 Current Focus

- 🔬 Completing PhD dissertation on algorithmic bureaucracy
- 📝 Publishing research on AI transparency and accountability
- 💡 Developing explainable AI frameworks for recommendation systems
- 🌍 Contributing to open science and reproducible research

---
## 📚 Publications Highlights

| Année | Titre | Type | DOI |
|:-----:|:------|:----:|:---:|
| 2025 | **Le Léviathan Algorithmique : pouvoir, opacité et responsabilité à l'ère de l'intelligence artificielle** | Examen de synthèse doctoral | [![DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.28011.20002-blue)](https://doi.org/10.13140/RG.2.2.28011.20002) |
| 2025 | **Modeling a Hybrid System for Verifying the Credibility of Information Sources** | Preprint | [![DOI](https://img.shields.io/badge/DOI-10.13140/rg.2.2.36348.24961-blue)](https://doi.org/10.13140/rg.2.2.36348.24961) |
| 2025 | **Hybrid System for Verifying Credibility: An Ontology** | Preprint | [![DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.22926.47680-blue)](https://doi.org/10.13140/RG.2.2.22926.47680) |
| 2025 | **Evaluation of Information Retrieval Models on TREC AP 88-90** | Preprint | [![DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.22608.62721-blue)](https://doi.org/10.13140/RG.2.2.22608.62721) |
| 2025 | **Development and Evaluation of an English-to-Russian Neural MT System** | Preprint | [![DOI](https://img.shields.io/badge/DOI-10.13140/RG.2.2.17980.55687-blue)](https://doi.org/10.13140/RG.2.2.17980.55687) |


<p align="center">
  <a href="https://dominiqueloyer.github.io/papers.html">
    <img src="https://img.shields.io/badge/📄_View_All_Publications-orange?style=for-the-badge" alt="View All Publications"/>
  </a>
</p>



## 📫 Contact & Links

- 🌐 **Website:** [dominiqueloyer.github.io](https://dominiqueloyer.github.io)
- 📧 **Email:** 2e2g3zhvt@mozmail.com
- 💼 **LinkedIn:** [linkedin.com/in/dominique-loyer-456ab739b](https://www.linkedin.com/in/dominique-loyer-456ab739b/)
- 🔬 **ORCID:** [0009-0003-9713-7109](https://orcid.org/0009-0003-9713-7109)
- 📚 **Google Scholar:** [Profile](https://scholar.google.com/citations?user=JmRd6U0AAAAJ)
- 🔍 **ResearchGate:** [Dominique Loyer](https://www.researchgate.net/profile/Dominique-Loyer)

---

## 📜 License

Unless otherwise specified, research code is released under [MIT License](LICENSE).  
Academic publications follow their respective copyright agreements.

---

<p align="center">
  <i>⭐ If you find my work interesting, consider following or starring relevant repositories!</i>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=DominiqueLoyer&color=blue&style=flat-square&label=Profile+Views" alt="Profile views" />
</p>
