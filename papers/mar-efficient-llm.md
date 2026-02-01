---
layout: default
title: MAR - Efficient LLMs
---

# MAR: Efficient Large Language Models via Module-aware Architecture Refinement

**arXiv:** [2601.21503](https://arxiv.org/abs/2601.21503) | **カテゴリ:** cs.AI, cs.CL, cs.LG, cs.NE

## 🏆 ICASSP 2026 採択

## 概要

LLMのエネルギー効率を向上させる2段階フレームワーク。State Space Models（SSM）による線形時間系列モデリングと、FFNへの活性化スパース化を統合。スパイキングニューラルネットワーク（SNN）とSSMの統合における課題に対し、Adaptive Ternary Multi-step Neuron（ATMN）とSpike-aware Bidirectional Distillation Strategy（SBDS）を設計。

## 主要な貢献

1. **SSM統合**: 線形時間系列モデリングでアテンションコスト削減
2. **活性化スパース化**: FFN計算コスト削減
3. **ATMN + SBDS**: SNN-SSM統合の情報密度・時間ミスマッチ問題を解決

## 結果

- 制約リソース下でdenseモデルの性能を効果的に回復
- 推論エネルギー消費を大幅削減
- 同等・大規模の効率モデルを上回る

## 選定理由

✅ ICASSP 2026採択 | ✅ 効率的LLMの新アーキテクチャ

[← 戻る](/)
