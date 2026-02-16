---
layout: paper
title: "Feed-SR: Industrial-Scale Sequential Recommender for LinkedIn Feed"
date: 2026-02-17
arxiv_id: "2602.12354"
category: cs.IR
tags: [recommender-systems, transformer, production, linkedin, feed-ranking]
---

# Feed-SR: An Industrial-Scale Sequential Recommender for LinkedIn Feed Ranking

## 基本情報
- **arXiv**: [2602.12354](https://arxiv.org/abs/2602.12354)
- **著者**: Lars Hertel, Gaurav Srivastava, Syed Ali Naqvi, Satyam Kumar et al.
- **機関**: LinkedIn

## 🏭 Industry Deployment
**LinkedInフィードの主要推薦システムとして本番稼働中**

## 一言まとめ
LinkedInフィードランキングのための産業規模Transformerベース逐次推薦モデル。DCNv2ベースのランカーを置き換え、厳しい本番制約を満たしながら大幅な改善を達成。

## 課題
- 既存のDCNv2ベースランカーの限界
- LinkedIn規模（数億ユーザー）での本番制約
- レイテンシと品質のトレードオフ

## 提案手法: Feed-SR
- Transformerベースの逐次ランキングモデル
- モデリング選択・学習テクニック・サービング最適化の詳細

### 検討した代替アーキテクチャ
- 他の逐次モデル
- LLMベースのランキングアーキテクチャ
- → Feed-SRが最良のオンライン指標と本番効率の組み合わせ

## 実験結果
### オンラインA/Bテスト
- **滞在時間**: +2.10%

## キーポイント
- LinkedIn規模での産業実装詳細
- LLMベースアーキテクチャとの比較検討
- 本番効率と指標改善の両立
