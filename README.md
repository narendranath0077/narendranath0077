<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=Narendranath+Athota;I+build+AI+systems+that+actually+work.;RAG+%7C+Agentic+AI+%7C+LLM+Evaluation)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/narendranath-athota-3499a5259)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:athotanarendranath@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/narendranath0077)

</div>

---

## A Short Version About Me

I'm an **AI / GenAI Developer at CGI** (Bengaluru). I work on the parts of LLM systems that most demos skip — how do you know if your RAG pipeline is actually retrieving the right things? How do you catch hallucinations before they hit production? How do you turn a fragile, hardcoded LLM chain into something that reasons through novel inputs?

That's my day job. And also my side projects. And also kind of what I think about too much.

---

## What I've shipped

### @ CGI (Sep 2025 → Present)

**Problem:** The team was spending hours manually reviewing LLM outputs across 100+ internal enterprise documents. No scale, no consistency.

**What I built:** An automated evaluation pipeline using LangChain + RAGAS that scores responses on faithfulness, answer relevance, and context precision. Result → ~40% reduction in manual review cycles, measured by ticket count before/after.

---

**Problem:** Dense-only vector search was retrieving semantically similar but contextually off-target chunks for domain-specific queries.

**What I built:** Hybrid FAISS + BM25 retrieval to balance semantic similarity with keyword precision. RAGAS context-precision went up ~40% against the original baseline.

---

**Problem:** Static LangChain pipelines broke on edge cases because every flow was hardcoded.

**What I built:** Migrated them to ReAct-style agentic workflows with dynamic tool-calling — the system now reasons through what to do rather than following a script.

---

**On the side:** Generated 1,000+ synthetic Q&A pairs using LLaMA 3 via Ollama to build evaluation datasets that stress-test the pipeline on edge cases, not just the queries everyone already handles.

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔍 Universal RAG Chatbot
**The premise:** Most RAG demos ingest 5 PDFs and call it done. This one handles zip archives, mixed file types (PDF, DOCX, CSV, JSON, XLSX), and full directories — then actually reranks before answering.

**What's different:** BM25 + CrossEncoder reranking layered on FAISS dense retrieval. Falls back gracefully if the CrossEncoder can't load offline. Async FastAPI backend, Streamlit UI with a glass-smoke aesthetic.

`LangChain` `LangGraph` `FAISS` `BM25` `FastAPI` `Ollama` `Streamlit`

[→ View Repo](https://github.com/narendranath0077/Universal-RAG-based-chatbot)

</td>
<td width="50%" valign="top">

### 🤖 Multi-Agent Diet Planner
**The premise:** Four specialised agents — constraint analyser, meal generator, validator, feedback handler — coordinate via Pydantic-validated JSON to build personalised nutrition plans from real health metrics (BMI, BMR, TDEE).

**What's different:** It doesn't just generate a plan once. A SQLite feedback loop tracks adherence and adapts future recommendations. Every output is schema-validated against macros, allergens, and cost constraints. Agentic in the actual sense.

`LangChain` `SQLite` `Pydantic` `Python`

[→ View Repo](https://github.com/narendranath0077)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛰️ Real-Time Oil Spill Detection
**The premise:** Detect oil spills from Sentinel-1 SAR satellite imagery fused with AIS vessel tracking data — in real time.

**What's different:** Not just one model — UNet, DeepLabV3+, and a hybrid model that hit **>92% IoU**. Built in my final year of B.Tech as a genuine attempt at a real-world environmental monitoring problem.

`PyTorch` `UNet` `DeepLabV3+` `SAR Imagery` `AIS Data`

[→ View Repo](https://github.com/narendranath0077/Real-Time-Oil-Spill-Detection-Using-AIS-Satellite-Imagery)

</td>
<td width="50%" valign="top">

### 🎙️ Python Voice Assistant *(where it all started)*
**The premise:** Voice-controlled assistant using SpeechRecognition + Pyttsx3 — open websites, tell jokes, give the time.

**Why it's here:** Before FAISS and RAGAS, there was this. Built just to see if I could make something that responds to me. The instinct to build things that interact intelligently with people never left — it just leveled up.

`Python` `SpeechRecognition` `Pyttsx3`

[→ View Repo](https://github.com/narendranath0077/PyCharmMiscProject)

</td>
</tr>
</table>

---

## Tech I actually use

```python
core_stack = {
    "LLM Orchestration" : ["LangChain", "LangGraph", "LlamaIndex", "LangSmith"],
    "Retrieval"         : ["FAISS", "BM25", "ChromaDB", "Pinecone", "CrossEncoder"],
    "Evaluation"        : ["RAGAS", "Pydantic", "Synthetic Data Generation"],
    "Model APIs"        : ["OpenAI", "Gemini", "Ollama / LLaMA 3", "HuggingFace"],
    "Serving"           : ["FastAPI (async)", "Streamlit", "REST APIs"],
    "ML / DL"           : ["PyTorch", "TensorFlow", "Transformers", "CNNs"],
    "Cloud & Infra"     : ["AWS EC2/S3", "GCP / Vertex AI", "Docker", "GitHub Actions"],
}
```

---

## Certifications

| Certification | Issuer | Year |
|---|---|---|
| Oracle Cloud Infrastructure 2025 Generative AI Professional (1Z0-1127-25) | Oracle University | 2025 |
| Claude Code in Action | Anthropic | Feb 2026 |

---

## GitHub Stats

<div align="center">

![Narendranath's GitHub Stats](https://github-readme-stats.vercel.app/api?username=narendranath0077&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=narendranath0077&layout=compact&theme=tokyonight&hide_border=true&langs_count=6)

</div>

---

## Currently thinking about

- Why most production RAG systems are still fundamentally brittle — and what it actually takes to fix that
- The gap between "agentic" as a marketing word and agentic systems that work under adversarial inputs
- MCP (Model Context Protocol) and what it means for the future of tool-calling architectures

---

<div align="center">

**If you're working on LLM systems, RAG, or evaluation — let's talk.**

[![Connect on LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/narendranath-athota-3499a5259)

<sub>Bengaluru, India · Open to interesting problems · athotanarendranath@gmail.com</sub>

</div>
