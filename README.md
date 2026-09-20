# 👋 Hi, I'm Jules

## Building AI systems you can trust, on real, messy, business data

> I build AI systems that plug into a company's real data, and I make them **reliable**: I know how to evaluate them, measure where they fail, and make them **abstain rather than be wrong**.

My edge is not "I can call an LLM." It's **measurable reliability**: retrieval evaluation, uncertainty quantification, calibrated abstention. My research background (conformal risk control) is exactly what makes this rigorous.

🌍 Neuchâtel, Switzerland · 🇨🇮🇨🇭🇫🇷 Ivorian, Swiss and French background
🎓 Dual Master's: Statistics (Neuchâtel) and ML/AI (Lyon 2)

---

## 🔥 Featured project

### 📄 [RAG Assurance, a system that knows when it misread](https://github.com/OJules/rag-assurance) · [**Live demo**](https://rag-assurance.streamlit.app/)

A document-QA assistant for insurance contracts: the full chain, from a business question to a **usable, traceable decision**.

Not "a RAG that reads PDFs", but a system that **knows when it misread, says so, reasons contract-by-contract to avoid mixing them, and measures its own reliability.**

- **Retrieval isn't the bottleneck**: Recall@5 ≈ 0.97. The errors that remain have *perfect* retrieval, so the weak link is reasoning, not search.
- **Contract confusion, measured**: when several contracts share an attribute with different values, a global RAG mixes them. I isolated reasoning per contract and built trap questions to measure it: **global 0/11 vs per-contract 11/11 correctly attributed**, at about 2× the cost. A measured trade-off, not an assumption.
- **Honest about extraction quality**: each passage carries an explainable quality score (good / medium / poor) and *why*, and I document what it still misses (column interleaving, character spacing).
- **Deployed**, with a business-facing interface: decision, evidence, sources, uncertainty.

Stack: Python · sentence-transformers (E5) · Chroma · Groq · Streamlit · pdfplumber

---

## 🎯 What I focus on

- **Reliable RAG & document AI**: retrieval, grounding, citation, abstention
- **Evaluation of AI systems**: gold sets, the right metrics, and knowing when a metric lies
- **Uncertainty quantification**: conformal prediction (CRC, K-CRC, sem-CRC), calibrated abstention
- **From prototype to deployment**: turning a model into something a business can actually use

---

## 💼 Professional experience

- **Data Scientist intern**, WTO, Economic Research and Statistics Division, Geneva (2026)
- **Data Scientist (AI Research)**, Université Lyon 2 (2025)
- **Statistical Research Analyst**, LIVES Institute, UNIL (2022)
- **Data Analyst & Product Designer**, Assurland Africa (2021)
- **Project Manager**, ESN Neuchâtel (2023 to 2025)
- **Mathematics Tutor**, Anacours (2025) and Université Internationale de Grand Bassam (2019 to 2020)

---

## 🧪 Other projects

### 🎲 [Conformal Risk Control](https://github.com/OJules/Predicition-Conforme)
Uncertainty quantification for medical AI: CRC, K-CRC and sem-CRC, with a benchmarking pipeline. *The methodological backbone behind the reliability angle above.*

### 🌐 [Domain Adaptation](https://github.com/OJules/Adaptation-de-Domaine)
Transfer-learning techniques for domain shift across data distributions.

### ⚖️ [Fairness & Imbalanced Data](https://github.com/OJules/Fairness-and-imbalanced-data)
Bias-mitigation strategies and fairness metrics on imbalanced datasets.

---

## 🛠️ Tech

**Languages**: Python, R, SQL
**ML / DS**: PyTorch, TensorFlow, scikit-learn, pandas
**LLM / RAG**: sentence-transformers, Chroma, retrieval evaluation, answer-contract design
**Delivery**: Streamlit, Git, deployment

---

## 🎓 Background

**M.Sc. ML/AI (MIASHS)**, Université Lyon 2 (2024 to 2025)
*Thesis: conformal risk control for semantic uncertainty quantification in CT imaging.*

**M.Sc. Statistics**, Université de Neuchâtel (2021 to 2023)
*Thesis: statistical evaluation of public-prevention campaigns in Switzerland.*

**B.Sc. Mathematics**, Université Internationale de Grand Bassam, Côte d'Ivoire (2017 to 2020)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jules-odje)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:odjejulesgeraud@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OJules)

<div align="center">
<img height="165em" src="https://github-readme-stats.vercel.app/api?username=OJules&show_icons=true&theme=default&include_all_commits=true&count_private=true"/>
</div>

---

*Interested in the intersection of ML/statistics and development economics, especially African markets.*
