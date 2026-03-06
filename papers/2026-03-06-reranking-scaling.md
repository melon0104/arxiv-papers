---
layout: paper
title: "Scaling Laws for Reranking in Information Retrieval"
date: 2026-03-06
categories: [cs.IR]
---

# Scaling Laws for Reranking in Information Retrieval

**arXiv**: [2603.04816](https://arxiv.org/abs/2603.04816)

**著者**: Rahul Seetharaman et al.

**カテゴリ**: cs.IR

## 概要

リランカーのスケーリング則に関する初の体系的研究。pointwise、pairwise、listwise の3つのリランキングパラダイムについて、モデルサイズとデータ予算にわたるパフォーマンスを分析。

## 主な貢献

- **予測可能なべき乗則**: クロスエンコーダリランカーの詳細なケーススタディで、性能が予測可能なべき乗則に従うことを実証
- **計算リソースの節約**: 小規模モデル（最大400Mパラメータ）のみを訓練・評価し、1Bパラメータモデルの性能を正確に推定可能
- **ドメイン内・ドメイン外両方で有効**: 両設定でNDCGを正確に予測
- **メトリクス依存性**: NDCG、MAPは信頼性のあるスケーリング挙動を示すが、Contrastive EntropyやMRRは全ての場合で予測可能ではない

## 注目ポイント

- 産業グレード検索システム構築のための実践的知見を提供
- リランキングのスケーリング原則を確立
