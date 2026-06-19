---
layout: default
title: Retrieval Systems
permalink: /retrieval/
---

<div class="hero">

# Retrieval Systems

Days 8&ndash;14: dense embeddings, ANN indexing, hybrid BM25 + vector fusion, and LLM query expansion.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary sources</h3>
    <p><span class="source-tag">S3</span> Vespa: Hybrid Text Search<br><span class="source-tag">S4</span> ColBERT</p>
    <a href="https://docs.vespa.ai/en/learn/tutorials/hybrid-search.html" target="_blank" rel="noreferrer">Vespa &rarr;</a> &nbsp;
    <a href="https://github.com/stanford-futuredata/ColBERT" target="_blank" rel="noreferrer">ColBERT &rarr;</a>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S5</span> Eugene Yan &mdash; discovery system tradeoffs<br><span class="source-tag">S6</span> OpenAI Function Calling &mdash; LLM query expansion</p>
  </div>
</div>

## Concepts

- Sentence-transformer embeddings and dense retrieval
- Approximate nearest neighbour (ANN) with FAISS
- BM25 vs vector retrieval tradeoffs
- Hybrid score fusion (RRF, linear combination)
- Query normalization and structured facet extraction
- LLM-powered query rewrite and expansion

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 8 | <span class="source-tag">S4</span> | Generate item embeddings with a sentence-transformer baseline | <span class="checkpoint">Embeddings indexed</span> |
| 9 | <span class="source-tag">S4</span> | Add ANN retrieval with FAISS or equivalent | <span class="checkpoint">Vector search works</span> |
| 10 | <span class="source-tag">S3</span> | Compare BM25 vs vector retrieval on evaluation set | <span class="checkpoint">Comparison notebook ready</span> |
| 11 | <span class="source-tag">S3</span> | Build hybrid retrieval score fusion | <span class="checkpoint">Hybrid search works</span> |
| 12 | <span class="source-tag">S7</span> | Implement query normalization and facet-style structured extraction | <span class="checkpoint">Query parser works</span> |
| 13 | <span class="source-tag">S6</span> | Add LLM query rewrite / expansion | <span class="checkpoint">Rewritten queries stored</span> |
| 14 | <span class="source-tag">S5</span> | Build retrieval dashboard; inspect latency vs quality | <span class="checkpoint">Retrieval checkpoint complete</span> |

## Milestone

- Hybrid search engine complete: BM25 + dense + fusion + LLM query expansion

## Next

Continue to [Recommendation Systems]({{ '/recommendations/' | relative_url }}).
