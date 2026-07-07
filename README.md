<div align="center">

# Nathan Sujatno

**AI Engineering Intern @ Valero Energy · CS + Intelligent Systems @ UT Dallas**

[![Portfolio](https://img.shields.io/badge/Portfolio-6D28D9?style=flat-square&logo=vercel&logoColor=white)](https://nathan-sujatno.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4C1D95?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nathan-sujatno/)
[![GitHub](https://img.shields.io/badge/GitHub-312E81?style=flat-square&logo=github&logoColor=white)](https://github.com/Nsujatno)
[![Email](https://img.shields.io/badge/Email-5B21B6?style=flat-square&logo=gmail&logoColor=white)](mailto:nathan.sujatno@gmail.com)

Richardson, TX

</div>

---

## About

CS + Intelligent Systems (fast-track master's) student at UT Dallas, graduating May 2027 (BS) / May 2028 (MS), Hobson Wildenthal Honors College. Currently an AI Engineering Intern at Valero Energy, building an LLM-powered document extraction pipeline and its evaluation harness.

Focused on AI/agentic systems engineering — retrieval, evaluation, and multi-agent orchestration — with a full-stack background (React/Next.js, FastAPI/Node, AWS). More interested in whether a system is reliable and explainable than in how flashy the demo looks.

**Open to:** Spring 2027 AI engineering internships

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-14151A?style=flat-square&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-14151A?style=flat-square&logo=typescript&logoColor=3178C6)
![SQL](https://img.shields.io/badge/SQL-14151A?style=flat-square&logo=postgresql&logoColor=4169E1)

**AI / ML**
![LangGraph](https://img.shields.io/badge/LangGraph-14151A?style=flat-square&logo=langchain&logoColor=8B5CF6)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-14151A?style=flat-square&logoColor=8B5CF6)
![PyTorch](https://img.shields.io/badge/PyTorch-14151A?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-14151A?style=flat-square&logo=scikitlearn&logoColor=F7931E)
![ClearML](https://img.shields.io/badge/ClearML-14151A?style=flat-square&logoColor=8B5CF6)

**Backend & Data**
![FastAPI](https://img.shields.io/badge/FastAPI-14151A?style=flat-square&logo=fastapi&logoColor=009688)
![Node.js](https://img.shields.io/badge/Node.js-14151A?style=flat-square&logo=nodedotjs&logoColor=339933)
![MongoDB](https://img.shields.io/badge/MongoDB-14151A?style=flat-square&logo=mongodb&logoColor=47A248)
![Supabase](https://img.shields.io/badge/Supabase-14151A?style=flat-square&logo=supabase&logoColor=3ECF8E)
![Pinecone](https://img.shields.io/badge/Pinecone-14151A?style=flat-square&logoColor=8B5CF6)

**Frontend & Cloud**
![React](https://img.shields.io/badge/React-14151A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-14151A?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-14151A?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![AWS](https://img.shields.io/badge/AWS-14151A?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-14151A?style=flat-square&logo=azuredevops&logoColor=0078D7)

---

## AI / ML Focus Areas

| Domain | Details |
|---|---|
| Retrieval & RAG | BM25, dense, and hybrid (RRF) retrieval; benchmarking against hand-labeled golden datasets |
| Evaluation | LLM-as-judge scoring (faithfulness, relevance, completeness); automated eval pipelines with ClearML |
| Agentic workflows | Multi-agent orchestration and routing with LangGraph |
| Document extraction | LLM-powered structured extraction from unstructured enterprise data (Docling + LlamaIndex) |

---

## Featured Projects

<details>
<summary><b>Ask My Doc</b> — RAG evaluation framework (in progress, targeting Sept 2026)</summary>

A production-style evaluation harness for RAG over HuggingFace documentation. Benchmarks BM25, dense, and hybrid (RRF) retrieval against a hand-labeled golden dataset, scored with an LLM-as-judge on faithfulness, relevance, and completeness.

| | |
|---|---|
| **Stack** | Python, pgvector, text-embedding-3-small, Gemini 2.5 Flash, Streamlit, Docker |
| **Focus** | Retrieval strategy comparison + eval rigor, not just pipeline construction |
| **Status** | In development |

</details>

<details>
<summary><b>GreenGain</b> — 2nd Place, HackEarth (Feb 2026)</summary>

Multi-agent workflow that routes vector retrieval strategy (local vs. hybrid) based on user geographic data to produce location-specific tax recommendations, with a validation layer enforcing hard financial constraints.

| | |
|---|---|
| **Stack** | Python, LangGraph |
| **Reliability** | Programmatic filter guarantees 100% compliance with ROI thresholds under 30 years |
| **Result** | 2nd place, HackEarth |

</details>

<details>
<summary><b>Eco Quest</b> — 1st Place / 1,000+ participants, Dev Season of Code (Feb–Mar 2026)</summary>

Personalized carbon-reduction assistant: a LangGraph workflow generates missions from survey data and CO2 calculations, a Gemini Vision pipeline scans receipts to estimate footprint, and an agentic shopping assistant streams personalized suggestions using purchase history from Supabase.

| | |
|---|---|
| **Stack** | LangGraph, Gemini 2.5 Flash, Gemini Vision, Supabase, SSE streaming |
| **Result** | 1st place / 1,000+ participants |

</details>

<details>
<summary><b>OPTCG Binder App</b> — One Piece TCG binder builder</summary>

Web app for building and organizing One Piece TCG binder pages, with an AI feature that uses embeddings to suggest visually or thematically similar cards.

| | |
|---|---|
| **Stack** | Embeddings-based similarity search |

</details>

---

## Experience

**AI Engineering Intern** — Valero Energy Corporation, San Antonio, TX
*May 2026 – Current*
- Owning end-to-end development of an LLM-powered document extraction system (Docling + LlamaIndex) reducing manual processing time by ~95%
- Built an automated ClearML evaluation pipeline benchmarking extraction accuracy at 90% against a ground-truth dataset, removing manual validation bottlenecks

`LlamaIndex` `Docling` `ClearML` `LLM Evaluation`

**Fullstack Intern** — NRVE (AI-powered mental health app for kids), Remote
*June 2025 – August 2025*
- Built a serverless AWS backend (Lambda, API Gateway, S3) + MongoDB with 15+ REST endpoints
- Cut audio endpoint response time from 3.5s to 40ms using CloudFront edge caching
- Built the backend-to-mobile integration layer (React Native, Axios) including mini-game state and session management

`AWS Lambda` `CloudFront` `MongoDB` `React Native`

---

## Leadership

**ACM Dev Lead & Officer — MeteorMate**
*June 2025 – Current*
Co-leading a 7-person team building an AI-powered roommate matching platform for UTD students — sprint planning, task delegation, code review.

**Project Manager — AI MD, UTD Student Organization**
*September 2025 – December 2025*
Directed a team of 4 developers building a full-stack MERN healthcare application.

---

## Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 1st Place / 1,000+ participants | Dev Season of Code Hackathon — Eco Quest |
| 2nd Place | HackEarth — GreenGain |
| Academic Excellence Scholar | Hobson Wildenthal Honors College, UT Dallas |

</div>

---

<div align="center">

[nathan-sujatno.vercel.app](https://nathan-sujatno.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/nathan-sujatno/) · [nathan.sujatno@gmail.com](mailto:nathan.sujatno@gmail.com)

</div>
