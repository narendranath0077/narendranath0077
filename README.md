<div align="center">

<img src="assets/banner.svg" alt="Narendranath Athota - AI Engineer. Agentic AI, RAG, LLM Evaluation." width="100%"/>

<br/>

<a href="https://linkedin.com/in/narendranath-athota-3499a5259"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:athotanarendranath@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/narendranath0077?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Browse-181717?style=flat-square&logo=github&logoColor=white" alt="Repositories"/></a>
<img src="https://img.shields.io/badge/Bengaluru-India-2dd4bf?style=flat-square" alt="Bengaluru, India"/>

<br/><br/>

**I build AI systems that are measured, evaluated, and built to recover from failure.**

</div>

<br/>

<table align="center">
  <tr>
    <td align="center" width="25%"><h2>40%</h2><sub>better retrieval quality<br/>than baseline<br/>(hybrid BM25 + FAISS + rerank)</sub></td>
    <td align="center" width="25%"><h2>40%</h2><sub>fewer manual review cycles<br/>(automated RAGAS evaluation,<br/>100+ enterprise documents)</sub></td>
    <td align="center" width="25%"><h2>~40%</h2><sub>token reduction in agent workflows<br/>(Tree-sitter structured<br/>code context)</sub></td>
    <td align="center" width="25%"><h2>5+</h2><sub>production use cases on one<br/>modular Agentic RAG<br/>platform</sub></td>
  </tr>
</table>

<br/>

## About

I'm an **Associate Software Engineer at CGI**, working on AI engineering: enterprise RAG, agentic workflows, and the unglamorous part most demos skip, which is knowing whether the system is actually right.

- How do you know your retriever is finding the *right* chunks and not just similar ones?
- How do you catch a hallucination before a user does?
- How do you turn a hardcoded LLM chain into something that reasons through input it has never seen?

That is my day job, my side projects, and most of what I think about.

<br/>

## Now

