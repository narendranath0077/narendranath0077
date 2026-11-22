<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0f3d3a,100:0d1117&height=230&section=header&text=Narendranath%20Athota&fontSize=54&fontColor=f0f6fc&fontAlignY=38&animation=fadeIn&desc=AI%20Engineer%20%C2%B7%20Agentic%20AI%20%C2%B7%20RAG%20%C2%B7%20LLM%20Evaluation&descSize=18&descAlignY=60&descColor=2dd4bf" alt="Narendranath Athota, AI Engineer" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3500&pause=1200&color=2DD4BF&center=true&vCenter=true&width=760&height=36&lines=Agentic+RAG+that+retries+instead+of+guessing;Hybrid+retrieval%3A+BM25+%2B+FAISS+%2B+rerank;Quality+measured+with+RAGAS%2C+not+assumed;FastAPI+backends+with+200%2B+tests;Tree-sitter+context%2C+~40%25+fewer+tokens" alt="Agentic RAG that retries instead of guessing. Hybrid retrieval. Quality measured with RAGAS. FastAPI backends with 200+ tests."/>

<br/>

<a href="https://linkedin.com/in/narendranath-athota-3499a5259"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:athotanarendranath@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/narendranath0077?tab=repositories"><img src="https://img.shields.io/badge/Repositories-21262d?style=flat-square&logo=github&logoColor=white" alt="Repositories"/></a>

</div>

<br/>

```text
narendranath@cgi:~$ cat now.txt

role        Associate Software Engineer, CGI (Bengaluru)
focus       agentic AI, enterprise RAG, evaluation, Python backends
building    Vantage: an agentic analytics platform with grounded answers
reading     MCP, and how agents behave under adversarial input
reach me    athotanarendranath@gmail.com
```

<br/>

<div align="center">

<img src="https://img.shields.io/badge/retrieval_quality-40%25_over_baseline-0f766e?style=for-the-badge&labelColor=0d1117" alt="40% retrieval quality improvement over baseline"/>
<img src="https://img.shields.io/badge/manual_review_cycles-40%25_fewer-0f766e?style=for-the-badge&labelColor=0d1117" alt="40% fewer manual review cycles"/>
<br/>
<img src="https://img.shields.io/badge/agent_token_use-~40%25_lower-0f766e?style=for-the-badge&labelColor=0d1117" alt="About 40% lower token consumption"/>
<img src="https://img.shields.io/badge/production_use_cases-5%2B-0f766e?style=for-the-badge&labelColor=0d1117" alt="5 plus production use cases"/>
<img src="https://img.shields.io/badge/automated_tests-200%2B-0f766e?style=for-the-badge&labelColor=0d1117" alt="200 plus automated tests"/>

</div>

<br/>

## How I work

- **Measure before claiming.** Retrieval and answer quality are scored (faithfulness, answer relevancy, context precision with RAGAS) against baselines, so an improvement is a number and not an impression.
- **Treat failure as a normal path.** Agents evaluate their own context and retry or re-plan retrieval, rather than answering confidently on weak evidence.
- **Validate at every boundary.** Pydantic schemas, whitelisted parameterised queries, and grounded responses with provenance, so the model is never trusted with more than it should be.

<br/>

## Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Vantage</h3>
      <sub>Agentic data analytics platform &nbsp;·&nbsp; Sep 2026</sub>
      <p>A LangGraph agent with tool calling that builds dashboards, answers natural-language questions about data, and generates insights. Runs on Ollama, Anthropic, or OpenAI models.</p>
      <p>The FastAPI backend is governed: semantic validation, whitelisted parameterised query execution, response grounding, and data provenance. Backed by 200+ automated tests and GitHub Actions CI.</p>
      <code>LangGraph</code> <code>FastAPI</code> <code>DuckDB</code> <code>Pydantic</code> <code>React</code><br/><br/>
      <a href="https://github.com/narendranath0077/dataviz"><b>Repository →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>Agentic RAG System</h3>
      <sub>Universal RAG chatbot &nbsp;·&nbsp; Jan 2026</sub>
      <p>A multi-step LangGraph pipeline: query rewriting, intent understanding, scope validation, dynamic retrieval planning, content evaluation, and retry. Ingests zips, directories, and mixed formats (PDF, DOCX, CSV, JSON, XLSX).</p>
      <p>Post-retrieval uses Reciprocal Rank Fusion, deduplication, and reranking, with a fallback when models cannot load offline.</p>
      <code>LangGraph</code> <code>FAISS</code> <code>BM25</code> <code>RAGAS</code> <code>FastAPI</code><br/><br/>
      <a href="https://github.com/narendranath0077/Universal-RAG-based-chatbot"><b>Repository →</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Multi-Agent Diet Planner</h3>
      <sub>Four coordinating agents with a feedback loop</sub>
      <p>A constraint analyser, meal generator, validator, and feedback handler exchange Pydantic-validated JSON to build plans from BMI, BMR, and TDEE. A SQLite loop tracks adherence and adapts later plans, and every output is schema-checked against macros, allergens, and cost.</p>
      <code>LangChain</code> <code>Pydantic</code> <code>SQLite</code><br/><br/>
      <a href="https://github.com/narendranath0077/Multi-Agent-AI-Diet-Planning-System-"><b>Repository →</b></a>
    </td>
    <td width="50%" valign="top">
      <h3>Oil Spill Detection</h3>
      <sub>Sentinel-1 SAR + AIS vessel data &nbsp;·&nbsp; B.Tech final-year project</sub>
      <p>Semantic segmentation of oil spills from satellite radar imagery fused with vessel-tracking data, designed to be real-time capable. UNet, DeepLabV3+, and a hybrid model were compared; the hybrid reached over 92% IoU.</p>
      <code>PyTorch</code> <code>UNet</code> <code>DeepLabV3+</code> <code>SAR</code><br/><br/>
      <a href="https://github.com/narendranath0077/Real-Time-Oil-Spill-Detection-Using-AIS-Satellite-Imagery"><b>Repository →</b></a>
    </td>
  </tr>
</table>

<br/>

### Agentic RAG: control flow

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#0d1117','primaryColor':'#111c30','primaryBorderColor':'#334155','primaryTextColor':'#e2e8f0','lineColor':'#64748b','secondaryColor':'#0f2a2a','tertiaryColor':'#0d1117','fontFamily':'ui-monospace, SFMono-Regular, Menlo, monospace','fontSize':'14px'}}}%%
flowchart LR
    Q([User query]) --> R[Rewrite query<br/>detect intent]
    R --> S{In scope?}
    S -- no --> X([Out of scope])
    S -- yes --> P[Plan retrieval]
    P --> H[Hybrid retrieve<br/>BM25 + FAISS]
    H --> F[RRF, dedup,<br/>rerank]
    F --> E{Context<br/>sufficient?}
    E -- no, retry --> P
    E -- yes --> A([Grounded answer<br/>with sources])

    classDef core fill:#0f2a2a,stroke:#2dd4bf,color:#99f6e4
    classDef gate fill:#2a2210,stroke:#fbbf24,color:#fde68a
    class H,F core
    class S,E gate
