# Towards Anytime-Valid Statistical Watermarking

- **arXiv ID**: 2602.17608
- **カテゴリ**: cs.LG, stat.ML
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.17608

## 著者
Baihe Huang, Eric Xu, Kannan Ramchandran, Jiantao Jiao, **Michael I. Jordan**

## 選定理由
✅ **有名研究機関**: UC Berkeley
✅ **有名研究者**: Michael I. Jordan (機械学習の大家)

## 概要
LLM出力のWatermarking検出において、初のe-value-basedフレームワーク「Anchored E-Watermarking」を提案。Optional stoppingでもType-I errorを保証するanytime-valid inferenceを実現。

## 主要な貢献
1. **E-value-based Watermarking**: Test supermartingaleを構築しanytime-valid推論を実現
2. **Anchor Distribution**: ターゲットモデルを近似するアンカー分布でoptimal e-valueを特徴づけ
3. **Optimal Stopping Time**: Worst-case log-growth rateに対する最適e-valueを導出

## 実験結果
- 検出に必要な平均トークン数を既存手法比で**13-15%削減**
- 標準ベンチマークでの有効性を実証

## 技術的詳細
- 従来の固定ホライズン仮説検定の制約を克服
- サンプリング分布選択の原理的アプローチを提供

## 関連研究
- LLM watermarking
- Sequential hypothesis testing
- E-values and anytime-valid inference
