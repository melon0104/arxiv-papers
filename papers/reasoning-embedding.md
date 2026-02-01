---
layout: default
title: Reasoning Models and Embeddings
---

# Do Reasoning Models Enhance Embedding Models?

**arXiv:** [2601.21192](https://arxiv.org/abs/2601.21192) | **カテゴリ:** cs.AI, cs.CL

## 概要

RLVR（Reinforcement Learning with Verifiable Rewards）で訓練された推論モデルが、埋め込みモデルの初期化として優れた表現を提供するか検証。驚くべきことに、**null effect**を発見：同一訓練レシピでRLVRバックボーンとベースモデルに一貫した性能差なし。

## 主要な貢献

1. **HRSA（Hierarchical Representation Similarity Analysis）**: 表現、幾何、機能レベルで類似性を分解
2. **発見**: RLVRは局所幾何再編成を誘導するが、グローバル多様体幾何と線形読み出しを保持
3. **Manifold Realignment**: 後続の対比学習がbase/reasoning初期化モデルを強くアラインメント

## 結論

- RLVRはSFTと異なり、意味的ランドスケープを根本的に再構築するのではなく、**既存ランドスケープ内で軌跡を最適化**

## 選定理由

✅ RLVR・埋め込みモデルの重要な分析

[← 戻る](/)
