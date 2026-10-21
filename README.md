# llamaXia

Multi-agent LLM systems with automated Solana rewards for YouTube engagement — and a Minecraft break room.

## The system

Three layers, one machine:

1. **Social tipping & engagement bots** — crypto micro-rewards (Solana) distributed to YouTube commenters through automated bots + web wallet infrastructure. A middle layer of Python automation bridges YouTube's API to the chain, since there's no native link between them.
2. **Visual workflow automation** — n8n-powered workflows with pre-built integration nodes for basic LLM chains. The plumbing that turns agent decisions into real actions.
3. **Structured multi-agent operations** — CrewAI-style agent teams running on a linear operational blueprint. A coordinated crew that picks up tasks and gets work done — then kicks back in the Minecraft break room when off the clock.

## Status

Early development. Architecture being prototyped.

## The playlist

The official llamaXia playlist on YouTube — the sound of the build:
https://www.youtube.com/playlist?list=PLCkhxoFgwVbk

First tracks in: Falling In Reverse — "God Is A Weapon (feat. Marilyn Manson)" and Majestic Sounds Radio (24/7 live radio).

## Research directions

- **Next-Concept Modeling (NCM)** — Stanford / Together AI hierarchical generation: sketch first, words last, instead of one token at a time. Interesting for local agent brains because it cuts weight reads (the VRAM bottleneck) instead of just adding compute.
  - Paper: https://arxiv.org/abs/2610.14162
  - Code: https://github.com/HazyResearch/ncm
  - Status: watching, not wired in — the released code is evaluation-only, CUDA-only, and the web-text checkpoint is not usable yet.

## Ownership

All rights reserved. Created by meta4ickly-ux.
