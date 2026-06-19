---
layout: default
title: Production Systems
permalink: /production/
---

<div class="hero">

# Production Systems

Days 50&ndash;56: candidate generation architecture, feature store, A/B framework, observability, guardrails, and capstone demo.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary sources</h3>
    <p><span class="source-tag">S5</span> Eugene Yan &mdash; end-to-end system design<br><span class="source-tag">S1</span> Netflix: System Architectures</p>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S6</span> OpenAI: Function Calling &mdash; guardrails and fallback<br><span class="source-tag">S8</span> MCP &mdash; final API boundary design<br><span class="source-tag">S10</span> DSPy &mdash; capstone demo</p>
  </div>
</div>

## Concepts

- Candidate generation &rarr; ranking &rarr; reranking architecture
- Feature-store style layer for search and recommendation signals
- Experimentation framework and A/B test reporting
- Observability: request logs, latency tracking, quality dashboards
- Guardrails, fallback behavior, and safe degradation
- Final system diagram and API boundary documentation

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 50 | <span class="source-tag">S5</span> | Design candidate generation &rarr; ranking &rarr; reranking architecture | <span class="checkpoint">Final architecture draft</span> |
| 51 | <span class="source-tag">S1</span> | Add feature-store style layer for search/reco features | <span class="checkpoint">Feature pipeline works</span> |
| 52 | <span class="source-tag">S5</span> | Add experimentation and A/B test reporting | <span class="checkpoint">Experiment layer ready</span> |
| 53 | <span class="source-tag">S5</span> | Add observability: logs, latency, quality dashboards | <span class="checkpoint">Monitoring in place</span> |
| 54 | <span class="source-tag">S6</span> | Add guardrails and fallback behavior | <span class="checkpoint">Safe fallback path works</span> |
| 55 | <span class="source-tag">S8</span> | Finalize agent/search system diagram and API boundaries | <span class="checkpoint">System design complete</span> |
| 56 | <span class="source-tag">S10</span> | Final capstone demo, repo cleanup, README, summary | <span class="checkpoint">Finished portfolio project</span> |

## Milestone

- Production-ready architecture complete

## Final deliverables

<div class="grid">
  <div class="card">
    <h3>Search stack</h3>
    <p>Hybrid BM25 + dense retrieval, LLM query understanding, facet extraction</p>
  </div>
  <div class="card">
    <h3>Recommendation stack</h3>
    <p>Collaborative filtering, session-aware signals, diversity controls</p>
  </div>
  <div class="card">
    <h3>Personalization layer</h3>
    <p>User profiles, intent prediction, personalized reranking</p>
  </div>
  <div class="card">
    <h3>Agentic assistant</h3>
    <p>Tool-using agent with memory, multi-step reasoning, and evaluation harness</p>
  </div>
  <div class="card">
    <h3>Multimodal retrieval</h3>
    <p>Image + text fusion, visual similarity, cold-start paths</p>
  </div>
  <div class="card">
    <h3>Experimentation framework</h3>
    <p>Offline A/B simulation, observability dashboards, guardrails</p>
  </div>
</div>
