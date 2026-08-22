<div align="center">
  <img src="./assets/banner.png" alt="Aayush Dubey — builds systems that stay up" width="100%" />
</div>

<br />

<div align="center">

  `● SYSTEM ONLINE` &nbsp;·&nbsp; `svc: aayush-dubey.backend` &nbsp;·&nbsp; `net: NSUT · Delhi`

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3500&pause=900&color=4ADE80&center=true&vCenter=true&width=640&lines=builds+systems+that+stay+up.;FastAPI+%C2%B7+PostgreSQL+%C2%B7+Keycloak;multi-tenant+platforms+%C2%B7+OCR+%2F+RAG;open+to+SDE+%2F+internship+%C2%B7+2026" alt="typing tagline" />

  <br />

  [![portfolio](https://img.shields.io/badge/portfolio-aayush--portfolio--sandy.vercel.app-4ADE80?style=flat-square&labelColor=0A0B0D)](https://aayush-portfolio-sandy.vercel.app/)
  [![linkedin](https://img.shields.io/badge/linkedin-aayush--kumar--dubey-4ADE80?style=flat-square&labelColor=0A0B0D)](https://www.linkedin.com/in/aayush-kumar-dubey-917bb9285)
  <a href="mailto:aayushdubey.work@gmail.com"><img src="https://img.shields.io/badge/email-aayushdubey.work%40gmail.com-4ADE80?style=flat-square&labelColor=0A0B0D" alt="email aayushdubey.work@gmail.com" /></a>
  [![available](https://img.shields.io/badge/status-available%20·%202026-4ADE80?style=flat-square&labelColor=0A0B0D)](https://aayush-portfolio-sandy.vercel.app/)

</div>

---

Backend engineer working where **reliability is the feature** — FastAPI platforms, multi-tenant auth, OCR/RAG pipelines, and observable LLM workflows. I care about the unglamorous parts: tenancy boundaries, schema design, and traces that make 2 a.m. debugging survivable.

Currently shipping production backends at **Flywheel** — a multi-tenant document ingestion platform (OCR, translate, review, index) with Keycloak auth, Marqo search, and self-hosted models on H100s.

```
role      Software Engineering Intern · Flywheel
study     B.Tech ICE · NSUT Delhi · 2023–present
focus     APIs · multi-tenancy · OCR / RAG · eval pipelines
looking   SDE / internship · 2026 · backend, platform, full-stack
```

## now

- Shipping **20+ merged PRs** into a production multi-tenant document platform (FastAPI, Temporal, MinIO, Marqo, React)
- Owning **Keycloak JWT + RBAC** so mutating endpoints stay tenant-scoped — fail-closed, not decorative
- Designing **document lifecycle APIs** (include / soft-delete / restore / chunk delete) so vector index and relational store never drift
- Replacing cloud OCR/translation with **self-hosted Chandra + Gemma on vLLM (H100)** — OCR accuracy **77% → 90%**

## production

Shipped into Flywheel's multi-tenant ingestion stack — auth that actually gates mutations, vector-store layering behind a single protocol, domain tagging with a Gemma auto-tagger, and a resumable OCR benchmarking harness used to pick production engines.

| signal | value |
| :--- | :--- |
| PRs merged to production | **20+** |
| OCR accuracy | **77% → 90%** after model benchmarking |
| users on systems managed | **80K+** |
| chunks indexed for search | **15K+** |
| Marqo call sites removed | **11** (152 lines of duplicated logic) |
| auth / tenancy tests | **15** verifying scoped mutations |

## selected systems

| | | |
| :--- | :--- | :--- |
| **[Airbnb Clone](https://github.com/nexus69420/Airbnb-clone)** | End-to-end booking platform — listings, filters, bookings, reviews, wishlists, host management across 9 domain entities. Next.js 15 + FastAPI, JWT auth, Alembic migrations. [Live demo](https://airbnb-clone-sand-five.vercel.app). | `TypeScript` `Next.js` `FastAPI` |
| **[KAI — RAG Workspace](https://github.com/nexus69420/kai-ai-rag)** | Full-stack RAG desk: PDF upload, hybrid retrieval (dense + keyword + RRF) with Gemini reranking, streaming answers with page-level citations. [Live demo](https://kai-ai-rag.vercel.app). | `TypeScript` `Gemini` `Postgres` `Qdrant` |
| **[OCR Benchmark](https://github.com/nexus69420/ocr-benchmark-v2)** | Resumable benchmarking CLI with YAML model registry — scores OCR/VLM engines by ANLS/CER/WER plus a vision-LLM judge for accuracy-vs-latency tradeoffs. | `Python` `vLLM` `OCR` `Eval` |

More context and writeups: **[aayush-portfolio-sandy.vercel.app](https://aayush-portfolio-sandy.vercel.app/)**.

## stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,js,ts,html,css,fastapi,postgres,redis,docker,linux,git,react,nextjs,tailwind,nodejs&theme=dark" alt="tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Keycloak-auth-4ADE80?style=flat-square&labelColor=101216" alt="Keycloak" />
  <img src="https://img.shields.io/badge/Marqo-search-4ADE80?style=flat-square&labelColor=101216" alt="Marqo" />
  <img src="https://img.shields.io/badge/Temporal-workflows-4ADE80?style=flat-square&labelColor=101216" alt="Temporal" />
  <img src="https://img.shields.io/badge/vLLM-inference-4ADE80?style=flat-square&labelColor=101216" alt="vLLM" />
  <img src="https://img.shields.io/badge/Qdrant-vectors-4ADE80?style=flat-square&labelColor=101216" alt="Qdrant" />
  <img src="https://img.shields.io/badge/Pydantic-models-4ADE80?style=flat-square&labelColor=101216" alt="Pydantic" />
</p>

When OCR or RAG misbehaves, I'd rather **read the score and the trace** than guess.

## telemetry

<div align="center">
  <img height="165" src="https://github-readme-stats.shion.dev/api?username=nexus69420&show_icons=true&hide_border=true&bg_color=0A0B0D&title_color=4ADE80&icon_color=4ADE80&text_color=E8E6E0&ring_color=4ADE80&hide_rank=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.shion.dev/api/top-langs/?username=nexus69420&layout=compact&hide_border=true&bg_color=0A0B0D&title_color=4ADE80&text_color=E8E6E0" alt="top languages" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=nexus69420&bg_color=0A0B0D&color=8A8F98&line=4ADE80&point=4ADE80&area=true&hide_border=true&area_color=4ADE80" alt="contribution graph" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nexus69420/nexus69420/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nexus69420/nexus69420/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution snake" src="https://raw.githubusercontent.com/nexus69420/nexus69420/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

## connect

Open to **2026** software-engineering internships and full-time roles — backend, platform, or full-stack. If you're hiring for systems that need to stay up, I'd like to hear about it.

<p align="center">
  <a href="https://aayush-portfolio-sandy.vercel.app/">portfolio</a>
  &nbsp;·&nbsp;
  <a href="mailto:aayushdubey.work@gmail.com">aayushdubey.work@gmail.com</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/aayush-kumar-dubey-917bb9285">linkedin/in/aayush-kumar-dubey</a>
</p>

<p align="center">
  <sub><code>uptime 100% · last deploy: now</code></sub>
</p>
