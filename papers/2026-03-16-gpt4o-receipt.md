---
layout: paper
date: 2026-03-16
title: "GPT4o-Receipt: AI-Generated Document Forensics"
arxiv_id: "2603.11442"
categories: [cs.AI, cs.CV]
---

# GPT4o-Receipt: AI-Generated Document Forensics

## 基本情報
- **arXiv ID**: 2603.11442
- **カテゴリ**: cs.AI, cs.CV

## 概要
AI生成財務文書（領収書）の検出に関するベンチマーク。GPT-4o生成領収書1,235枚と本物の領収書をペアリングし、5つのSOTA MLLMと30人のアノテーターで評価。

## 主な発見
- **パラドックス**: 人間はAIの視覚的アーティファクトをより良く見抜くが、AI文書検出では劣る
- 支配的なフォレンジック信号は**算術エラー**（人間には不可視、LLMは瞬時に検証）
- 小計が正しいかどうかは人間には見えないが、LLMはミリ秒で検証

## 評価結果
- **Claude Sonnet 4**: 最高性能
- **Gemini 2.5 Flash**: 人間を上回る
- 5モデル間で**大きな性能差とキャリブレーション差**

## 注目ポイント
- 単純な精度指標では検出器選択に不十分
- AI生成文書フォレンジクスの新しい評価フレームワーク
- 人間+AIのハイブリッド検出の可能性
