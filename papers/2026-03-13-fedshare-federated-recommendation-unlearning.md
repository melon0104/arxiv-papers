---
layout: paper
title: "FedShare: Federated Learn-Unlearn for Recommendation with Personalized Data Sharing"
date: 2026-03-13
arxiv_id: "2603.11610"
categories: [cs.IR]
---

# FedShare: Federated Learn-Unlearn for Recommendation

## 基本情報
- **arXiv ID**: 2603.11610
- **カテゴリ**: cs.IR（情報検索）
- **投稿日**: 2026年3月12日

## 概要
連合推薦システム（FedRS）において、ユーザーごとのデータ共有量を制御可能にし、さらに共有データの「忘却（unlearning）」にも対応したフレームワーク「FedShare」を提案。

## 主要な貢献
1. **パーソナライズされたデータ共有**: ユーザーが共有データ量を選択可能
2. **コントラスティブ学習**: ローカル・グローバル表現を整合
3. **コントラスティブunlearning**: 過去の埋め込みスナップショットを活用し、共有解除データの影響を選択的に除去

## 技術的利点
- 大量の履歴勾配情報の保存が不要（既存手法の課題を解決）
- 学習・unlearning両フェーズで強力な推薦性能
- unlearningフェーズでのストレージオーバーヘッドを大幅削減

## 評価
3つの公開データセットで、最先端ベースラインを上回る性能を実証。

## リンク
- [arXiv](https://arxiv.org/abs/2603.11610)
- [PDF](https://arxiv.org/pdf/2603.11610)
