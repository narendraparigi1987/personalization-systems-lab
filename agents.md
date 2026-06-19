---
layout: default
title: Agentic Systems
permalink: /agents/
---

<div class="hero">

# Agentic Systems

Days 36&ndash;42: MCP tool interfaces, multi-step tool chaining, memory layer, agent evaluation, and end-to-end shopping assistant demo.
</div>

<div class="grid">
  <div class="card">
    <h3>Primary sources</h3>
    <p><span class="source-tag">S8</span> Model Context Protocol<br><span class="source-tag">S9</span> Anthropic: Code Execution with MCP</p>
    <a href="https://modelcontextprotocol.io/specification/2025-06-18/server" target="_blank" rel="noreferrer">MCP Spec &rarr;</a> &nbsp;
    <a href="https://www.anthropic.com/engineering/code-execution-with-mcp" target="_blank" rel="noreferrer">Anthropic &rarr;</a>
  </div>
  <div class="card">
    <h3>Supporting sources</h3>
    <p><span class="source-tag">S6</span> OpenAI: Function Calling &mdash; tool exposure patterns<br><span class="source-tag">S10</span> DSPy &mdash; agent evaluation and task scoring</p>
  </div>
</div>

## Concepts

- Tool, prompt, and resource interfaces (MCP primitives)
- Exposing search / recommend / profile as callable tools
- Single-tool agent loop
- Multi-step tool chaining
- Memory and preference storage
- Agent evaluation: task scoring and prompt optimization
- End-to-end shopping / search assistant workflow

## Week schedule

| Day | Source | Build | Checkpoint |
|-----|--------|-------|------------|
| 36 | <span class="source-tag">S8</span> | Define tool, prompt, and resource interfaces | <span class="checkpoint">Agent primitives defined</span> |
| 37 | <span class="source-tag">S6</span> | Expose search / recommend / profile as tools | <span class="checkpoint">Tool API layer ready</span> |
| 38 | <span class="source-tag">S8</span> | Build a simple agent that chooses one tool and answers | <span class="checkpoint">First agent demo works</span> |
| 39 | <span class="source-tag">S9</span> | Add multi-step tool use and tool chaining | <span class="checkpoint">Multi-step agent works</span> |
| 40 | <span class="source-tag">S8</span> | Add memory / preference storage | <span class="checkpoint">Memory layer persists</span> |
| 41 | <span class="source-tag">S10</span> | Add agent evaluation prompts and task scoring | <span class="checkpoint">Agent eval notebook ready</span> |
| 42 | <span class="source-tag">S9</span> | Demo a shopping / search assistant workflow end to end | <span class="checkpoint">Agent demo complete</span> |

## Milestone

- Marketplace agent complete with tool use, memory, and end-to-end demo

## Next

Continue to [Multimodal Systems]({{ '/multimodal/' | relative_url }}).
