<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=280&color=gradient&customColorList=12,20,24,30&text=ASHISH%20GUPTA&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35"/>

# BUILDING SYSTEMS THAT THINK

### ◈ Backend Engineer • ◉ AI Systems Builder • ◆ Scalable Architectures

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&pause=1200&color=38BDF8&center=true&vCenter=true&width=900&lines=Building+Scalable+Systems+That+Think;Low-Latency+Products+at+Scale;AI+Infrastructure+%7C+Distributed+Systems;Turning+Complexity+Into+Products" />

<br>

<a href="mailto:ashishking554@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail"/>
</a>

<a href="https://linkedin.com/in/ashish-gupta-007620292">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/>
</a>

<a href="https://github.com/Azziz14">
<img src="https://img.shields.io/badge/GitHub-111111?style=for-the-badge&logo=github"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Azziz14&style=for-the-badge&color=blueviolet"/>

</div>

---

# ◬ ABOUT

I build **high-performance backend systems** and **AI-powered products** focused on:

◆ Scalability  
◆ Reliability  
◆ Performance  
◆ Distributed Architectures  
◆ Real-time Systems  

I enjoy solving engineering problems where **speed**, **architecture**, and **intelligence** matter.

---

# ⌬ TECH ARSENAL

## 💻 Languages

<p align="center">
<img src="https://skillicons.dev/icons?i=python,java,cpp,c,javascript,typescript,sql"/>
</p>

## ⚙ Backend

<p align="center">
<img src="https://skillicons.dev/icons?i=spring,nodejs,express,fastapi,redis,mongodb,mysql,docker"/>
</p>

## 🎨 Frontend

<p align="center">
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind"/>
</p>

## 🤖 AI / ML

<p align="center">
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch"/>
</p>

<p align="center">
<img src="https://img.shields.io/badge/RAG-4ECDC4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Transformers-FFA726?style=for-the-badge"/>
<img src="https://img.shields.io/badge/QLoRA-45B7D1?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PEFT-9B59B6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/BERT-FF6B6B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/XGBoost-16A085?style=for-the-badge"/>
</p>

---

# ◉ FLAGSHIP SYSTEMS

---

## 🎯 InterviewPilot AI

### Adaptive RAG Interview Intelligence Platform

**Problem**

Traditional interview preparation platforms are static and generic.

**Solution**

Built an adaptive AI platform that learns from candidate performance.

### Architecture

```text
                ┌────────────────────┐
                │   Resume Upload    │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Skill Extraction   │
                └─────────┬──────────┘
                          │
        ┌─────────────────┴─────────────────┐
        ▼                                   ▼
┌───────────────┐                   ┌───────────────┐
│ JD Analyzer   │                   │ Vector Store  │
│ Matcher       │◄─────────────────►│ (ChromaDB)    │
└───────┬───────┘                   └───────┬───────┘
        │                                   │
        └───────────────┬───────────────────┘
                        ▼
              ┌───────────────────┐
              │ Question Engine   │
              └─────────┬─────────┘
                        │
                        ▼
              ┌───────────────────┐
              │ LLM Evaluation    │
              └─────────┬─────────┘
                        │
         ┌──────────────┴──────────────┐
         ▼                             ▼
┌──────────────────┐         ┌──────────────────┐
│ Weakness Engine  │         │ Performance DB   │
└─────────┬────────┘         └──────────────────┘
          │
          ▼
┌────────────────────────────┐
│ Personalized Roadmap       │
└────────────────────────────┘
```

### Stack

`FastAPI` `React` `Gemini` `ChromaDB` `PostgreSQL`

---

## 📈 CryptoTrade

### Low-Latency Trading Infrastructure

**Problem**

Retail trading systems suffer from slow execution.

**Solution**

Built an event-driven real-time trading engine.

### Architecture

```text
                ┌────────────────────┐
                │ Binance WebSocket  │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Stream Processor   │
                └─────────┬──────────┘
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
 ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
 │ Order Engine │ │ Risk Engine  │ │ Price Cache  │
 └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
        │                │                │
        ▼                ▼                ▼
 ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
 │ Portfolio DB │ │ Redis OTP    │ │ Analytics    │
 └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
        └────────────┬───┴────────────┬───┘
                     ▼                ▼
             ┌────────────────────────────┐
             │ React Trading Dashboard    │
             └────────────────────────────┘
```

### Metrics

◆ <100ms latency  
◆ Real-time execution  
◆ High throughput  

### Stack

`Spring Boot` `Java` `Redis` `MongoDB`

---

## 🧠 QueryForge AI

### Natural Language → SQL Compiler

**Problem**

SQL writing is slow and technical.

**Solution**

Built an LLM system that converts natural language into SQL.

### Architecture