| | |
|---|---|
| 🔨 **Building** | [Vantage](https://github.com/narendranath0077/dataviz), an agentic analytics platform with governed, grounded answers |
| 🧪 **Working on** | Code-analysis pipelines (Tree-sitter, UIRs) and legacy modernisation tooling at CGI |
| 🔎 **Exploring** | MCP and what it changes for tool-calling architectures; agent reliability under adversarial input |
| 💬 **Ask me about** | RAG evaluation, hybrid retrieval, ReAct agents, LangGraph, FastAPI backends |

<br/>

## Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 Vantage</h3>
      <sub><b>Agentic AI data analytics platform</b> · Sep 2026</sub>
      <p>A LangGraph agent that builds dashboards, answers natural-language questions about your data, and generates insights. Runs on Ollama, Anthropic, or OpenAI models.</p>
      <p>Built for trust: semantic validation, whitelisted parameterised queries, response grounding and data provenance. <b>200+ automated tests</b> with GitHub Actions CI.</p>
      <code>LangGraph</code> <code>FastAPI</code> <code>DuckDB</code> <code>Pydantic</code> <code>React</code><br/><br/>
      <a href="https://github.com/narendranath0077/dataviz"><b>View repository →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🔍 Agentic RAG System</h3>
      <sub><b>Universal RAG chatbot</b> · Jan 2026</sub>
      <p>A multi-step LangGraph pipeline: query rewriting, intent understanding, scope validation, dynamic retrieval planning, content evaluation, and retries. Ingests zips, directories, and mixed formats (PDF, DOCX, CSV, JSON, XLSX).</p>
      <p>Post-retrieval uses Reciprocal Rank Fusion, deduplication, and reranking, with graceful fallback when models can't load offline.</p>
      <code>LangGraph</code> <code>FAISS</code> <code>BM25</code> <code>RAGAS</code> <code>FastAPI</code><br/><br/>
      <a href="https://github.com/narendranath0077/Universal-RAG-based-chatbot"><b>View repository →</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 Multi-Agent Diet Planner</h3>
      <sub><b>Coordinated agents with a feedback loop</b></sub>
      <p>Four specialised agents (constraint analyser, meal generator, validator, feedback handler) coordinate over Pydantic-validated JSON to produce plans from BMI, BMR, and TDEE.</p>
      <p>A SQLite feedback loop tracks adherence and adapts future plans. Every output is schema-checked against macros, allergens, and cost.</p>
      <code>LangChain</code> <code>Pydantic</code> <code>SQLite</code><br/><br/>
      <a href="https://github.com/narendranath0077/Multi-Agent-AI-Diet-Planning-System-"><b>View repository →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>🛰️ Oil Spill Detection</h3>
      <sub><b>Sentinel-1 SAR + AIS vessel data</b> · B.Tech final-year project</sub>
      <p>Semantic segmentation of oil spills from satellite radar imagery fused with vessel-tracking data, built to be real-time capable.</p>
      <p>Compared UNet, DeepLabV3+, and a hybrid model, which reached <b>&gt;92% IoU</b>.</p>
      <code>PyTorch</code> <code>UNet</code> <code>DeepLabV3+</code> <code>SAR</code><br/><br/>
      <a href="https://github.com/narendranath0077/Real-Time-Oil-Spill-Detection-Using-AIS-Satellite-Imagery"><b>View repository →</b></a>
    </td>
  </tr>
</table>

<br/>

### How the Agentic RAG pipeline thinks

<img src="assets/agentic-rag-pipeline.svg" alt="Agentic RAG pipeline: rewrite and intent, scope check, hybrid retrieval, fusion and rerank, evaluate, grounded answer, with a retry loop" width="100%"/>

<br/>

## Experience

**Associate Software Engineer** · CGI, Bengaluru · *Sep 2026 – Present*

- Build code-analysis pipelines using Tree-sitter parsing to generate UIRs and structured code context for agent tools, cutting token consumption by **~40%**.
- Improve a Legacy Modernisation solution by refining application workflows, fixing functional issues, and raising execution reliability.
- Analyse product requirements, find gaps across pages, APIs, and workflows, and drive implementation to support customer leads.
- Lead testing and deployment validation in customer environments: defect coordination, functional testing, client demos, and release-readiness calls.

**Apprentice AI Developer** · CGI, Bengaluru · *Sep 2025 – Aug 2026*

- Built a modular enterprise **Agentic RAG platform** (LangGraph, ChromaDB, tool-calling agents) with ReAct workflows, self-evaluation, and retry across **5+ production use cases**.
- Designed **hybrid retrieval** (BM25 + FAISS + reranking) for a **40% retrieval-quality gain** over baseline.
- Automated RAG evaluation with LangChain and RAGAS, scoring answer relevancy, faithfulness, and retrieval quality across **100+ enterprise documents**, cutting manual review by **40%**.

<br/>

## Toolbox

| | |
|---|---|
| **LLM & agents** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-0f766e?style=flat-square) |
| **Retrieval & eval** | ![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white) ![BM25](https://img.shields.io/badge/BM25-334155?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-ff6446?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white) ![RAGAS](https://img.shields.io/badge/RAGAS-0f766e?style=flat-square) |
| **Backend & data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |
| **ML / DL** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **Cloud & DevOps** | ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![GCP](https://img.shields.io/badge/GCP%20Vertex%20AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| **AI-assisted dev** | ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white) ![Codex](https://img.shields.io/badge/OpenAI%20Codex-412991?style=flat-square&logo=openai&logoColor=white) ![Copilot](https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white) |

<br/>

## Credentials

| | | |
|---|---|---|
| 🎓 | **B.Tech, Computer Science (Artificial Intelligence)** | KKR & KSR Institute of Technology and Sciences · 2025 |
| 🏅 | **Oracle Cloud Infrastructure 2025 Generative AI Professional** (1Z0-1127-25) | Oracle University · Oct 2025 |
| 🏅 | **Claude Code in Action** | Anthropic · Feb 2026 |

<br/>

## Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=narendranath0077&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=narendranath0077&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages"/>

</div>

<br/>

<div align="center">

### Working on LLM systems, RAG, or evaluation?

**Let's talk.** I like hard problems where "it works in the demo" is not the bar.

<a href="https://linkedin.com/in/narendranath-athota-3499a5259"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/></a>
<a href="mailto:athotanarendranath@gmail.com"><img src="https://img.shields.io/badge/Email%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me"/></a>

<sub>Where it started: <a href="https://github.com/narendranath0077/NEXUS---Voice-Based-AI-Assistant">NEXUS</a>, a Python voice assistant I built just to see if I could make something that talks back.</sub>

</div>
