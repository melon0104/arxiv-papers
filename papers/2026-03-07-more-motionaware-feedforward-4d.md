# MoRe: Motion-aware Feed-forward 4D Reconstruction Transformer

**arXiv ID**: [2603.05078](https://arxiv.org/abs/2603.05078)

**カテゴリ**: cs.CV (コンピュータビジョン (CV))

**著者**: Juntong Fang, Zequn Chen, Weiqi Zhang, Donglin Di, Xuancheng Zhang...

**投稿日**: 2026-03-05

---

## 概要

Reconstructing dynamic 4D scenes remains challenging due to the presence of moving objects that corrupt camera pose estimation. Existing optimization methods alleviate this issue with additional supervision, but they are mostly computationally expensive and impractical in real-time applications. To address these limitations, we propose MoRe, a feedforward 4D reconstruction network that efficiently recovers dynamic 3D scenes from monocular videos. Built upon a strong static reconstruction backbone, MoRe employs an attention-forcing strategy to disentangle dynamic motion from static structure. To further enhance robustness, we fine-tune the model on large-scale, diverse datasets encompassing both dynamic and static scenes. Moreover, our grouped causal attention captures temporal dependencies and adapts to varying token lengths across frames, ensuring temporally coherent geometry reconstruction. Extensive experiments on multiple benchmarks demonstrate that MoRe achieves high-quality dynamic reconstructions with exceptional efficiency.

---

## コメント

Accepted by CVPR 2025. Project page:https://hellexf.github.io/MoRe/

---

**リンク**: https://arxiv.org/abs/2603.05078
