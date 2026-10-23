<!-- Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=140&section=header&text=John%20Carl%20Santos&fontSize=40&fontColor=ffffff&fontAlignY=55&desc=AI%20Engineer%20%C2%B7%20Full%20Stack%20%C2%B7%20Philippines%20%F0%9F%87%B5%F0%9F%87%AD&descAlignY=75&descSize=14&descColor=8b949e" width="100%"/>
</div>

<br/>

<!-- Intro -->
<p align="left">
  <code>// <a href="https://www.dyeyc.dev/">dyeyc.dev</a></code>
</p>

### Hey, I'm CJ 👋


<p align="left">
  <img src="https://komarev.com/ghpvc/?username=JohnCarl-30&label=Profile%20views&color=0e75b6&style=flat" />
</p>

AI engineer at SOFI AI Tech Solutions and 4th-year CS student at PCU Bulacan, class of 2027.

I build AI products end to end: agents, RAG and the evals that show they work. My rule is that a 200 is not proof. Every project below ends in a measured result, not "it runs".

```ts
const status = {
  location: "Philippines 🇵🇭",
  building: "relaydesk — AI support for small businesses",
  certs: ["Oracle GenAI", "AWS"],
  openTo: "AI engineer / forward deployed engineer roles, 2027",
};
```

<br/>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛎️ <a href="https://github.com/JohnCarl-30/relaydesk">relaydesk</a></h3>
      <p>AI customer support as a widget plus a staff inbox. It answers from the business's help center with citations, and when the help center has no answer it says so and opens a ticket. A co-pilot drafts the reply; a person sends it. One help center per business, self-serve setup, and an MCP server so agents can work the inbox.</p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white"/>
        <img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square"/>
        <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white"/>
      </p>
      <sub>retrieval hit@3 55/60 · ticket precision 1.00 · Langfuse experiment gate on every PR</sub>
    </td>
    <td width="50%" valign="top">
      <h3>✍️ <a href="https://github.com/JohnCarl-30/auto-learn">auto-learn</a></h3>
      <p>Fix your sentence, and learn the word that fixed it. An ESL writing tool where the better word is withheld server-side until you open its card: the replacement text does not exist on the client until the teaching does. Now with a speaking partner.</p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white"/>
      </p>
      <sub>pnpm monorepo · shared Zod contract · evals · Playwright e2e</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📉 <a href="https://github.com/JohnCarl-30/rag-eval-harness">rag-eval-harness</a></h3>
      <p>Your RAG got worse. Your tests stayed green. A regression gate for RAG pipelines: score a golden set, keep every run, and fail CI when retrieval or answers slip. A weaker retriever cut <b>context recall 0.880 → 0.740</b> and the gate exited 1.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/RAGAS-1C3C3C?style=flat-square"/>
        <img src="https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white"/>
      </p>
      <sub>on PyPI · keyless CI mode · baseline diff view</sub>
    </td>
    <td width="50%" valign="top">
      <h3>✅ <a href="https://github.com/JohnCarl-30/closer">closer</a></h3>
      <p>A post-ship agent. Paste a merged PR: it marks the Linear issue Done, emails whoever asked, then re-reads both apps. A 200 from Gmail is not enough; the message has to show up in sent mail. Ambiguous matches mean zero writes until a human picks.</p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/Linear-5E6AD2?style=flat-square&logo=linear&logoColor=white"/>
        <img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
      </p>
      <sub>hackathon build · verifier re-reads every write · claims checked in CI</sub>
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

**AI**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/AI_SDK-000000?style=flat-square&logo=vercel&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-1C3C3C?style=flat-square)

**Languages & Frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Data & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

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
