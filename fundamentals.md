---
layout: default
title: Fundamentals
permalink: /fundamentals/
---

<div class="hero">

# Fundamentals

Days 1&ndash;7: build the base layer &mdash; schemas, synthetic data, BM25 search, and offline evaluation.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary source</h3>
    <p><span class="source-tag">S5</span> Eugene Yan &mdash; System Design for Recommendations and Search</p>
    <a href="https://eugeneyan.com/writing/system-design-for-discovery/" target="_blank" rel="noreferrer">Read &rarr;</a>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S1</span> Netflix: System Architectures<br><span class="source-tag">S3</span> Vespa: Hybrid Text Search</p>
  </div>
</div>

## Concepts

- Information retrieval basics and BM25
- User and item schema design
- Synthetic behavior log generation
- Offline evaluation: Recall@K, MRR, NDCG
- Failure analysis methodology

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 1 | <span class="source-tag">S5</span> | Repo scaffold, env, notebook layout, synthetic catalog design | <span class="checkpoint">Project runs locally</span> |
| 2 | <span class="source-tag">S5</span> | Define schemas: User, Item, SearchEvent, ClickEvent, PurchaseEvent | <span class="checkpoint">Data model committed</span> |
| 3 | <span class="source-tag">S1</span> | Generate synthetic behavior logs and basic user/item distributions | <span class="checkpoint">Dataset created</span> |
| 4 | <span class="source-tag">S3</span> | Implement BM25 baseline search | <span class="checkpoint">Search returns ranked results</span> |
| 5 | <span class="source-tag">S5</span> | Add Recall@K, MRR, NDCG notebook | <span class="checkpoint">Evaluation notebook works</span> |
| 6 | <span class="source-tag">S1</span> | Do failure analysis on baseline search | <span class="checkpoint">Top failure modes listed</span> |
| 7 | <span class="source-tag">S5</span> | Write week-one summary and design notes | <span class="checkpoint">Week 1 review complete</span> |

## Milestone

- Search V1 complete with BM25, evaluation notebook, and failure analysis

## Next

Continue to [Retrieval Systems]({{ '/retrieval/' | relative_url }}).
