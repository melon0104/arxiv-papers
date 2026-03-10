---
layout: paper
title: "UIS-Digger: Towards Comprehensive Research Agent Systems for Real-world Unindexed Information Seeking"
date: 2026-03-10
categories: [cs.AI, cs.IR]
arxiv_id: "2603.08117"
conference: "ICLR 2026"
---

# UIS-Digger: Towards Comprehensive Research Agent Systems for Real-world Unindexed Information Seeking

## 基本情報
- **arXiv ID**: 2603.08117
- **カテゴリ**: cs.AI, cs.IR
- **投稿日**: 2026-03-09
- **採択**: ICLR 2026

## 著者
Chang Liu, Chuqiao Kuang, Tianyi Zhuang, Yuxin Cheng, Huichi Zhou, Xiaoguang Li, Lifeng Shang

## 概要
LLMベース情報検索エージェントの最近の進歩は確立されたベンチマークで記録的性能を達成。しかしこれらのエージェントは検索エンジンにインデックスされた知識に大きく依存し、**Unindexed Information Seeking (UIS)** という重大な盲点を残す。

UIS問題：検索エンジンクローラーに捕捉されない重要情報
- 見落とされたコンテンツ
- 動的ウェブページ
- 埋め込みファイル

**UIS-QA**ベンチマーク：
- 110件の専門家アノテーションQAペア
- SOTAエージェントでも性能が急落（GAIA 70.90→UIS-QA 24.55）

**UIS-Digger**フレームワーク：
- **Dual-mode browsing**: ウェブページ検索とファイルパース同時実行
- **~30Bパラメータ**バックボーンでSFT・RFT訓練
- O3やGPT-4.1搭載システムを上回る**27.27%**達成

## 主要結果
- 小規模モデル（~30B）でフロンティアモデル超え
- プロアクティブな非インデックスソースとの対話の重要性を実証
- 現行エージェント評価パラダイムの根本的限界を発見

## 技術的詳細
- デュアルモードブラウジング（検索+パース）
- SFT (Supervised Fine-Tuning) + RFT (Reinforcement Fine-Tuning)
- マルチエージェント協調アーキテクチャ

## 実用的意義
- 実世界情報検索の盲点への対処
- 包括的情報アクセスの実現
- 次世代リサーチエージェントの方向性

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08117
