---
layout: default
title: Self-Improving Pretraining
---

# Self-Improving Pretraining: using post-trained models to pretrain better models

**arXiv:** [2601.21343](https://arxiv.org/abs/2601.21343) | **カテゴリ:** cs.CL, cs.AI, cs.LG

## 概要

事前学習段階からLLMの安全性・事実性・品質を向上させる新手法。ドキュメントをストリーミングしながら、各ステップで次のKトークン生成に対してRLを適用。強力なpost-trainedモデルが候補生成（モデルロールアウト、元サフィックス、書き換えサフィックス）を品質・安全性・事実性で判定。

## 主要な貢献

1. **事前学習時のRL適用**: fine-tuning前に問題行動を防止
2. **強力な判定モデル**: post-trainedモデルによる品質判定
3. **段階的改善**: 訓練初期は元/書き換えサフィックスに依存、改善後はロールアウトを報酬

## 結果

- 標準事前学習比で**事実性36.2%、安全性18.5%の相対改善**
- 全体生成品質で**最大86.3%の勝率改善**

## 選定理由

✅ 著名研究者（Jason Weston）による事前学習革新

[← 戻る](/)
