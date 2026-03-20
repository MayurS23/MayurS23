<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Mayur+%F0%9F%91%8B;Software+Developer;AI+%2F+ML+Engineer;Systems+Builder" alt="Typing SVG" />

<p>
  <b>Building production-grade systems — distributed, tested, and AI-powered.</b><br/>
  From search engines to intrusion detectors to C++/WASM visualizers.
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mayur--s)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mayuur203@gmail.com)
[![Portfolio](https://img.shields.io/badge/Live_Demo-00e5ff?style=for-the-badge&logo=githubpages&logoColor=black)](https://mayurs23.github.io/pathfinding-visualizer/)
[![Profile Views](https://komarev.com/ghpvc/?username=MayurS23&style=for-the-badge&color=6366f1&label=PROFILE+VIEWS)](https://github.com/MayurS23)

</div>

---

## 🧑‍💻 About Me

```python
mayur = {
    "location"   : "Mysuru, Karnataka 🇮🇳",
    "focus"      : ["Distributed Systems", "AI / ML", "Software Testing"],
    "languages"  : ["Python", "C++", "JavaScript", "TypeScript"],
    "currently"  : "Building things that scale, break gracefully, and ship with confidence",
    "tests"      : "My projects ship with 50–142 passing tests — always.",
    "ask_me"     : "RAG pipelines, BM25 ranking, WebAssembly, system design",
    "fun_fact"   : "I wrote a search engine & IDS from scratch — because why not?",
}
```

---

## 🚀 Projects

### 🤖 AI & Machine Learning

<table>
<tr>
<td width="50%" valign="top">

#### 🧠 [AI Codebase Intelligence](https://github.com/MayurS23/ai-codebase-intelligence)
> Talk to any GitHub repo like a senior engineer who's read every file

RAG + AST parsing + call graph analysis + **Claude AI** to answer natural language questions about any codebase with exact file & line references.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-6C3EB7?style=flat&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_AI-D97757?style=flat&logo=anthropic&logoColor=white)

- 🔗 Traces execution flows from any function entry point
- 🌐 Supports 12 languages: Python, JS, Go, Rust, C++, Java...
- ✅ **50 tests** across 8 modules — all passing

</td>
<td width="50%" valign="top">

#### 🛡️ [CyberFlux — AI Intrusion Detection](https://github.com/MayurS23/Cyberfluxmain)
> Hybrid ML+DL system that detects malicious network traffic in real-time

Ensemble of **LSTM, CNN, Autoencoder, Random Forest, XGBoost** + GAN-based synthetic data generation. React SOC dashboard with WebSocket alert streaming.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

- 🤖 6-model ensemble: weighted aggregation for fewer false positives
- 📡 Deployed live → [cyberflux-ids.emergent.host](https://cyberflux-ids.emergent.host)
- 📊 Trained on NSL-KDD benchmark dataset

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🗂️ [RAG AI System](https://github.com/MayurS23/rag-ai-system)
> Production-grade knowledge assistant — ingest any doc, get cited answers

Ingests PDFs, Markdown, code, and URLs → FAISS vector store → MMR reranking → cited answers via **Claude / GPT-4o / Ollama**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

- ⚡ SSE streaming, Redis caching, per-IP rate limiting
- 🔄 Swap LLM/vector store via 1 env var — zero code changes
- 📈 FAISS search: <1ms at 10k vectors, ~10ms at 1M vectors

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

---

### ⚙️ Distributed Systems

<table>
<tr>
<td width="50%" valign="top">

#### 🔍 [Distributed Search Engine](https://github.com/MayurS23/distributed-search-engine)
> Google-scale search engine built from scratch in Python

Async BFS crawler → sharded inverted index (4 Redis shards) → **BM25 ranking** (same as Elasticsearch) → FastAPI REST API.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

- 🔎 Positional index for exact phrase queries (`"inverted index"`)
- 🤖 `robots.txt` compliant async crawler
- ✅ **92 tests** (unit + integration) — all passing

</td>
<td width="50%" valign="top">

#### ⚡ [Distributed Rate Limiter](https://github.com/MayurS23/distributed-rate-limiter)
> Production-grade API rate limiting with atomic Redis guarantees

Token Bucket algorithm implemented with **atomic Lua scripting in Redis** — race-condition-free under any concurrency. Per-route, per-role limits. Horizontally scalable.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

- ⚛️ Atomic Lua scripts — zero race conditions at any concurrency
- 🔧 Per-route and per-role configurable limits
- 📦 Horizontal scalability via Redis cluster

</td>
</tr>
</table>

---

### 🖥️ Algorithms & Visualization

<table>
<tr>
<td width="50%" valign="top">

#### 🗺️ [PathOS — Pathfinding Visualizer](https://github.com/MayurS23/pathfinding-visualizer)
> BFS, DFS, Dijkstra & A* written in C++ and compiled to WebAssembly

Watch algorithms explore a grid in real-time directly in your browser — at near-native C++ speed via WASM. Zero-copy JS↔WASM memory bridge via `HEAP32` typed arrays.

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

- 🧮 A* visits ~50% fewer nodes than BFS while finding the same optimal path
- 🎮 Maze generator, compare mode, weighted nodes, 4 grid sizes
- 🚀 [**Live Demo →**](https://mayurs23.github.io/pathfinding-visualizer/)

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**Backend & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white)

**AI / ML**

![Claude AI](https://img.shields.io/badge/Claude_AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-6C3EB7?style=for-the-badge&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge&logoColor=white)

**Testing & Tools**

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MayurS23&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MayurS23&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="170"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MayurS23&theme=tokyonight&hide_border=true" />
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=MayurS23&theme=tokyonight&no-frame=true&row=1&column=7&margin-w=4" />
</div>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MayurS23&theme=tokyo-night&hide_border=true&area=true" />
</div>

---

<div align="center">
  <i>"First, solve the problem. Then, write the code."</i><br/>
  <sub>— John Johnson</sub>
</div>
