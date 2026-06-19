---
layout: default
title: Personalization Layer
permalink: /personalization/
---

<div class="hero">

# Personalization Layer

Days 22&ndash;28: user profile vectors, session modeling, intent prediction, and personalized reranking.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary sources</h3>
    <p><span class="source-tag">S1</span> Netflix: System Architectures<br><span class="source-tag">S2</span> Netflix: FM-Intent</p>
    <a href="https://netflixtechblog.com/fm-intent-predicting-user-session-intent-with-hierarchical-multi-task-learning-94c75e18f4b8" target="_blank" rel="noreferrer">FM-Intent &rarr;</a>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S5</span> Eugene Yan &mdash; offline A/B simulation and architecture design</p>
  </div>
</div>

## Concepts

- User profile vector construction (long-term preferences)
- Category affinity and short-term interest features
- Session-state modeling from recent click sequences
- Intent prediction: browse / compare / buy
- Personalized reranking fusing profile + session + retrieval signals
- Offline A/B simulation framework

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 22 | <span class="source-tag">S1</span> | Build user profile vectors | <span class="checkpoint">Profile store created</span> |
| 23 | <span class="source-tag">S2</span> | Add category affinity and short-term interest features | <span class="checkpoint">Affinity features working</span> |
| 24 | <span class="source-tag">S2</span> | Add session-state modeling from recent clicks | <span class="checkpoint">Session state available</span> |
| 25 | <span class="source-tag">S2</span> | Implement intent prediction: browse / compare / buy | <span class="checkpoint">Intent classifier works</span> |
| 26 | <span class="source-tag">S1</span> | Personalized reranking using profile + session + retrieval | <span class="checkpoint">Personalized reranker works</span> |
| 27 | <span class="source-tag">S5</span> | Build offline A/B simulation framework | <span class="checkpoint">Experiment harness ready</span> |
| 28 | <span class="source-tag">S5</span> | Write architecture note for personalized search/ranking | <span class="checkpoint">Week 4 design doc done</span> |

## Milestone

- Personalized search and ranking complete with intent classification and offline experiments

## Next

Continue to [LLM Search Systems]({{ '/llm-search/' | relative_url }}).
