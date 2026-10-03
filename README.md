<div align="center">

<!-- 1. Custom animated hero (assets/hero.svg): pulsing neural net + ECG signal line -->
<img src="assets/hero.svg" alt="Anu Mishra - Data Science & Machine Learning" width="100%" />

<!-- 2. Typing animation -->
<a href="https://github.com/Anumishra02">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&width=760&lines=Turning+raw+data+into+decisions;Electronics+Engineering+%2B+Deep+Learning;Training+models+in+PyTorch+%26+scikit-learn;Biomedical+Signal+Processing+with+AI;AI%2FML+Research+Intern+%40+HCL+Technologies" alt="Typing SVG" />
</a>

<br/>

<!-- 3. Live badges -->
<img src="https://komarev.com/ghpvc/?username=Anumishra02&label=Profile%20Views&color=7c3aed&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/Anumishra02?style=for-the-badge&logo=github&color=ff6ec7" />
<img src="https://img.shields.io/badge/Open_to-Data_Science_and_ML_Roles_2027-22d3ee?style=for-the-badge" />
<br/><br/>

<a href="https://anumishra.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/anumish/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:anumishra555555@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<!-- <a href="YOUR_RESUME_LINK"><img src="https://img.shields.io/badge/Resume-7C3AED?style=for-the-badge&logo=readme&logoColor=white" /></a> -->

</div>

<img src="assets/divider.svg" width="100%" height="4" />

## 👋 Hey, I'm Anu

I'm an **Electronics Engineering undergrad (CGPA 8.41) who fell for data science**, and I'm currently an **AI/ML Research Intern at HCL Technologies**, training deep learning models on **biomedical signals**.

I like the full loop: messy data → clean features → a model I can defend with the right metrics → something people can actually use.

```python
class AnuMishra:
    def __init__(self):
        self.role      = "Data Science & ML Engineer in the making"
        self.background = ["Electronics Engineering", "Embedded C/C++", "Signal Processing"]
        self.daily     = ["Python", "Pandas", "NumPy", "scikit-learn", "PyTorch"]
        self.now       = "Deep learning on biomedical signals @ HCL"
        self.graduating = "June 2027"

    def philosophy(self):
        return "Measure first. Explain the result. Then ship it."

    def open_to(self):
        return ["Data Science internships", "ML Engineer roles", "Research collabs"]
```

<div align="center">

| 🔭 Now | 📚 Learning | 🎯 Next |
| :---: | :---: | :---: |
| Biomedical signal DL model (PyTorch) | LLMs, RAG & prompt engineering | End-to-end MLOps on Azure |
| ATSync (NLP + Gemini) | Advanced feature engineering | Open-source ML contributions |

</div>

<img src="assets/divider.svg" width="100%" height="4" />

## 📈 Numbers I'm Proud Of

<div align="center">

<img src="https://img.shields.io/badge/R%C2%B2%20Score-0.90-7c3aed?style=for-the-badge" />
<img src="https://img.shields.io/badge/Training%20Rows-6%2C019-22d3ee?style=for-the-badge" />
<img src="https://img.shields.io/badge/Predictions%20within%20%E2%82%B92L-81%25-ff6ec7?style=for-the-badge" />
<img src="https://img.shields.io/badge/Cross--Validation-10--fold-a78bfa?style=for-the-badge" />
<img src="https://img.shields.io/badge/CGPA-8.41%2F10-22d3ee?style=for-the-badge" />
<img src="https://img.shields.io/badge/Certifications-3-ff6ec7?style=for-the-badge" />

</div>

---

## 🧪 How I Work

```mermaid
flowchart LR
    A[📥 Raw Data] --> B[🧹 Clean & Validate]
    B --> C[🛠️ Feature Engineering]
    C --> D[🤖 Train Model]
    D --> E[📏 Cross-Validate]
    E --> F{Good enough?}
    F -- No --> C
    F -- Yes --> G[🚀 Deploy as API]

    classDef step fill:#4c1d95,stroke:#a78bfa,color:#fff
    classDef decide fill:#be185d,stroke:#ff6ec7,color:#fff
    class A,B,C,D,E,G step
    class F decide
```

