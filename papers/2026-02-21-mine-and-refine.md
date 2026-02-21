# Mine and Refine: Optimizing Graded Relevance in E-commerce Search Retrieval

- **arXiv ID**: 2602.17654
- **カテゴリ**: cs.IR (情報検索)
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.17654

## 著者
Jiaqi Xi, Raghav Saboo, Luming Chen, Martin Wang, Sudeep Das

## 選定理由
✅ **実運用記載**: Production A/B tests、E-commerce searchシステムでデプロイ済み

## 概要
大規模Eコマース検索向けの2段階「Mine and Refine」コントラスト学習フレームワークを提案。検索における段階的な関連性（完全一致、代替品、補完品）を効果的に分離するための手法。

## 主要な貢献
1. **Policy-aligned LLM**: 人間アノテーションに基づく軽量LLMで3段階の関連性ガイドラインを学習
2. **Stage 1**: Label-aware supervised contrastive objectiveで多言語Siamese two-tower retrieverを学習
3. **Stage 2**: ANNでハードサンプルをマイニングし、Multi-class Circle Lossで関連性レベル間の境界を鮮明化
4. **ロバスト性強化**: スペルミス拡張と合成クエリ生成

## 実験結果
- オフライン評価とProduction A/Bテストで統計的に有意なエンゲージメントとビジネスインパクトの改善
- ノイズの多いロングテールクエリへの汎化性能を実証

## 技術的詳細
- Engagement-driven auditing でラベルノイズを軽減
- Hybrid blendingとthresholdingのための安定したsimilarity score分離を実現

## 関連研究
- Dense Retrieval
- Contrastive Learning for IR
- E-commerce Search
