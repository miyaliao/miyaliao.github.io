---
layout: page
title: Evidence Chain Verification System for Research Agents
description: LLM Course Final Project | DeepScientist Extension
img: assets/img/3.jpg
importance: 2
category: work
---

- Extended DeepScientist with a citation fact-checking pipeline for research-agent reports, including PDF claim extraction, evidence tracking, literature API verification, and auditable report generation.
- Implemented a Semantic Scholar -> arXiv -> Crossref fallback verifier and structured claim-verification workflow to trace claims back to external evidence.
- Added framework-level execution constraints to prevent LLM agents from bypassing mandatory scoring, rendering, artifact recording, and memory-writing steps.
- Validated the system with 139 automated tests and 6 real multi-domain quests, covering 144 claim-verification calls and achieving 36/36 mandatory tool-call compliance.
