---
layout: paper
title: "Scaling Laws for Reranking in Information Retrieval"
date: 2026-03-08
categories: [cs.IR]
---

# Scaling Laws for Reranking in Information Retrieval

- **arXiv**: [2603.04816](https://arxiv.org/abs/2603.04816)
- **著者**: Rahul Seetharaman et al.

## 概要

リランキングにおけるスケーリング則の初の体系的研究。Pointwise、Pairwise、Listwise リランキングの3パラダイムについて、モデルサイズとデータ予算に対する性能変化を分析。

## 主な貢献

1. **リランキングのスケーリング則を発見**: 性能は予測可能なべき乗則に従う
2. **小規模実験から大規模性能を予測**: 400Mパラメータモデルで1Bモデルの性能を予測可能
3. **メトリクス別の信頼性評価**: NDCG, MAPは信頼性が高く、MRRは予測しにくい

## 実験設定

- Cross-encoder リランカーの詳細なケーススタディ
- 複数の損失関数、モデル、メトリクスで評価
- In-domain / Out-of-domain の両方で検証

## 産業応用への示唆

- **大規模モデルの性能を小規模実験で予測可能**
- 計算リソースの大幅な節約が可能
- 産業グレードの検索システム構築に有用
