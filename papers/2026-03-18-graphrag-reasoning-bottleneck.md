---
layout: paper
title: "The Reasoning Bottleneck in Graph-RAG"
date: 2026-03-18
arxiv_id: "2603.14045"
categories: ["cs.IR", "cs.CL"]
importance: "★★★"
---

# The Reasoning Bottleneck in Graph-RAG: Structured Prompting and Context Compression for Multi-Hop QA

## 基本情報
- **arXiv ID**: 2603.14045
- **タイトル**: The Reasoning Bottleneck in Graph-RAG: Structured Prompting and Context Compression for Multi-Hop QA
- **著者**: Alex Thomo et al.
- **投稿日**: 2026-03-14
- **分野**: cs.IR, cs.CL

## 概要
Graph-RAGシステムにおける「強い検索≠強い回答」問題を実証。KET-RAGを3つのマルチホップQAベンチマークで評価し、検索コンテキストにゴールド回答が77-91%含まれているにもかかわらず、精度は35-78%、エラーの73-84%が推論失敗であることを発見。

## 技術的貢献
- **SPARQL Chain-of-Thought**: 質問をエンティティ-リレーションシップコンテキストに整列したトリプルパターンクエリに分解
- **グラフウォーク圧縮**: 知識グラフ走査によりコンテキストを~60%圧縮、LLM呼び出し不要

## 実験結果
- **SPARQL CoT**: 精度 +2〜+14 ポイント改善
- **グラフウォーク圧縮**: 小型モデルで構造化プロンプティングと組み合わせ平均 +6 ポイント
- **コスト削減**: 質問タイプルーティングにより、フル拡張したLlama-8Bが非拡張Llama-70Bと同等以上、約12倍低コスト
- **汎用性**: LightRAGでも効果を確認、Graph-RAGシステム間で転移可能

## 意義
Graph-RAGの真のボトルネックは検索ではなく推論であることを定量化。小型モデルでも適切な拡張で大型モデルを凌駕できることを実証。
