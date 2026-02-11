# QP-OneModel: A Unified Generative LLM for Multi-Task Query Understanding in Xiaohongshu Search

## 基本情報
- **arXiv**: [2602.09901](https://arxiv.org/abs/2602.09901)
- **カテゴリ**: cs.IR, cs.CL
- **投稿日**: 2026-02-10
- **機関**: Xiaohongshu (小紅書)

## 一言まとめ
SNS検索のクエリ理解を統一LLMで解決。小紅書で**deployed**、DCG+0.21%、リテンション+0.044%向上。

## 概要
SNS検索エンジンのクエリ処理（QP）は従来、個別の判別モデル（BERT等）のパイプラインに依存し、意味理解の制限とメンテナンス負荷が課題だった。QP-OneModelは異種サブタスクを統一シーケンス生成パラダイムに再定式化。

## 技術的貢献
- **統一生成パラダイム**: 異種サブタスクをシーケンス生成に統合
- **3段階アラインメント戦略**: 段階的な整合化で強化学習に移行
- **Multi-reward RL**: 複数報酬による強化学習
- **Intent Description生成**: 高忠実度な意味信号として下流タスクを支援

## 実験結果
- 判別ベースライン比で総合**+7.35%**
- NER F1 **+9.01%**、Term Weighting F1 **+9.31%**
- 32Bモデルを未見タスクで**+7.60%**上回る汎化
- オンラインA/B: DCG **+0.21%**、リテンション **+0.044%**

## 選定理由
✅ 有名機関 (Xiaohongshu/ByteDance系)
✅ 本番運用 (Fully deployed at Xiaohongshu)
