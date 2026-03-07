# SlideSparse: Fast and Flexible (2N-2):2N Structured Sparsity

**arXiv ID**: [2603.05232](https://arxiv.org/abs/2603.05232)

**カテゴリ**: cs.LG (機械学習 (ML))

**著者**: Hanyong Shao, Yingbo Hao, Ting Song, Yan Xia, Di Zhang...

**投稿日**: 2026-03-05

---

## 概要

NVIDIA's 2:4 Sparse Tensor Cores deliver 2x throughput but demand strict 50% pruning -- a ratio that collapses LLM reasoning accuracy (Qwen3: 54% to 15%). Milder $(2N-2):2N$ patterns (e.g., 6:8, 25% pruning) preserve accuracy yet receive no hardware support, falling back to dense execution without any benefit from sparsity. We present SlideSparse, the first system to unlock Sparse Tensor Core acceleration for the $(2N-2):2N$ model family on commodity GPUs. Our Sliding Window Decomposition reconstructs any $(2N-2):2N$ weight block into $N-1$ overlapping 2:4-compliant windows without any accuracy loss; Activation Lifting fuses the corresponding activation rearrangement into per-token quantization at near-zero cost. Integrated into vLLM, SlideSparse is evaluated across various GPUs (A100, H100, B200, RTX 4090, RTX 5080, DGX-spark), precisions (FP4, INT8, FP8, BF16, FP16), and model families (Llama, Qwen, BitNet). On compute-bound workloads, the measured speedup ratio (1.33x) approaches the theoretical upper-bound $N/(N-1)=4/3$ at 6:8 weight sparsity in Qwen2.5-7B, establishing $(2N-2):2N$ as a practical path to accuracy-preserving LLM acceleration. Code available at https://github.com/bcacdwk/vllmbench.

---

## コメント

なし

---

**リンク**: https://arxiv.org/abs/2603.05232
