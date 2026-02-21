# Deep-Flow: Conditional Flow Matching for Continuous Anomaly Detection in Autonomous Driving

- **arXiv ID**: 2602.17586
- **カテゴリ**: cs.RO, cs.AI, cs.LG
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.17586

## 著者
Antonio Guillen-Perez

## 選定理由
✅ **有名データセット**: Waymo Open Motion Dataset (WOMD)
✅ **産業応用**: Level 4自動運転のSafety validation

## 概要
Level 4自動運転車のSafety-critical異常検出のための教師なしフレームワーク。Optimal Transport Conditional Flow Matching (OT-CFM)でエキスパート人間運転の連続確率密度を特徴づけ。

## 主要な貢献
1. **Spectral Manifold制約**: PCAボトルネックで低ランクspectral manifoldに生成プロセスを制約
2. **Lane-aware Goal Conditioning**: Early Fusion Transformerエンコーダ
3. **Kinematic Complexity Weighting**: パス曲率とjerkで高エネルギー機動を優先

## 実験結果
- **AUC-ROC 0.766**: Safety-critical eventsのheuristic golden set比
- Kinematic dangerとsemantic non-complianceの基本的区別を発見

## 技術的詳細
- 決定論的log-likelihood推定のための正確なJacobian trace計算
- Out-of-distribution behaviors（車線境界違反など）を検出

## 産業的インパクト
- 統計的Safety gatesの数学的基盤を提供
- 自動運転フリートの安全デプロイを支援
