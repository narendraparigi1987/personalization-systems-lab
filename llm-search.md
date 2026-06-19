---
layout: default
title: LLM Search Systems
permalink: /llm-search/
---

<div class="hero">

# LLM Search Systems

Days 29&ndash;35: tool-calling wrappers, structured query understanding, facet extraction, item enrichment, and LLM reranking.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary sources</h3>
    <p><span class="source-tag">S6</span> OpenAI: Function Calling<br><span class="source-tag">S7</span> OpenAI: Structured Outputs</p>
    <a href="https://platform.openai.com/docs/guides/function-calling" target="_blank" rel="noreferrer">Function Calling &rarr;</a> &nbsp;
    <a href="https://platform.openai.com/docs/guides/structured-outputs" target="_blank" rel="noreferrer">Structured Outputs &rarr;</a>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S10</span> DSPy &mdash; compositional LLM reranking and scoring loops</p>
    <a href="https://github.com/stanfordnlp/dspy" target="_blank" rel="noreferrer">DSPy &rarr;</a>
  </div>
</div>

## Concepts

- Tool-calling wrapper around search and recommend APIs
- Query classification with structured JSON output
- Query rewrite with schema-enforced output
- Facet extraction: brand, price, condition, location
- Item enrichment: tags, summaries, attributes
- LLM reranker / scoring loop
- Measuring LLM impact vs traditional ranking

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 29 | <span class="source-tag">S6</span> | Add basic tool-calling wrapper around search and recommend APIs | <span class="checkpoint">LLM can call tools</span> |
| 30 | <span class="source-tag">S7</span> | Add query classification with structured output | <span class="checkpoint">Queries classified reliably</span> |
| 31 | <span class="source-tag">S7</span> | Add query rewrite with JSON schema output | <span class="checkpoint">Rewrites are machine-readable</span> |
| 32 | <span class="source-tag">S7</span> | Add facet extraction: brand, price, condition, location | <span class="checkpoint">Facet extraction works</span> |
| 33 | <span class="source-tag">S7</span> | Add item enrichment: tags, summaries, attributes | <span class="checkpoint">Item enrichment pipeline works</span> |
| 34 | <span class="source-tag">S10</span> | Prototype an LLM reranker / scoring loop | <span class="checkpoint">LLM reranker running</span> |
| 35 | <span class="source-tag">S10</span> | Compare traditional ranking vs LLM-assisted ranking | <span class="checkpoint">LLM impact measured</span> |

## Milestone

- LLM search layer complete: structured query understanding, facet extraction, enrichment, and reranking

## Next

Continue to [Agentic Systems]({{ '/agents/' | relative_url }}).
