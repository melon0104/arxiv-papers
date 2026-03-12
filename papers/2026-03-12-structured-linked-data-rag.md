# Structured Linked Data as a Memory Layer for Agent-Orchestrated Retrieval

- **arXiv**: [2603.10700](https://arxiv.org/abs/2603.10700)
- **分野**: cs.IR（情報検索）、cs.AI
- **著者**: Andrea Volpini Volpini et al.
- **キーワード**: RAG, Schema.org, Linked Data, Google ADK

## 概要

RAGシステムは通常、文書をフラットテキストとして扱い、知識グラフが提供する構造化メタデータやリンク関係を無視している。本研究では、Schema.orgマークアップとLinked Data Platform上のエンティティページがRAG精度を改善できるかを検証。

## 実験設計

- **4ドメイン**: 編集、法務、旅行、Eコマース
- **Google Vertex AI Vector Search 2.0** + **Google Agent Development Kit (ADK)**
- **7条件**: プレーンHTML、JSON-LD付きHTML、エージェント最適化エンティティページ × 標準RAG/エージェントRAG

## 主な結果

- JSON-LD単体では改善は控えめ
- **Enhanced entity page形式**（llms.txt形式のエージェント指示、パンくずリスト、ニューラル検索機能を含む）で大幅改善:
  - 標準RAG: **+29.6%** 精度改善
  - エージェントパイプライン: **+29.8%** 精度改善
- Enhanced+（リッチなナビゲーションアフォーダンス付き）: 精度4.85/5、完全性4.55/5

## 注目ポイント

構造化データ×RAGの実証研究。データセット、評価フレームワーク、エンティティページテンプレートを公開しており再現性が高い。
