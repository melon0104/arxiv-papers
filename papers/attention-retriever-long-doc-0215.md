# AttentionRetriever: Attention Layers are Secretly Long Document Retrievers

[📄 arXiv:2602.12278](https://arxiv.org/abs/2602.12278)

## 概要
RAGにおける長文書検索の新手法。既存の検索モデルは長文書検索に最適化されておらず、文脈依存性・因果的依存関係・検索範囲の課題に対応できていない。

## 提案手法
**AttentionRetriever**：Attention機構とエンティティベース検索を活用し、文脈を考慮した長文書埋め込みを構築。
- 文脈認識型（context-aware）の埋め込み生成
- エンティティベースで検索範囲を動的に決定
- Dense検索モデルと同等の効率を維持

## 実験結果
- 長文書検索データセットで既存手法を大幅に上回る性能
- Dense検索モデルと同等の推論効率

## 注目ポイント
- 長文書RAGの根本課題に取り組む
- Attention機構の新しい活用法

## カテゴリ
cs.IR, cs.AI
