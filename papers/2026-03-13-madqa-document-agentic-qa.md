---
layout: paper
title: "MADQA: Strategic Navigation or Stochastic Search in Document Collections"
date: 2026-03-13
arxiv_id: "2603.12180"
categories: [cs.CL, cs.AI]
---

# MADQA: Document-Intensive Workflow Benchmark

## 基本情報
- **arXiv ID**: 2603.12180
- **カテゴリ**: cs.CL, cs.AI
- **投稿日**: 2026年3月12日
- **注目ポイント**: 🤗 **Hugging Face共著** (Clementine Fourrier, Niels Rogge)

## 概要
マルチモーダルエージェントが真の戦略的推論を示すのか、単なる確率的試行錯誤なのかを検証するベンチマーク「MADQA」を提案。

## ベンチマーク構成
- **2,250の人間作成質問**
- **800の異種PDFドキュメント**
- Classical Test Theoryに基づく識別力設計

## 評価プロトコル
精度-労力トレードオフを測定する新しい評価プロトコルを導入。

## 主要な発見
- 最良エージェントは人間検索者と同等の精度を達成可能
- しかし異なる問題で成功し、弱い戦略計画をブルートフォース検索で補償
- オラクル性能との約20%のギャップは解消されず
- 非生産的ループに陥りがち

## 意義
ブルートフォース検索から、校正された効率的推論への移行を促進するためのデータセットと評価ツールを公開。

## リンク
- [arXiv](https://arxiv.org/abs/2603.12180)
- [PDF](https://arxiv.org/pdf/2603.12180)
