---
layout: default
title: Multimodal Systems
permalink: /multimodal/
---

<div class="hero">

# Multimodal Systems

Days 43&ndash;49: image embeddings, visual similarity, text + image fusion, cold-start items, and cold-start users.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary sources</h3>
    <p><span class="source-tag">S4</span> ColBERT &mdash; late-interaction retrieval patterns<br><span class="source-tag">S3</span> Vespa &mdash; fusion retrieval architecture</p>
    <a href="https://github.com/stanford-futuredata/ColBERT" target="_blank" rel="noreferrer">ColBERT &rarr;</a>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S5</span> Eugene Yan &mdash; cold-start handling and catalog coverage</p>
  </div>
</div>

## Concepts

- Image embeddings with CLIP or equivalent vision encoders
- Visual similarity search over an ANN index
- Text + image score fusion for multimodal retrieval
- Cold-start items: metadata-first ranking for new listings
- Cold-start users: popularity + onboarding signals
- Exploration and diversity logic for better catalog coverage

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 43 | <span class="source-tag">S4</span> | Add image embeddings for items | <span class="checkpoint">Image vectors indexed</span> |
| 44 | <span class="source-tag">S4</span> | Build visual similarity search | <span class="checkpoint">Similar-items-by-image works</span> |
| 45 | <span class="source-tag">S3</span> | Fuse text + image retrieval | <span class="checkpoint">Multimodal retrieval works</span> |
| 46 | <span class="source-tag">S5</span> | Handle cold-start items with metadata-first ranking | <span class="checkpoint">New-item path works</span> |
| 47 | <span class="source-tag">S5</span> | Handle cold-start users with popularity + onboarding signals | <span class="checkpoint">New-user path works</span> |
| 48 | <span class="source-tag">S1</span> | Add lightweight exploration / diversity logic | <span class="checkpoint">Better catalog coverage</span> |
| 49 | <span class="source-tag">S5</span> | Write multimodal + cold-start analysis note | <span class="checkpoint">Week 7 review complete</span> |

## Milestone

- Multimodal search complete with visual similarity, fusion retrieval, and cold-start paths

## Next

Continue to [Production Systems]({{ '/production/' | relative_url }}).
