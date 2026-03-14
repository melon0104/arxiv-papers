# IndexCache: Accelerating Sparse Attention via Cross-Layer Index Reuse

- **arXiv**: https://arxiv.org/abs/2603.12201
- **PDF**: https://arxiv.org/pdf/2603.12201
- **Categories**: cs.CL, cs.LG
- **Published**: 2026-03-12

## Authors
Yushi Bai, Qian Dong, Ting Jiang, Xin Lv, Zhengxiao Du, et al.

## Abstract
Long-context agentic workflows have emerged as a defining use case for large language models, making **attention efficiency critical** for both inference speed and serving cost.

Sparse attention addresses this challenge effectively, and **DeepSeek Sparse Attention (DSA)** is a representative production-grade solution: a lightweight lightning indexer selects the top-k most relevant tokens per query, reducing core attention from O(L²) to O(Lk).

## The Problem
However, the indexer itself retains **O(L²) complexity** and must run independently at every layer, despite the fact that the resulting top-k selections are highly similar across adjacent layers.

## IndexCache Solution
We propose **IndexCache**, which:
- **Caches top-k indices** across layers
- Reuses indices from previous layers with selective updates
- Reduces redundant index computation

### Key Insight
Top-k token selections exhibit high consistency across layers, enabling:
- Cross-layer index sharing
- Incremental index updates
- Significant compute savings

## Results
- Maintains quality of sparse attention
- Reduces indexing overhead substantially
- Applicable to production long-context serving

## Why Notable
- **DeepSeek collaboration**: Building on production sparse attention
- **Practical efficiency gains**: Addresses real-world serving costs
- **Long-context focus**: Critical for agentic workflows
