---
layout: page
title: Qwen3-Math RL Pipeline
description: LLM Course Mid-term Project
img: assets/img/12.jpg
importance: 1
category: work
---

[GitHub](https://github.com/miyaliao/Qwen3-Math-RL-Pipeline)

- Built an end-to-end optimization pipeline for Qwen3-Math, covering math data cleaning, prompt-completion formatting, LoRA-based supervised fine-tuning, inference evaluation, and RL training preparation.
- Implemented local multi-pass evaluation to compute `pass@1`, `pass@8`, and `correct_ratio`, then stratified samples by difficulty to identify unstable reasoning cases suitable for reinforcement learning.
- Prepared RL training data and implemented GRPO training scripts, improving final validation accuracy from 38.5% to 46.70% (+8.20 percentage points).
