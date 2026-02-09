# TokenMixer-Large: Scaling Up Large Ranking Models in Industrial Recommenders

**arXiv**: [2602.06563](https://arxiv.org/abs/2602.06563)  
**日付**: 2026-02-09  
**分野**: cs.IR（情報検索）  
**機関**: ByteDance

## 概要

ByteDanceが提案する7B〜15Bパラメータの大規模ランキングモデル。TokenMixerアーキテクチャを拡張し、以下の課題を解決：

1. **Residual設計の最適化**: mixing-and-reverting操作
2. **深層モデルの勾配更新改善**: inter-layer residuals
3. **完全なMoEスパース化**: Sparse-Pertoken MoE
4. **スケーラビリティ探索**: 15Bまでの拡張検証

## 技術的ポイント

- **アーキテクチャ**: 標準TransformerのSelf-Attentionをreshape操作に置換
- **MoE統合**: auxiliary lossと新規Sparse-Pertoken MoEアーキテクチャ
- **実運用**: ByteDanceの複数シナリオでデプロイ済み
- **スケーリング則**: オンライン/オフライン実験で検証

## 結果

- オンライントラフィックで7Bパラメータまでスケーリング成功
- オフライン実験で15Bパラメータまで検証
- 有意なオフライン・オンライン性能向上を達成

## 選定理由

- **有名研究機関**: ByteDance
- **実運用**: 複数のproductionシナリオでデプロイ
- 推薦システムの大規模モデルスケーリング則研究として重要
