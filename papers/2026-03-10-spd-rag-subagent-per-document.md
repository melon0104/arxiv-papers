---
layout: paper
title: "SPD-RAG: Sub-Agent Per Document Retrieval-Augmented Generation"
date: 2026-03-10
categories: [cs.CL, cs.AI, cs.IR]
arxiv_id: "2603.08329"
---

# SPD-RAG: Sub-Agent Per Document Retrieval-Augmented Generation

## 基本情報
- **arXiv ID**: 2603.08329
- **カテゴリ**: cs.CL, cs.AI, cs.IR
- **投稿日**: 2026-03-09

## 著者
Yagiz Can Akay, Muhammed Yusuf Kartal, Esra Alparslan, Faruk Ortakoyluoglu, Arda Akpinar

## 概要
複雑な実世界クエリへの回答は、膨大なドキュメントコーパス全体に散在する事実の統合を要求。標準的なRAGパイプラインは不完全な証拠カバレッジに悩まされ、長コンテキストLLMは大量入力での信頼性ある推論に苦戦。

**SPD-RAG**の提案：**ドキュメント軸に沿って問題を分解**する階層的マルチエージェントフレームワーク

アーキテクチャ：
- 各ドキュメントは専用の**Document-level Agent**が処理（自身のコンテンツのみで動作）
- **Coordinator**が関連エージェントにタスクを配信し、部分回答を集約
- **Token-bounded Synthesis Layer**で部分回答をマージ（大規模コーパス向け再帰的map-reduce対応）

## 主要結果
- **LOONG benchmark** (EMNLP 2024) で平均スコア58.1を達成
- Normal RAG (33.0)、Agentic RAG (32.8) を大幅に上回る
- フルコンテキストベースライン (68.0) の**38%のAPIコスト**で競争力ある性能

## 技術的詳細
- ドキュメントレベルの専門化と中央集権的融合
- モジュラー・拡張可能な検索パイプライン
- スケーラビリティと回答品質の両立

## 実用的意義
- 大規模マルチドキュメントQAの効率化
- コスト効率の高いRAGアーキテクチャ
- 企業向け知識検索システムの設計指針

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08329
