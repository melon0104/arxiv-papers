# A Long-term Value Prediction Framework In Video Ranking

- **arXiv ID**: 2602.17058
- **カテゴリ**: cs.IR (情報検索)
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.17058
- **DOI**: 10.1145/3774904.3792830

## 著者
Huabin Chen, Xinao Wang, Huiping Chu, Keqin Xu, et al.

## 選定理由
✅ **実運用記載**: Taobaoの本番システム（billion-scale）にデプロイ済み
✅ **有名研究機関**: Alibaba

## 概要
ショート動画推薦におけるランキング段階でのLong-term Value (LTV)予測フレームワーク。Position bias、Attribution ambiguity、Temporal limitationsの3つの課題に対処。

## 主要な貢献
1. **Position-aware Debias Quantile (PDQ)**: 分位数ベースの分布正規化でposition-robustなLTV推定を実現
2. **Multi-dimensional Attribution Module**: コンテキスト、行動、コンテンツシグナル間の連続的なアトリビューション強度を学習
3. **Cross-temporal Author Modeling**: Censoring-awareな日次LTVターゲットでクリエイター起点の再エンゲージメントを捕捉

## 実験結果
- オフライン評価とオンラインA/Bテストで有意なLTV指標改善
- 短期目標との安定したトレードオフ

## 技術的詳細
- Task augmentationとして既存ランキングモデルに統合
- 効率的なトレーニングとサービング設計
- Billion-scaleのTaobao本番システムでデプロイ済み

## 産業的インパクト
- ショート動画プラットフォームでのユーザーエンゲージメント最大化
- LTVとshort-term metricsのバランス制御
