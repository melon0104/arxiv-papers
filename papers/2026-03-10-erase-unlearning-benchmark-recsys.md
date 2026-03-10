---
layout: paper
title: "ERASE: A Real-World Aligned Benchmark for Unlearning in Recommender Systems"
date: 2026-03-10
categories: [cs.IR]
arxiv_id: "2603.08341"
---

# ERASE: A Real-World Aligned Benchmark for Unlearning in Recommender Systems

## 基本情報
- **arXiv ID**: 2603.08341
- **カテゴリ**: cs.IR (Information Retrieval)
- **投稿日**: 2026-03-09

## 著者
Pierre Lubitzsch, Maarten de Rijke, Sebastian Schelter

## 概要
Machine Unlearning (MU)は、プライバシーコンプライアンス、セキュリティ、責任問題に対応するため、訓練済みモデルから選択したデータを削除可能にする技術。既存のMUベンチマークは実世界の推薦システム設定を十分に反映していない：協調フィルタリングのみに焦点、非現実的に大きな削除リクエストを想定、逐次的アンラーニングや効率性などの実践的制約を見落とし。

本研究では**ERASE**を提案。実世界の利用に沿った大規模ベンチマークで、以下を網羅：
- **3つのコアタスク**: 協調フィルタリング、セッションベース推薦、次バスケット推薦
- **実世界シナリオ**: センシティブなインタラクションやスパムの逐次削除など
- **7つのアンラーニングアルゴリズム**: 汎用・推薦特化手法
- **9つの公開データセット・9つのSOTAモデル**
- **600GB以上の再利用可能なアーティファクト**（ログ、1000以上のモデルチェックポイント）

## 主要結果
- 近似アンラーニングは一部の設定で再訓練と同等性能
- ロバスト性はデータセット・アーキテクチャ間で大きく変動
- **繰り返しアンラーニング**で汎用手法の弱点が露呈（特にAttention・RNN系）
- 推薦特化手法はより安定した挙動

## 実用的意義
- GDPR等のデータ削除要請への対応能力評価
- 推薦システムのプライバシー・セキュリティ設計指針
- 実用的なMU手法選択の経験的基盤を提供

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08341
