---
layout: page
title: Dynamic LoRA for Efficient LLM Training
description: Gradient-norm–based dynamic switching between LoRA ranks and full fine-tuning. Target NeurIPS 2026.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

Research on efficient LLM fine-tuning. Proposed DFLoRA: a framework that dynamically switches between LoRA ranks and full fine-tuning based on gradient norms. Designed MoE-inspired parameter routing to preserve optimizer momentum during rank changes. Evaluated on Qwen2.5 and Gemma 3 across 10+ benchmarks—+2.1% vs static LoRA, 42% less catastrophic forgetting vs full fine-tuning.
