---
layout: paper
title: "OfficeQA Pro: An Enterprise Benchmark for End-to-End Grounded Reasoning"
date: 2026-03-10
categories: [cs.CL, cs.AI]
arxiv_id: "2603.08076"
---

# OfficeQA Pro: An Enterprise Benchmark for End-to-End Grounded Reasoning

## 基本情報
- **arXiv ID**: 2603.08076
- **カテゴリ**: cs.CL, cs.AI
- **投稿日**: 2026-03-09
- **所属**: Databricks

## 著者
Xinyu Xu, Weiru Liu, Wen Pu, Jonathan Herzig, Yonatan Bitton, Alisa Liu, Guan-Lin Chao, Ronan Le Bras, Hao Cheng, Jianfeng Gao

## 概要
一般ドメインでのLLM性能はQA・推論・幻覚ベンチマークで急速に向上するが、**企業文書での性能は不均一**のまま。企業シナリオ向けのRAGシステムは、ソース引用を必要としながら複雑な文書の理解を要求し、精度・エビデンス検索・正しいグラウンディングを同時に達成する必要がある。

**OfficeQA Pro**の提案：
- **560QAペア**：PowerPoint、Excel、Word文書から引用を要求する質問
- **4つのエンタープライズ推論技術**を評価
- Claude Opus、GPT-5.4、Gemini等の最新モデルをテスト

## 主要結果
- エンタープライズ対応アプローチは依然として**正確性不足**
- 引用精度がグラウンディングの課題を表出
- SOTAモデルでも**グラウンディング一貫性が低い**

## 評価されたモデル
- Claude Opus
- GPT-5.4  
- Gemini
- その他商用・オープンモデル

## 実用的意義
- エンタープライズRAGシステムの現実的評価基準
- 企業文書理解の課題特定
- ビジネスAI導入の指針

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08076
