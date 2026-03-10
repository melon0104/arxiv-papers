---
layout: paper
title: "CODA: Difficulty-Aware Compute Allocation for Adaptive Reasoning"
date: 2026-03-10
categories: [cs.CL]
arxiv_id: "2603.08659"
---

# CODA: Difficulty-Aware Compute Allocation for Adaptive Reasoning

## 基本情報
- **arXiv ID**: 2603.08659
- **カテゴリ**: cs.CL (Computation and Language)
- **投稿日**: 2026-03-09

## 著者
Siye Wu, Jian Xie, Yikai Zhang, Yanghua Xiao

## 概要
大規模推論モデルの出現は、推論時計算のスケーリングが複雑なタスクの性能を大幅に向上させることを実証。しかし、**overthinking問題**という別の罠に陥りがち：単純な問題に対して反復的な根拠が最小限の精度向上しかもたらさないにもかかわらず、不釣り合いに高いコストを発生させる。

これが**適応的推論**の動機：推論深度をインスタンスの難易度に動的に合わせる。

**CODA (Compute Allocation by Difficulty Awareness)** の提案：
- 推論をユーティリティ最大化問題として定式化
- 限界精度向上が増分コストを下回るまでトークンを割り当て
- ポリシー内部の難易度シグナルでトークン割り当てを実現

## 技術的詳細
- **グループベースロールアウト**による難易度推定
- **Gumbel-Softmax離散サンプリング**による適応的選択
- Easy-side gate: 単純なインスタンスでの冗長性をペナルティ
- Hard-side gate: 複雑なインスタンスでの熟考的ロールアウトを奨励

## 主要結果
- 外部アノテーション・ユーザー提供予算なしで適応的推論を実現
- 簡単なタスクで**60%以上のトークンコスト削減**、精度維持
- 難しいタスクでは熟考的ロールアウトを促進し性能最大化

## 実用的意義
- 推論コストと品質の動的バランス
- 大規模デプロイメントのコスト効率化
- overthinking問題の解決策

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08659
