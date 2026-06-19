---
layout: default
title: Recommendation Systems
permalink: /recommendations/
---

<div class="hero">

# Recommendation Systems

Days 15&ndash;21: collaborative filtering, top-N generation, evaluation, diversity, and session-aware signals.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary sources</h3>
    <p><span class="source-tag">S1</span> Netflix: System Architectures<br><span class="source-tag">S5</span> Eugene Yan: System Design</p>
    <a href="https://netflixtechblog.com/system-architectures-for-personalization-and-recommendation-e081aa94b5d8" target="_blank" rel="noreferrer">Netflix &rarr;</a>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S2</span> Netflix: FM-Intent &mdash; session signals for recommendation</p>
    <a href="https://netflixtechblog.com/fm-intent-predicting-user-session-intent-with-hierarchical-multi-task-learning-94c75e18f4b8" target="_blank" rel="noreferrer">Read &rarr;</a>
  </div>
</div>

## Concepts

- User-item interaction matrix construction
- Collaborative filtering and matrix factorization (ALS)
- Top-N candidate generation
- Evaluation: MAP, HitRate, Recall@K
- Diversity with MMR and reranking rules
- Session-aware signals and next-item prediction

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 15 | <span class="source-tag">S1</span> | Create user-item interaction matrix | <span class="checkpoint">Matrix built</span> |
| 16 | <span class="source-tag">S1</span> | Train a simple collaborative-filtering baseline (ALS) | <span class="checkpoint">First recommender runs</span> |
| 17 | <span class="source-tag">S1</span> | Generate top-N recommendations | <span class="checkpoint">Recommendation endpoint works</span> |
| 18 | <span class="source-tag">S5</span> | Add MAP / HitRate / Recall@K evaluation | <span class="checkpoint">Recommender metrics notebook ready</span> |
| 19 | <span class="source-tag">S5</span> | Add diversity with MMR or reranking rules | <span class="checkpoint">Diversity feature added</span> |
| 20 | <span class="source-tag">S2</span> | Add session-aware signals to the recommendation logic | <span class="checkpoint">Session features available</span> |
| 21 | <span class="source-tag">S5</span> | Compare popularity vs CF vs session-aware recommender | <span class="checkpoint">Week 3 comparison complete</span> |

## Milestone

- Recommendation engine complete with offline evaluation and diversity controls

## Next

Continue to [Personalization Layer]({{ '/personalization/' | relative_url }}).
