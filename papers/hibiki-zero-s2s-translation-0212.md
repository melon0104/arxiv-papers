---
layout: paper
title: "Hibiki-Zero: Simultaneous Speech-to-Speech Translation Without Aligned Data"
arxiv_id: "2602.11072"
date: 2026-02-12
categories: [cs.CL, cs.SD, eess.AS]
github: "https://github.com/kyutai-labs/hibiki-zero"
---

# Hibiki-Zero: Simultaneous S2S Translation

## 基本情報
- **arXiv**: [2602.11072](https://arxiv.org/abs/2602.11072)
- **カテゴリ**: cs.CL, cs.SD, eess.AS
- **著者**: Tom Labiausse et al. (Kyutai Labs)
- **コード**: [GitHub](https://github.com/kyutai-labs/hibiki-zero)

## 概要

単語レベルアラインメントデータを完全に不要にした同時音声翻訳モデル。GRPOによる強化学習で翻訳品質を維持しながら遅延を最適化。

## 技術的貢献

### 訓練パイプラインの簡略化
1. 文レベルアラインメントデータで高遅延音声翻訳を学習
2. GRPO強化学習で遅延最適化（品質維持）

### 多言語対応の容易さ
- 言語固有のアラインメントヒューリスティック設計が不要
- 1000時間未満の音声で新言語追加可能

## 性能

5つのX-to-Englishタスクで以下のSOTAを達成：
- 翻訳精度
- 遅延
- 音声転送
- 自然さ

## リソース

- モデル重み公開
- 推論コード公開
- 45時間多言語評価ベンチマーク公開
