<h1 align="center">Hi 👋, I'm Ravi Doddi</h1>

<h3 align="center">
Mobile Architect · 17+ Years in Software Engineering · 12+ Years in Native iOS
<br />
Now Building Production-Grade Agentic AI Systems
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/ravi-doddi-32061110/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:doddi.ravi@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/iOSNinja">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🧭 About Me

I'm a hands-on **Mobile Architect and Technical Lead** based in Frisco, TX, with **17+ years in software engineering and 12+ years in native iOS** — building and scaling secure, high-traffic mobile apps and white-label platforms across iOS and Android.

I've delivered products from **POC → pilot → enterprise scale** at companies like **PDI Technologies** (40+ branded loyalty apps) and **7-Eleven** (Mobile Checkout, Digital Wallet, 7Rewards). My depth is in mobile architecture, modular platform design, payments/wallets, identity/security, and CI/CD automation — paired with cross-functional technical leadership across onshore and offshore teams.

**Currently:** Going deep on **AI/ML and Agentic AI** through two intensive off-time programs — **UT Austin's PGP in AI/ML Business Applications** (2025–2026) and **Interview Kickstart's Applied Agentic AI for SWEs** (2026). Equally comfortable with deterministic ML pipelines and probabilistic LLM-based agent systems — from data and modeling through deployment via Flask / FastAPI / Streamlit / Docker.

---

## 🎯 Mission

**Three domains, one engineering discipline.** Whether I'm architecting a mobile platform (17+ years and counting), training a classical ML model, or orchestrating multi-agent LLM systems — I bring the same rigor: modular design, observability, security, evaluation, and guardrails baked in from day one, regardless of whether the inference is deterministic or probabilistic.

---

## 💭 Philosophy

> **Build · Break · Learn · Ship.**
>
> Eval-driven. Guardrail-defended. Observability-first.
>
> The kind of system you can actually deploy, not just demo.

---

## 🏗️ Three Pillars of My Work

### 📱 Mobile Architecture & iOS Engineering — 12+ Years

- **Languages:** Swift, Objective-C, SwiftUI, Kotlin, Java
- **Architecture:** MVVM · MVC · Coordinators · Clean Architecture · Dependency Injection · SDK/XCFramework design · Modularization (CocoaPods/SPM)
- **Platform Engineering:** White-label platforms (40+ branded apps), configuration-driven UI rendering frameworks (JSON-driven), reusable feature modules
- **Payments & Wallet:** Apple Pay, Google Pay, Stripe, P97, Zipline, PCI-minded tokenized flows, loyalty/rewards integrations
- **Security & Identity:** Biometric auth (Face ID/Touch ID), Auth0, OAuth2/OIDC, JWT, MFA, TLS/cert pinning, AES-256, Keychain, jailbreak/root detection, iXGuard
- **Frameworks & SDKs:** UIKit, Core Data, Core Location, Branch, Arity, Foursquare Pilgrim, SFMC, Braze, Kount, Scandit, Card.io
- **DevOps:** Fastlane · Jenkins · CI/CD pipelines · XCTest/XCUITest · Firebase Analytics/Crashlytics · New Relic · Mixpanel · Qualys

### 🧠 Classical AI/ML — UT Austin PGP (2025–2026)

End-to-end ML lifecycle across regression, classification, and computer vision:

- **Foundations:** EDA · data preprocessing · feature engineering · model selection · hyperparameter tuning · cross-validation · business insights & actionable recommendations
- **Algorithms:** Decision Trees · Random Forest · Gradient Boosting · XGBoost · Logistic/Linear Regression · ensemble methods
- **Deep Learning:** Neural Networks · ANNs · CNNs · Transfer Learning · data augmentation · regularization
- **Evaluation:** RMSE · R² · Precision/Recall · F1 · AUC · confusion matrices · false-negative-aware tuning
- **Libraries:** Python, NumPy, Pandas, scikit-learn, XGBoost, TensorFlow/Keras, PyTorch, Matplotlib/Seaborn, Jupyter/Colab
- **Deployment:** Flask APIs · Streamlit UIs · Hugging Face Spaces · joblib serialization · batch + online prediction patterns

### 🤖 Agentic AI & LLM Systems — IK Applied Agentic AI for SWEs (2026)

Production-grade multi-agent systems with full engineering discipline:

- **Orchestration:** LangGraph multi-agent orchestration · `Send()` API parallel dispatch · ReAct tool-calling loops · Pydantic structured outputs · multi-turn memory (checkpointers) · human-in-the-loop
- **RAG:** Vector stores (Chroma, FAISS, Qdrant) · hybrid search (BM25 + dense) · SPLADE sparse embeddings · RRF fusion · source-attributed retrieval
- **Protocols:** MCP (Model Context Protocol) · Agent-to-Agent (A2A) · multimodal voice agents (Whisper STT + OpenAI TTS)
- **Observability:** LangSmith tracing · `@traceable` wrappers · structured JSON logging with trace IDs · log↔trace correlation across CloudWatch/Loki
- **Evaluation:** Routing accuracy · MRR · faithfulness/correctness LLM-as-judge · G-Eval · citation verification · DeepEval CI integration
- **Guardrails:** Layered input/output stack — regex blocks · OpenAI Moderation · Presidio PII redaction · Guardrails AI validators · LLM-based injection classifier · JSONL audit trail
- **Cost & Performance:** tiktoken accounting · model routing (gpt-4o-mini vs gpt-4o) · semantic caching with hit-rate metrics · per-agent cost/latency breakdown · budget enforcement · quality-regression CI gating

---

## 🌟 Featured Project

### 🦊 [Finnie — AI-Powered Personal Finance Tutor](https://github.com/iOSNinja/ai-finance-assistant)