<details>
<summary><b>🧠 Click to open my "new dataset" checklist</b></summary>

<br/>

1. **Understand the target.** What decision will this model support, and what does a wrong prediction cost?
2. **Audit the data.** Check types, units, missing values, duplicates and leakage.
3. **Clean the awkward columns.** In CarVal, mileage, engine and power arrived as text with units mixed in.
4. **Engineer features.** Derive things like *car age* and *km per year* instead of feeding raw columns.
5. **Baseline first.** Beat a simple model before reaching for a complex one.
6. **Validate honestly.** K-fold CV and a held-out set, plus error metrics a non-technical person can read.
7. **Explain, then ship.** Wrap it in an API and a UI so the result is usable.

</details>

<img src="assets/divider.svg" width="100%" height="4" />

## 🚀 Featured Projects

*Click a project to expand the case study.*

<details open>
<summary><b>🚗 CarVal — Used-Car Price Predictor</b> &nbsp;·&nbsp; <code>Gradient Boosting</code> <code>scikit-learn</code> <code>Flask</code></summary>

<br/>

A machine learning system that predicts used-car prices and compares them to the live market.

| | |
| --- | --- |
| **Data** | 6,019 listings across 11 cities, cleaned from raw mileage, engine and power fields |
| **Features** | Derived car age and kilometers per year; OneHotEncoder across 13 inputs |
| **Model** | `GradientBoostingRegressor` (500 estimators, depth 5, learning rate 0.05) |
| **Result** | **R² = 0.90** with 10-fold CV; **81%** of held-out predictions within ₹2L of the true price |
| **Deployment** | Flask backend with 4 API routes (auto-fill, market comparison), dark-themed live-price UI on Render, 30 brands and 1,800+ models |