```

<br/>

## Experience

**Associate Software Engineer** &nbsp;·&nbsp; CGI, Bengaluru &nbsp;·&nbsp; *Sep 2026 – Present*

- Build code-analysis pipelines that use Tree-sitter parsing to generate UIRs and give agent tools structured code context, cutting token consumption by about 40%.
- Improve a Legacy Modernisation solution by refining application workflows, fixing functional issues, and raising execution reliability.
- Analyse product requirements, find gaps across pages, APIs, and workflows, and drive their implementation to support customer leads.
- Lead testing and deployment validation in customer environments: defect coordination, functional testing, client demonstrations, and release-readiness recommendations.

**Apprentice AI Developer** &nbsp;·&nbsp; CGI, Bengaluru &nbsp;·&nbsp; *Sep 2025 – Aug 2026*

- Built a modular enterprise Agentic RAG platform (LangGraph, ChromaDB, tool-calling agents) with ReAct workflows, self-evaluation, and retry across 5+ production use cases.
- Designed hybrid retrieval pipelines combining BM25, FAISS, and reranking, improving retrieval quality by 40% over baseline.
- Automated RAG evaluation with LangChain and RAGAS, scoring answer relevancy, faithfulness, and retrieval quality across 100+ enterprise documents, which cut manual review cycles by 40%.

<br/>

## Toolbox

<table>
  <tr>
    <td width="150"><b>Core</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,fastapi,flask,postgres,sqlite,pandas,numpy,pytorch,tensorflow&theme=dark" alt="Python, FastAPI, Flask, PostgreSQL, SQLite, Pandas, NumPy, PyTorch, TensorFlow"/></td>
  </tr>
  <tr>
    <td><b>Platform</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,azure,gcp,githubactions,git,react&theme=dark" alt="Docker, Azure, GCP, GitHub Actions, Git, React"/></td>
  </tr>
  <tr>
    <td><b>LLM and agents</b></td>
    <td>
      <img src="https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square" alt="LangGraph"/>
      <img src="https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
      <img src="https://img.shields.io/badge/LangSmith-1c3c3c?style=flat-square" alt="LangSmith"/>
      <img src="https://img.shields.io/badge/Hugging_Face-ffd21e?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama"/>
      <img src="https://img.shields.io/badge/MCP-0f766e?style=flat-square" alt="Model Context Protocol"/>
    </td>
  </tr>
  <tr>
    <td><b>Retrieval and eval</b></td>
    <td>
      <img src="https://img.shields.io/badge/FAISS-0467df?style=flat-square" alt="FAISS"/>
      <img src="https://img.shields.io/badge/BM25-334155?style=flat-square" alt="BM25"/>
      <img src="https://img.shields.io/badge/ChromaDB-ff6446?style=flat-square" alt="ChromaDB"/>
      <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"/>
      <img src="https://img.shields.io/badge/RAGAS-0f766e?style=flat-square" alt="RAGAS"/>
      <img src="https://img.shields.io/badge/DuckDB-fff000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB"/>
      <img src="https://img.shields.io/badge/Pydantic-e92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic"/>
    </td>
  </tr>
  <tr>
    <td><b>AI-assisted dev</b></td>
    <td>
      <img src="https://img.shields.io/badge/Claude_Code-d97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code"/>
      <img src="https://img.shields.io/badge/OpenAI_Codex-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Codex"/>
      <img src="https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white" alt="GitHub Copilot"/>
    </td>
  </tr>
</table>

<br/>

## Credentials

| | |
|---|---|
| **B.Tech, Computer Science (Artificial Intelligence)** | KKR & KSR Institute of Technology and Sciences, Guntur · May 2025 |
| **Oracle Cloud Infrastructure 2025 Generative AI Professional** (1Z0-1127-25) | Oracle University · Oct 2025 |
| **Claude Code in Action** | Anthropic · Feb 2026 |

<br/>

## Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=narendranath0077&bg_color=0d1117&color=8b949e&line=2dd4bf&point=f0f6fc&area=true&area_color=2dd4bf&hide_border=true&title_color=2dd4bf" alt="Contribution activity graph" width="100%"/>

<img height="165" src="https://github-readme-stats.vercel.app/api?username=narendranath0077&show_icons=true&count_private=true&hide_border=false&border_color=30363d&bg_color=0d1117&title_color=2dd4bf&icon_color=2dd4bf&text_color=c9d1d9&rank_icon=github" alt="GitHub stats"/>
<img height="165" src="https://streak-stats.demolab.com?user=narendranath0077&hide_border=false&border=30363d&background=0d1117&stroke=30363d&ring=2dd4bf&fire=fbbf24&currStreakNum=f0f6fc&currStreakLabel=2dd4bf&sideNums=f0f6fc&sideLabels=8b949e&dates=8b949e" alt="GitHub streak"/>

</div>

<br/>

<div align="center">

**Working on LLM systems, RAG, or evaluation? I'd like to hear about it.**

<a href="https://linkedin.com/in/narendranath-athota-3499a5259"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/></a>
<a href="mailto:athotanarendranath@gmail.com"><img src="https://img.shields.io/badge/Email_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me"/></a>

<sub>Where it started: <a href="https://github.com/narendranath0077/NEXUS---Voice-Based-AI-Assistant">NEXUS</a>, a Python voice assistant built to see if I could make something that talks back.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0f3d3a,100:0d1117&height=110&section=footer" alt="" width="100%"/>

</div>
