---
layout: paper
title: "RGAlign-Rec: Ranking-Guided Alignment for Latent Query Reasoning"
date: 2026-02-17
arxiv_id: "2602.12968"
category: cs.IR
tags: [recommender-systems, llm, production, shopee, e-commerce, chatbot]
---

# RGAlign-Rec: Ranking-Guided Alignment for Latent Query Reasoning in Recommendation Systems

## 基本情報
- **arXiv**: [2602.12968](https://arxiv.org/abs/2602.12968)
- **著者**: Junhua Liu, Yang Jihao, Cheng Chang, Kunrong LI et al.
- **機関**: Shopee

## 🏭 Industry Deployment
**Shopee大規模プラットフォームでA/Bテスト実施**

## 一言まとめ
Eコマースチャットボットにおける「ゼロクエリ」推薦（プロアクティブ意図予測）のためのLLMとランキングモデルの統合フレームワーク。

## 課題
1. **セマンティックギャップ**: ユーザー特徴とチャットボットKBの意図間の乖離
2. **目的不整合**: 汎用LLM出力とタスク特化ランキングユーティリティの不一致

## 提案手法: RGAlign-Rec
1. **LLMベースセマンティック推論器**
2. **Query-Enhanced (QE) ランキングモデル**
3. **Ranking-Guided Alignment (RGA)**
   - 下流ランキングシグナルをフィードバックとして活用
   - LLMの潜在推論を精緻化

## 実験結果
### オフライン (大規模Shopeeデータセット)
- **GAUC**: +0.12%（エラー率3.52%相対削減）
- **Recall@3**: +0.56%

### オンラインA/Bテスト
- **QE-Rec (Query-Enhanced)**: CTR +0.98%
- **RGA追加**: さらに +0.13%

## キーポイント
- ゼロクエリ推薦という新しい問題設定
- ランキング信号でLLM推論を誘導
- 大規模Eコマースでの実証