**A 6-agent LLM system built on LangGraph that demonstrates three distinct tool-design patterns side by side.**

| Pattern | Agents |
|---|---|
| RAG over curated knowledge | Finance Q&A · Tax Education |
| Pure-math computation | Goal Planning · Portfolio Analysis |
| External APIs with TTL caching + graceful fallback | Market Analysis (yfinance) · News Synthesizer (Tavily, domain allowlist) |

**Production hardening from day one:**

- 🔭 **Observability** — LangSmith tracing with custom run names, structured JSON logging with embedded trace IDs
- 📊 **Evaluation framework** — 5 suites covering routing accuracy, MRR, faithfulness/correctness LLM-as-judge, citation verification, disclaimer-presence checks
- 🛡️ **Layered guardrails** — Regex + OpenAI Moderation + Presidio PII + Guardrails AI + LLM-based injection classifier, every decision logged to JSONL audit trail
- 💰 **Cost optimization** — Model routing (gpt-4o-mini for orchestrator/synthesizer, gpt-4o for specialists), semantic caching, per-agent cost/latency breakdown, daily/session budget enforcement
- ⚖️ **Compliance** — Deterministic synthesizer programmatically appends regulatory disclaimers to enforce education-vs-advice distinction required in fintech

**Stack:** LangGraph · LangChain · OpenAI gpt-4o-mini / gpt-4o · text-embedding-3-small · ChromaDB · yfinance · Tavily · Streamlit · Pydantic v2 · LangSmith · DeepEval · Presidio · Guardrails AI · `uv` · Python 3.12

---

## 🚀 Other Notable AI Projects

### Agentic AI (2026)

| Project | What It Demonstrates |
|---|---|
| **Multi-Agent Travel Planner** | LangGraph parallel agents over Tavily + SerpAPI |
| **SnackStack Voice Food Assistant** | Whisper STT + OpenAI TTS multimodal pipeline |
| **Real-Estate Negotiation Simulator** | MCP + Google ADK + A2A protocol exploration |
| **SupportDesk RAG Assistant** | 6-module RAG pipeline with eval and agentic patterns |
| **Hybrid Search & Retrieval** | Qdrant with SPLADE sparse + dense embeddings + RRF |

### Classical ML Capstones (2025–2026)

| Project | Domain | Highlights |
|---|---|---|
| **SuperKart Sales Forecasting** | Regression | Gradient Boosting + XGBoost; tuned via RMSE/R²; deployed Flask + Streamlit on Hugging Face |
| **Employee Attrition Prediction** | Classification | Identified at-risk employees + key drivers (comp, workload, commute); HR recommendations |
| **Medical Assistant** | GenAI / RAG | RAG over medical manuals — embeddings + retrieval + LLM prompting, reduced hallucinations |
| **HelmNet** | Computer Vision | CNN + transfer learning + augmentation for helmet-detection safety compliance |
| **ReneWind** | Predictive Maintenance | Classification for wind-turbine failures; false-negative-focused tuning |
| **EasyVisa** | Classification | Supervised ML for visa approval; ensemble comparison + feature engineering |

---

## 🛠️ Tech Stack

### 📱 Mobile

![Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![Objective-C](https://img.shields.io/badge/Objective--C-438EFF?style=for-the-badge&logo=apple&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0066CC?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=xcode&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=for-the-badge&logo=fastlane&logoColor=black)

### 🤖 AI / ML & Agentic AI

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4A574?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB6C2D?style=for-the-badge&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### 🚢 Backend & Deployment

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 🧰 Concepts I Live and Breathe

**📱 Mobile & iOS:**  
`Swift` · `Objective-C` · `SwiftUI` · `UIKit` · `Kotlin` · `Jetpack Compose` · `Core Data` · `Core Location` · `MVVM` · `MVC` · `Coordinators` · `Clean Architecture` · `Dependency Injection` · `XCFramework / SDK Design` · `Modularization (CocoaPods / SPM)`

**🏛️ Mobile Platform Engineering:**  
`White-Label Platforms` · `Configuration-Driven UI` · `Apple Pay` · `Google Pay` · `Tokenized Payment Flows` · `Biometric Auth (Face ID / Touch ID)` · `OAuth2 / OIDC` · `JWT` · `TLS / Cert Pinning` · `AES-256` · `Keychain` · `Jailbreak / Root Detection` · `iXGuard`

**🤖 AI / ML & Agentic AI:**  
`Multi-Agent Orchestration` · `RAG` · `Hybrid Search` · `MCP` · `A2A` · `LLM Evaluation` · `Guardrails` · `Cost Optimization` · `Observability` · `Feature Engineering` · `Transfer Learning` · `Hyperparameter Tuning` · `LLM-as-Judge`

**⚙️ Engineering Discipline:**  
`CI / CD` · `Fastlane` · `Jenkins` · `Feature Flags` · `A/B Testing` · `Eval-Driven Development` · `Architecture Reviews` · `Code Reviews` · `Technical Leadership` · `Onshore/Offshore Coordination`

---

## 📫 Let's Connect

Open to **AI/ML Engineering**, **Agentic AI Engineering**, **Mobile Architect**, and **Technical Lead** roles.

📍 Frisco, TX  
📧 **doddi.ravi@gmail.com**  
💼 [LinkedIn](https://www.linkedin.com/in/ravi-doddi-32061110/)  
💻 [GitHub](https://github.com/iOSNinja)  
🦊 [Finnie — Capstone Project](https://github.com/iOSNinja/ai-finance-assistant)

---

<p align="center">
  <i>Architect mindset, always learning, shipping production-grade systems — one commit at a time.</i>
</p>
