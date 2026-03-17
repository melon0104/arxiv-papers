---
layout: paper
title: "SmartSearch: Conversational Memory Retrieval"
date: 2026-03-18
arxiv_id: "2603.15599"
categories: ["cs.LG"]
importance: "★★☆"
---

# SmartSearch: How Ranking Beats Structure for Conversational Memory Retrieval

## 基本情報
- **arXiv ID**: 2603.15599
- **タイトル**: SmartSearch: How Ranking Beats Structure for Conversational Memory Retrieval
- **著者**: Jesper Derehag et al.
- **投稿日**: 2026-03-16
- **分野**: cs.LG

## 概要
会話履歴からの検索において、LLMベースの構造化やポリシー学習は不要であることを実証。完全決定論的パイプラインでSOTAを達成。

## 技術的貢献
- **NER重み付きサブストリングマッチング**: 再現率向上
- **ルールベースエンティティ発見**: マルチホップ拡張
- **CrossEncoder+ColBERTランク融合**: 唯一の学習コンポーネント、CPU上で~650msで動作
- **スコア適応的トランケーション**: トークン予算内で最大限の関連情報を保持

## 実験結果
- **LoCoMo**: 93.5%
- **LongMemEval-S**: 88.4%
- 同一評価プロトコル下で全既知メモリシステムを上回る
- フルコンテキストベースラインより8.5倍少ないトークン

## オラクル分析
- 検索再現率は98.6%に達するが、インテリジェントなランキングなしではトークン予算へのトランケーションで22.5%のゴールドエビデンスしか残らない（コンパイルボトルネック）

## 意義
「構造より ランキング」の原則を実証。LLMベースの複雑な構造化なしで会話メモリ検索のSOTAを達成。
