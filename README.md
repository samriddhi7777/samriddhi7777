<div align="center">

# Hi, I'm Samriddhi Thakur 👋

**B.Tech CSE (E-Commerce Technology)** @ VIT Bhopal University | Building AI-augmented systems for real e-commerce problems

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:samriddhithakur7777@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/[YOUR-LINKEDIN-HANDLE](https://www.linkedin.com/in/samriddhi-thakur-6303a5282/))

</div>

---

### 👋 About Me

I'm a final-year CSE student specializing in **E-Commerce Technology**, focused on the intersection of **full-stack engineering** and **applied ML** — building systems that solve real marketplace problems, not toy demos.

- 🎓 **Education:** B.Tech CSE (Spec. E-Commerce Technology), VIT Bhopal University — **CGPA: 8.84/10**
- 💡 **Core Focus:** Full-stack platforms, fraud/ML detection systems, explainable AI, data-driven dashboards

---

### 🛠️ Technical Skill Stack

- **💻 Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

- **🧠 ML & Data:** ![XGBoost](https://img.shields.io/badge/XGBoost-4f46e5?style=flat-square) ![LightGBM](https://img.shields.io/badge/LightGBM-4f46e5?style=flat-square) ![SHAP](https://img.shields.io/badge/SHAP-4f46e5?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)

- **🔌 Web & Backend:** ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

- **🗄️ Databases & Cloud:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

- **⚙️ Tools:** ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

### 🚀 Featured Projects

#### 1. TrueComp — Salary Transparency Platform for Indian Tech

> **A Levels.fyi-equivalent built for the Indian market, with a custom engine that normalizes company-specific level names onto a universal scale.**

```
┌──────────────────┐ ─────────► ┌──────────────────┐ ─────────────► ┌────────────────────────┐
│  Next.js 14 UI   │            │  API Routes +    │                │  PostgreSQL + Prisma   │
│  (App Router)    │ ◄───────── │  NextAuth v5      │ ◄───────────── │  (Zod-validated data)  │
└──────────────────┘            └──────────────────┘                └────────────────────────┘
                                          │
                                          ▼
                              ┌────────────────────────┐
                              │  normalize.ts engine    │
                              │  Company bands → L1–L7  │
                              └────────────────────────┘
```

- **Normalization Engine:** Designed `normalize.ts` to map arbitrary company-specific level names (e.g. "SDE-2", "L4", "T3") onto a consistent L1–L7 scale for fair cross-company comparison.
- **Auth & Validation:** Implemented NextAuth v5 with Google OAuth, and end-to-end Zod validation across all API routes.
- **Live Comp Calculator:** Built a multi-step submission form with a real-time compensation calculator.
- **Technologies:** `Next.js 14`, `TypeScript`, `PostgreSQL`, `Prisma`, `NextAuth v5`, `Zod`
- 🔗 **Live:** [truecomp.vercel.app](https://truecomp.vercel.app)

#### 2. Smart Return Fraud Detector — E-Commerce Fraud Detection System

> **An ML system that detects six distinct e-commerce fraud patterns, including coordinated fraud rings, with full model explainability.**

```
┌──────────────────┐ ─────────► ┌──────────────────┐ ─────────────► ┌────────────────────────┐
│ Streamlit         │            │  FastAPI          │                │ XGBoost + LightGBM     │
│ Dashboard         │ ◄───────── │  Backend (Render) │ ◄───────────── │ + SHAP + NetworkX      │
└──────────────────┘            └──────────────────┘                └────────────────────────┘
```

- **Multi-Pattern Detection:** Engineered detection logic for six fraud patterns across the return pipeline.
- **Explainability:** Integrated SHAP to surface *why* a specific return was flagged, making the model's output auditable rather than a black box.
- **Fraud Ring Detection:** Used NetworkX graph analysis to identify coordinated fraud rings, not just individual bad actors.
- **Full-Stack Deployment:** FastAPI backend on Render, Streamlit dashboard on Streamlit Community Cloud.
- **Technologies:** `Python`, `XGBoost`, `LightGBM`, `SHAP`, `NetworkX`, `FastAPI`, `Streamlit`

---


### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=samriddhi7777&theme=tokyonight&hide_border=true" alt="GitHub Streak Stats" width="49%"/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=samriddhi7777&theme=react-dark&hide_border=true" alt="GitHub Activity Graph" width="49%"/>
</p>

---


<div align="center">

**"Ship it, explain it, own it."**

</div>
