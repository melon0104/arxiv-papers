---
layout: paper
title: "C2RAG: Robust Multi-Hop GraphRAG Retrieval"
date: 2026-03-18
arxiv_id: "2603.14828"
categories: ["cs.IR"]
importance: "★★☆"
---

# Mitigating KG Quality Issues: A Robust Multi-Hop GraphRAG Retrieval Framework

## 基本情報
- **arXiv ID**: 2603.14828
- **タイトル**: Mitigating KG Quality Issues: A Robust Multi-Hop GraphRAG Retrieval Framework
- **著者**: Rongzheng Wang et al.
- **投稿日**: 2026-03-16
- **分野**: cs.IR

## 概要
不完全な知識グラフ上でのマルチホップ検索における「検索ドリフト」と「検索ハルシネーション」問題を解決するC2RAG (Constraint-Checked RAG)を提案。

## 技術的貢献
- **制約ベース検索**: クエリを原子制約トリプルに分解し、細粒度の制約アンカリングで候補をフィルタリング→検索ドリフト抑制
- **充足性チェック**: 現在のエビデンスが構造的伝播を正当化するのに十分かを明示的に判定、不十分な場合はテキスト回復を起動→検索ハルシネーション防止

## 実験結果
- 3つのマルチホップベンチマークで最新ベースラインを一貫して上回る
- 平均 EM +3.4%、F1 +3.9%
- KG品質問題下でも頑健性を維持

## 意義
実世界のKGが持つ固有のノイズや不完全性に対応したGraph-RAGフレームワーク。理論的な正確性と実用的な頑健性を両立。
