---
layout: paper
title: "CRIMSON: A Clinically-Grounded LLM-Based Metric for Generative Radiology Report Evaluation"
date: 2026-03-09
categories: [cs.CL, cs.AI, cs.CV]
arxiv_id: "2603.06183"
---

# CRIMSON: A Clinically-Grounded LLM-Based Metric for Generative Radiology Report Evaluation

## 基本情報
- **arXiv ID**: 2603.06183
- **カテゴリ**: cs.CL, cs.AI, cs.CV
- **投稿日**: 2026-03-09
- **コード・モデル**: https://github.com/rajpurkarlab/CRIMSON
- **公開モデル**: Fine-tuned MedGemma

## 著者
Mohammed Baharoon, Thibault Heintz, Siavash Raissi, Mahmoud Alabbad, Mona Alhammad, Hassan AlOmaish, Sung Eun Kim, Oishi Banerjee, Pranav Rajpurkar

## 概要
既存の胸部X線レポート評価メトリクスはセマンティック類似性マッチングや表現レベルの識別に主に焦点を当て、臨床的要件と乖離がある。**CRIMSON**を提案：**診断正確性、文脈的関連性、患者安全性**に基づいてレポートを評価する臨床的に根拠のある評価フレームワーク。

## 技術的詳細
CRIMSONは完全な臨床コンテキストを組み込み：
- 患者年齢、適応、ガイドラインベースの決定ルール
- 正常または臨床的に重要でない所見が全体スコアに不釣り合いな影響を与えることを防止

**エラー分類体系**：
- 虚偽所見、欠落所見、8つの属性レベルエラー（位置、重症度、測定、診断過剰解釈など）

**臨床的重要度レベル**：
- 緊急、緊急でないが対処可能、対処不要、予想される/良性
- 心胸部放射線科医との協力で開発したガイドラインに基づく
- 重症度認識重み付けにより臨床的に重大なミスを良性の不一致より優先

## 主要結果
**ReXVal**で検証（6名のボード認定放射線科医による注釈）：
- Kendall's τ = 0.61-0.71
- Pearson's r = 0.71-0.84

新規ベンチマーク導入：
- **RadJudge**: 臨床的に困難な合否シナリオのターゲットスイート、専門家判断との一貫した一致
- **RadPref**: 100以上のペアワイズケース、3名の心胸部放射線科医による評価、放射線科医選好との最強整合を達成

## 実用的意義
- 放射線レポート生成モデルの臨床的に意味のある評価
- 医療AIの安全性評価の標準化
- 臨床現場での実用的なレポート品質保証

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.06183
- GitHub: https://github.com/rajpurkarlab/CRIMSON
