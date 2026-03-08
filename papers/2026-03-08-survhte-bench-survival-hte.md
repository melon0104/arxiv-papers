---
layout: paper
title: "SurvHTE-Bench: A Benchmark for Heterogeneous Treatment Effect Estimation in Survival Analysis"
date: 2026-03-08
categories: [cs.LG, cs.AI, stat.ML]
---

# SurvHTE-Bench: Heterogeneous Treatment Effect Estimation Benchmark

- **arXiv**: [2603.05483](https://arxiv.org/abs/2603.05483)
- **会議**: **ICLR 2026 採択**
- **著者**: Shahriar Noroozizadeh et al.
- **GitHub**: https://github.com/Shahriarnz14/SurvHTE-Bench

## 概要

右打ち切り生存データからの異質的処置効果（HTE）推定のための初の包括的ベンチマーク。精密医療や個別化政策立案など高リスク応用において重要。

## ベンチマーク構成

1. **合成データセット**: 既知のグラウンドトゥルース、因果仮定と生存ダイナミクスを体系的に変化
2. **半合成データセット**: 実世界の共変量とシミュレートされた処置・アウトカム
3. **実世界データセット**: 双子研究（既知のGT）とHIV臨床試験

## 評価対象手法

- Causal Survival Forests
- 生存メタ学習器
- アウトカム補完アプローチ

## 注目ポイント

- **初の生存分析向けHTE推定ベンチマーク**
- ICLR 2026採択
- 公平で再現可能な評価基盤を確立
- データ・コード公開