```text
               ┌────────────────────┐
               │ User Query (NL)    │
               └─────────┬──────────┘
                         │
                         ▼
               ┌────────────────────┐
               │ Intent Analyzer    │
               └─────────┬──────────┘
                         │
          ┌──────────────┴──────────────┐
          ▼                             ▼
 ┌──────────────────┐         ┌──────────────────┐
 │ Schema Context   │         │ CodeLlama Model  │
 │ Retrieval        │────────►│ SQL Generation   │
 └──────────────────┘         └─────────┬────────┘
                                        │
                                        ▼
                             ┌──────────────────┐
                             │ SQL Validator    │
                             └─────────┬────────┘
                                       │
                                       ▼
                             ┌──────────────────┐
                             │ Final SQL Output │
                             └──────────────────┘
```

### Metrics

◆ 80k+ Training Data  
◆ 79% Accuracy  
◆ <1s Inference  

### Stack

`Transformers` `QLoRA` `FastAPI`

---

## 🏥 MediSense AI

### Clinical Intelligence Platform

**Problem**

Disease detection from data is difficult.

**Solution**

Built predictive healthcare intelligence.

### Architecture

```text
                ┌────────────────────┐
                │ Medical Records    │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Data Cleaning      │
                └─────────┬──────────┘
                          │
         ┌────────────────┴────────────────┐
         ▼                                 ▼
┌──────────────────┐              ┌──────────────────┐
│ Feature Extract  │              │ Clinical NLP     │
│ (Numerical)      │              │ (BERT)           │
└─────────┬────────┘              └─────────┬────────┘
          └───────────────┬─────────────────┘
                          ▼
                ┌────────────────────┐
                │ Prediction Engine  │
                └─────────┬──────────┘
                          │
          ┌───────────────┴───────────────┐
          ▼                               ▼
┌──────────────────┐             ┌──────────────────┐
│ Diagnostic Layer │             │ Health Advisory  │
└──────────────────┘             └──────────────────┘
```

### Stack

`TensorFlow` `BERT` `Flask`

---

## 📧 Email Spam Classifier

### Intelligent Email Filtering System

**Problem**

Spam and phishing emails reduce productivity.

**Solution**

Built an ML-powered Gmail-integrated spam intelligence system.

### Architecture

```text
               ┌────────────────────┐
               │ Gmail API Fetcher  │
               └─────────┬──────────┘
                         │
                         ▼
               ┌────────────────────┐
               │ Email Preprocessor │
               └─────────┬──────────┘
                         │
         ┌───────────────┴───────────────┐
         ▼                               ▼
┌──────────────────┐             ┌──────────────────┐
│ Feature Extract  │             │ Label Pipeline   │
│ TF-IDF / NLP     │             │ Spam / Ham       │
└─────────┬────────┘             └─────────┬────────┘
          └──────────────┬─────────────────┘
                         ▼
               ┌────────────────────┐
               │ ML Classification  │
               │ Engine             │
               └─────────┬──────────┘
                         │
         ┌───────────────┴───────────────┐
         ▼                               ▼
┌──────────────────┐             ┌──────────────────┐
│ Analytics Layer  │             │ Admin Dashboard  │
└──────────────────┘             └──────────────────┘
```

### Stack

`Python` `Scikit-learn` `Flask`

---

# 📊 ENGINEERING SIGNALS

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Azziz14&show_icons=true&theme=tokyonight&hide_border=true"/>
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Azziz14&layout=compact&theme=tokyonight&hide_border=true"/>

<br><br>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Azziz14&theme=tokyo-night"/>

</div>

---

# 🔥 CONTRIBUTION HEATMAP

<div align="center">

<img width="95%" src="https://ghchart.rshah.org/58A6FF/Azziz14"/>

</div>

---

# 🧩 PROBLEM SOLVING

◈ **150+ LeetCode Problems Solved**

Core domains:

`Arrays` `Trees` `Graphs` `DP`  
`Hashing` `Sliding Window` `Stacks`  
`Binary Search` `Greedy`

---

# 💼 EXPERIENCE

### 🌐 MagnumCorps  
**Web Development Intern**  
`Jun 2024 — Aug 2024`

---

### 🚀 Yashika Tour & Travel  
**Freelance Full Stack Developer**  
`Oct 2024 — Dec 2024`

---

# 🎓 CERTIFICATIONS

◆ Salesforce Agentforce Specialist  
◆ Azure AI Fundamentals  
◆ Oracle Cloud AI Foundations  
◆ Generative AI Development  

---

# 🏆 BEYOND CODE

⚽ J&K Under-15 Football Squad  
🧘 State-Level Yoga Representation  
◆ Discipline under pressure  
◆ Team collaboration  
◆ Competitive mindset  

---

<div align="center">

## Build systems. Solve complexity. Scale ideas.

</div>