[🔗 View on GitHub](https://github.com/Anumishra02/CarVal)

</details>

<details>
<summary><b>🧬 Biomedical Signal Analysis — HCL Technologies</b> &nbsp;·&nbsp; <code>PyTorch</code> <code>Pandas</code> <code>NumPy</code></summary>

<br/>

Research internship project (Jun 2026 – present).

- Built and trained a **PyTorch deep learning model** for biomedical signal analysis.
- Designed **custom loss functions and optimization strategies** tailored to the task.
- Led **signal preprocessing and feature engineering**, then evaluated performance across multiple metrics.
- Diagnosed performance bottlenecks and proposed **empirically backed architecture improvements**.

*Code stays private because it is part of an internship project.*

</details>

<details>
<summary><b>📄 ATSync — AI Resume Analyzer</b> &nbsp;·&nbsp; <code>NLP</code> <code>Gemini AI</code> <code>FastAPI</code> &nbsp;·&nbsp; <i>ongoing</i></summary>

<br/>

- Scores resumes against job descriptions using **NLP keyword extraction**, with a **45% improvement in match accuracy** in benchmark tests.
- Integrates **Google Gemini** for grammar analysis, interview-question generation and cover-letter drafting, **cutting manual effort by about 60%**.
- Async **FastAPI** services with PDF parsing and Pydantic validation, with **sub-300 ms** responses in local load tests.

[🔗 View on GitHub](https://github.com/Anumishra02/ATSync)

</details>

<details>
<summary><b>🧑‍💻 CodeSense AI — AI Code Reviewer</b> &nbsp;·&nbsp; <code>Gemini AI</code> <code>Node.js</code> <code>React</code></summary>

<br/>

An LLM-assisted code-review tool that generates improvement suggestions, cutting manual review workload by about 40%, with REST APIs responding in under 250 ms.

[🔗 View on GitHub](https://github.com/Anumishra02/CodeSense-AI)

</details>

<div align="center">
<a href="https://github.com/Anumishra02/CodeSense-AI"><img height="110" src="https://github-readme-stats.vercel.app/api/pin/?username=Anumishra02&repo=CodeSense-AI&theme=tokyonight&hide_border=true" /></a>
</div>

<img src="assets/divider.svg" width="100%" height="4" />

## ⚙️ Tech Stack

### 🐍 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 📊 Data Science & Analysis
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### 🤖 Machine Learning & Deep Learning
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Gradient Boosting](https://img.shields.io/badge/Gradient%20Boosting-7C3AED?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-FF6EC7?style=for-the-badge)
![Feature Engineering](https://img.shields.io/badge/Feature%20Engineering-22D3EE?style=for-the-badge)

### ✨ Generative AI
![Gemini](https://img.shields.io/badge/Gemini%20AI-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-111827?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-111827?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-111827?style=for-the-badge)

### 🚀 Deployment & Tools
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### 🔌 Embedded & Signals (my Electronics roots)
![Embedded C/C++](https://img.shields.io/badge/Embedded%20C%2FC++-00599C?style=for-the-badge)
![Microcontrollers](https://img.shields.io/badge/Microcontrollers-0D9488?style=for-the-badge)
![Signal Processing](https://img.shields.io/badge/Signal%20Processing-22D3EE?style=for-the-badge)

<details>
<summary><b>🔭 Currently exploring</b></summary>

<br/>

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

</details>

<details>
<summary><b>🌐 Also comfortable with (web)</b></summary>

<br/>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-404D59?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)

</details>

<img src="assets/divider.svg" width="100%" height="4" />

## 🎓 Education, Certifications & Wins

| | |
| --- | --- |
| 🎓 **B.Tech, Electronics Engineering** | Kamla Nehru Institute of Technology · CGPA **8.41** · Expected June 2027 |
| 🏅 **Microsoft AI & ML Engineering** | Supervised, unsupervised & deep learning; MLOps on Azure |
| 🏅 **Oracle Foundations in AI** | Machine learning and ethical AI |
| 🏅 **IBM Back-End Development** | Node.js and Express applications |
| 🏆 **Smart India Hackathon** | Qualified among 50+ teams |

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Anumishra02&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="180" src="https://streak-stats.demolab.com/?user=Anumishra02&theme=tokyonight&hide_border=true" />

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anumishra02&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Anumishra02&theme=tokyo-night&hide_border=true&area=true" width="100%" />

<img src="https://github-profile-trophy.vercel.app/?username=Anumishra02&theme=algolia&no-frame=true&margin-w=15&margin-h=15" />

</div>

### 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Anumishra02/Anumishra02/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Anumishra02/Anumishra02/output/github-contribution-grid-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/Anumishra02/Anumishra02/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</div>

<img src="assets/divider.svg" width="100%" height="4" />

## 🛣️ Roadmap 2026–27

- [x] Train and deploy an end-to-end ML model (CarVal)
- [x] Start a research internship in deep learning (HCL)
- [x] Earn the Microsoft AI & ML Engineering certificate
- [ ] Publish 3 data-science case studies with notebooks
- [ ] Build a RAG project end-to-end
- [ ] Compete in a Kaggle competition
- [ ] Convert the internship into a full-time ML role

---

## 🎲 Just for Fun

<div align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="80%" />
<br/>
<img src="https://readme-jokes.vercel.app/api?theme=tokyonight" width="60%" />
<br/><sub>↻ Refresh the page for a new quote and joke</sub>
</div>

---

<div align="center">

### ☕ Have a dataset, a problem or an opportunity? Let's talk.

<a href="mailto:anumishra555555@gmail.com"><img src="https://img.shields.io/badge/Say%20Hello-7c3aed?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/anumish/"><img src="https://img.shields.io/badge/Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6EC7,100:7C3AED&height=120&section=footer" width="100%" />

</div>
