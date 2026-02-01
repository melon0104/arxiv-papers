---
layout: default
title: A2RAG - Adaptive Agentic Graph Retrieval
---

# A2RAG: Adaptive Agentic Graph Retrieval for Cost-Aware and Reliable Reasoning

**arXiv:** [2601.21162](https://arxiv.org/abs/2601.21162) | **カテゴリ:** cs.IR, cs.AI, cs.DB

## 概要

Graph-RAGの2大ボトルネック（混合難易度ワークロードでのコスト浪費、グラフ抽象化による情報損失）を解決する適応型エージェントフレームワーク。証拠の十分性を検証し、必要時のみ検索を強化する適応型コントローラーと、グラフ信号を元テキストにマッピングするエージェント型検索器を組み合わせ。

## 主要な貢献

1. **適応型コントローラー**: 証拠の十分性を検証し、必要に応じてリファインメント
2. **エージェント型検索器**: 検索努力を段階的にエスカレート、グラフ→元テキストへのマッピング
3. **抽出損失への頑健性**: 不完全なグラフでも動作

## 結果

- HotpotQA・2WikiMultiHopQAで**Recall@2が+9.9/+11.8**の絶対的改善
- トークン消費・エンドツーエンドレイテンシを約**50%削減**

## 選定理由

✅ 強力なGraphRAG手法 | ✅ 大幅なコスト削減と性能向上

[← 戻る](/)
