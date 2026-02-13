---
layout: paper
title: "Transformerにおける方向と大きさの分離：二重解離"
---

# Disentangling Direction and Magnitude in Transformer Representations: A Double Dissociation Through L2-Matched Perturbation Analysis

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11169
- **カテゴリ**: cs.CL, cs.AI, cs.LG
- **著者**: Srikar Mangadoddi et al.
- **投稿日**: 2026-02-11

## 選定理由
✅ **ICML 2026投稿**: トップ会議投稿論文
✅ **理論的洞察**: Transformer表現の新しい理解

## 概要
Transformerの隠れ状態は高次元ベクトルとして情報をエンコードするが、方向（表現空間での向き）と大きさ（ベクトルノルム）が異なる機能的役割を果たすかは不明確。

## 技術的貢献
- **L2-matched Perturbation Analysis**: 角度摂動と大きさ摂動が同一のユークリッド変位を達成することを保証する手法
- **Cross-over Dissociation発見**: 
  - 角度摂動は言語モデリング損失に最大42.9倍の損傷
  - 大きさ摂動は統語処理（主語-動詞一致）に不均衡な損傷（20.4% vs 1.6%精度低下）
- **因果介入**: 角度損傷はアテンション経路を通じて流れ、大きさ損傷はLayerNorm経路を通じて流れる

## 実験結果
- Pythiaファミリーモデルでパターンが再現
- RMSNormベースアーキテクチャでは異なるパターン（アーキテクチャ依存性を示唆）

## 所感
線形表現仮説を精緻化する重要な発見。モデル編集と解釈可能性研究への含意あり。
