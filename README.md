<div align="center">

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Narendranath+Athota+%F0%9F%91%8B;AI+%2F+GenAI+Developer+%40+CGI;I+build+things+that+think.)](https://git.io/typing-svg)

</div>

---

### Who I Am

I'm an **AI / GenAI Developer at CGI, Bengaluru** — I work on the messy, interesting parts of LLM systems: evaluation pipelines that actually measure something, retrieval that doesn't hallucinate half the corpus, and agentic workflows that don't fall apart on edge cases.

Before this, I was a CS (AI) student who got deep into deep learning, then got obsessed with why RAG systems fail, then started building tools to fix that. That thread is basically my whole career so far.

---

### What I'm Working On

At **CGI**, I'm embedded in an enterprise AI team building internal LLM tooling. Day-to-day, that means:

- Automating LLM output evaluation with **LangChain + RAGAS** — cut manual review cycles by ~40%
- Replacing dense-only vector search with **hybrid FAISS + BM25** pipelines (context precision up ~40%)
- Migrating static pipelines into **ReAct-style agentic workflows** with tool-calling
- Generating synthetic **Q&A datasets** using LLaMA 3 via Ollama to cover edge cases nobody thought to test for

---

### Projects

**[Universal RAG-Based Chatbot](https://github.com/narendranath0077/Universal-RAG-based-chatbot)**
A full agentic QA system — not just "ingest + retrieve." It handles multi-format ingestion (PDF, DOCX, CSV, ZIP, directories), does chunked embedding into FAISS, then reranks with BM25 + CrossEncoder before answering. FastAPI backend, Streamlit frontend, fully local via Ollama. Built because most RAG demos skip the hard parts.
`Python` `LangChain` `LangGraph` `FAISS` `BM25` `FastAPI` `Streamlit` `Ollama`

---

**[Multi-Agent Diet Planning System](https://github.com/narendranath0077)**
Four specialised agents — constraint analyser, meal generator, validator, feedback handler — that coordinate via Pydantic-validated JSON to produce personalised nutrition plans from real health metrics (BMI, BMR, TDEE). SQLite-backed feedback loop adapts recommendations based on user history. Every output is schema-validated against macros, allergens, and cost constraints.
`Python` `LangChain` `SQLite` `Pydantic`

---

**[Real-Time Oil Spill Detection](https://github.com/narendranath0077/Real-Time-Oil-Spill-Detection-Using-AIS-Satellite-Imagery)**
Semantic segmentation on **Sentinel-1 SAR imagery + AIS vessel data** using UNet, DeepLabV3+, and a hybrid model that hit **>92% IoU**. Real-time capable. Built during my final year — this is what got me into production-scale ML pipelines.
`PyTorch` `UNet` `DeepLabV3+` `SAR Imagery` `AIS Data`

---

### Stack

```
LLMs & Orchestration   LangChain · LangGraph · LlamaIndex · LangSmith
Retrieval              FAISS · BM25 · ChromaDB · Pinecone · HuggingFace Embeddings
Evaluation             RAGAS · Pydantic · Synthetic Data Generation
APIs & Serving         FastAPI (async) · Streamlit · REST APIs
Models                 OpenAI API · Gemini API · Ollama (LLaMA 3) · HuggingFace
ML / DL                PyTorch · TensorFlow · CNNs · Transformers
Cloud & DevOps         AWS (EC2, S3) · GCP / Vertex AI · Docker · GitHub Actions
```

---

### Certifications

- **Oracle Cloud Infrastructure 2025 Generative AI Professional** — Oracle University (1Z0-1127-25)
- **Claude Code in Action** — Anthropic (Feb 2026)

---

### GitHub Stats

<div align="center">

![Narendranath's GitHub Stats](https://github-readme-stats.vercel.app/api?username=narendranath0077&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=narendranath0077&layout=compact&theme=tokyonight&hide_border=true)

[![GitHub Streak](https://streak-stats.demolab.com?user=narendranath0077&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

### Reach Me

**Email:** athotanarendranath@gmail.com  
**LinkedIn:** [narendranath-athota-3499a5259](https://linkedin.com/in/narendranath-athota-3499a5259)  
**Location:** Bengaluru, India

---

<div align="center">
<sub>I'm most reachable on LinkedIn. If you're working on something with LLMs, RAG, or agentic systems — genuinely happy to talk.</sub>
</div>
