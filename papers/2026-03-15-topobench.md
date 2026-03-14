# TopoBench: Benchmarking LLMs on Hard Topological Reasoning

- **arXiv**: https://arxiv.org/abs/2603.12133
- **PDF**: https://arxiv.org/pdf/2603.12133
- **Categories**: cs.AI, cs.CL
- **Venue**: ICLR 2026 Workshop on Logical Reasoning of Large Language Models (Accepted)
- **Published**: 2026-03-12

## Authors
Mayug Maniparambil, Nils Hoehing, Janak Kapuriya, Arjun Karuvally, Ellen Rushe, et al.

## Abstract
Solving topological grid puzzles requires reasoning over **global spatial invariants** such as:
- Connectivity
- Loop closure
- Region symmetry

This remains challenging for even the most powerful large language models (LLMs).

## TopoBench Benchmark
To study these abilities under controlled settings, we introduce **TopoBench**, featuring:
- **6 puzzle families** across 3 difficulty levels
- Puzzles requiring spatial and topological reasoning
- Programmatically verifiable solutions

## Key Findings
Evaluation of strong reasoning LLMs on TopoBench reveals:
- Even frontier models solve **fewer than one quarter of hard instances**
- **Two families nearly unsolved** by all tested models
- Performance degrades sharply with puzzle complexity

## Analysis
We investigate whether these failures stem from:
- Reasoning limitations
- Representation issues
- Spatial understanding gaps

The benchmark provides diagnostic insights into specific reasoning capabilities.

## Why Notable
- **ICLR 2026 Workshop accepted**: Prestigious reasoning workshop
- **Exposes LLM limitations**: Hard spatial reasoning remains unsolved
- **Controlled evaluation**: Verifiable benchmark with clear ground truth
