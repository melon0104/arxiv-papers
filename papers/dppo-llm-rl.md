---
layout: paper
title: "DPPO: Divergence Proximal Policy Optimization for LLMs"
date: 2026-02-06
arxiv_id: "2602.04879"
categories: ["cs.LG", "cs.AI", "cs.CL"]
---

# DPPO: Rethinking the Trust Region in LLM Reinforcement Learning

**arXiv**: https://arxiv.org/abs/2602.04879

## 概要

LLMのRLファインチューニングにおけるPPOの根本的な問題点を指摘し、改善版「DPPO」を提案。

## PPOの問題点

PPOのratio clipping機構はLLMの大規模語彙に**構造的に不適合**:
1. サンプルトークンの確率比は真のpolicy divergenceのノイズの多いMC推定
2. **低確率トークン**: 更新が過度にペナルティされる
3. **高確率トークン**: 壊滅的なシフトが制約不足

結果として訓練の非効率性と不安定性を招く。

## 提案手法: DPPO

- ヒューリスティックなクリッピングを**policy divergenceの直接推定**に置換
- Total VariationまたはKLに基づく制約
- **メモリ効率**: Binary近似とTop-K近似で巨大なメモリフットプリントを回避

## 実験結果

- 既存手法と比較して訓練の安定性と効率性が**大幅に向上**
- RLベースのLLMファインチューニングのより堅牢な基盤を提供

## 所感

PPOがLLMの大規模語彙に合わないという指摘は本質的。DPPOは理論的にも実装的にも洗練されたアプローチで、今後のLLM RL研究の重要な参照点になりそう。
