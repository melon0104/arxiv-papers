---
layout: default
title: Spava - Long-Video Understanding
---

# Spava: Accelerating Long-Video Understanding via Sequence-Parallelism-aware Approximate Attention

**arXiv:** [2601.21444](https://arxiv.org/abs/2601.21444) | **カテゴリ:** cs.CV, cs.AI, cs.CL

## 概要

長時間ビデオ推論の効率ボトルネックを解決する系列並列フレームワーク。複数GPUにわたる近似アテンションの分散により、計算削減と並列性向上を両立。より多くの視覚埋め込みを圧縮なしで処理可能に。

## 主要な貢献

1. **分散近似アテンション**: 計算削減＋並列性向上
2. **圧縮なし処理**: より多くの視覚埋め込みを扱えることでタスク性能向上
3. **システム最適化**: 負荷分散、融合フォワードパス

## 結果

- FlashAttn比**12.72倍**、ZigZagRing比**1.70倍**、APB比**1.18倍**高速化
- 性能低下なし

## 選定理由

✅ Tsinghua（THUNLP） | ✅ GitHub公開: [github.com/thunlp/APB](https://github.com/thunlp/APB)

[← 戻る](/)
