<!-- Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=140&section=header&text=John%20Carl%20Santos&fontSize=40&fontColor=ffffff&fontAlignY=55&desc=AI%20Engineer%20%C2%B7%20Full%20Stack%20%C2%B7%20Philippines%20%F0%9F%87%B5%F0%9F%87%AD&descAlignY=75&descSize=14&descColor=8b949e" width="100%"/>
</div>

<br/>

<!-- Intro -->
<p align="left">
  <code>// JohnCarl-30.github.io</code>
</p>

### Hey, I'm CJ 👋


<p align="left">
  <img src="https://komarev.com/ghpvc/?username=JohnCarl-30&label=Profile%20views&color=0e75b6&style=flat" />
</p>

3rd-year CS student at PCU Bulacan. If you're thinking why I have so many tech stack it's just because I'm curios all want to make projects from that.
My first programming language is Java because of school req but I switch to Python because I'm interested in computer vision and machine learning. I love to build web even I'm suck at designing but I love to make a web or an app that helps people!!! 

```python
status = {
    "location":    "Philippines 🇵🇭",
    "certs":       ["Oracle GenAI", "AWS"],
    "building":    ["AI agents", "full stack"],
}
```

<br/>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📚 StudyAI</h3>
      <p>RAG-based study platform with flashcard generation, MMR reranking, and streaming responses. Full production deployment on DigitalOcean with CI/CD via GitHub Actions.</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
      </p>
      <sub>RAG · MMR reranking · streaming responses · CI/CD on DigitalOcean</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🏛️ CiviReport</h3>
      <p>Barangay complaint management system with JWT auth, real-time notifications, and a full REST API backend.</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
      </p>
      <sub>JWT auth · real-time notifications · REST API backend</sub>
    </td>
  </tr>
</table>

<br/>

---

## 🔧 Systems & Infrastructure

A set of four focused on systems depth — durable execution, search internals,
browser automation, infrastructure-as-code. Each one ends in a **measured
result** rather than "it runs", and each is verified locally: no cloud
deployment, and every README says so up front.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔁 <a href="https://github.com/JohnCarl-30/directory-pipeline">directory-pipeline</a></h3>
      <p>Agentic crawl → extract → enrich → resolve → OpenSearch, orchestrated by Temporal. Zero-downtime reindex behind an alias, measured under live read load: <b>101 concurrent reads through the swap, 0 failures</b>. Ships a search console at <code>/ui</code> — ranked results, facet filters, and the BM25 scoring tree behind every hit.</p>
      <p>
        <img src="https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white"/>
        <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
      </p>
      <sub>144 tests · entity resolution · search console with score explain</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🕵️ <a href="https://github.com/JohnCarl-30/browser-harvest">browser-harvest</a></h3>
      <p>Browser automation with fingerprint hardening, rotating proxies and a compliance gate — proven against a hostile site bundled in the repo that actively detects bots. <b>275 detection points eliminated, 275 → 0</b>.</p>
      <p>
        <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
      <sub>84 tests · honeypot avoidance · robots.txt & PII redaction</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔍 <a href="https://github.com/JohnCarl-30/hybrid-search">hybrid-search</a></h3>
      <p>BM25 + vector retrieval fused with reciprocal rank fusion, reranked, answered with verified citations — <b>measured against a labeled query set</b> rather than argued about. Found that equal-weight RRF loses to semantic alone, and fixed it.</p>
      <p>
        <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white"/>
        <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/>
        <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white"/>
      </p>
      <sub>101 tests · NDCG / MRR / Recall@k · HNSW kNN · eval harness</sub>
    </td>
    <td width="50%" valign="top">
      <h3>☁️ <a href="https://github.com/JohnCarl-30/azure-durable-pipeline">azure-durable-pipeline</a></h3>
      <p>The same pipeline on <b>Azure Durable Functions</b> instead of Temporal, with Terraform IaC and identity-based access — no connection strings anywhere. The README compares the two durable-execution engines honestly.</p>
      <p>
        <img src="https://img.shields.io/badge/Azure_Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white"/>
        <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      </p>
      <sub>61 tests · managed identity + Key Vault · verified on the real host</sub>
    </td>
  </tr>
</table>

<sub>💡 The most useful thing in these is probably the <a href="https://github.com/JohnCarl-30/azure-durable-pipeline#durable-functions-vs-temporal-having-written-both">Durable Functions vs Temporal comparison</a> — same workload built twice, so the write-up is from having actually done it.</sub>

<br/>

---

## 🛠️ Tech Stack

**AI / ML**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Data & Infra**

![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

<br/>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=JohnCarl-30&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" width="540" />
</div>

<br/>

---

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=120&section=footer" width="100%"/>
