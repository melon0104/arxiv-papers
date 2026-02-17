# Efficient Sampling with Discrete Diffusion Models: Sharp and Adaptive Guarantees

## 基本情報
- **arXiv**: [2602.15008](https://arxiv.org/abs/2602.15008)
- **カテゴリ**: cs.LG, cs.IT, math.ST, stat.ML
- **投稿日**: 2026-02-16
- **著者**: Daniil Dmitriev, Zhihan Huang, Yuting Wei

## 概要
離散空間上のスコアベース拡散モデルのサンプリング効率に関する**理論的基盤**を提供。τ-leapingベースサンプラーに対するシャープな収束保証を確立。

## 技術的特徴
1. **Uniform Discrete Diffusion**: $\tilde{O}(d/\varepsilon)$の反復複雑度達成
2. **語彙サイズSへの依存性除去**: 既存境界をd倍改善
3. **アルゴリズム下界**: 次元への線形依存は一般に不可避と証明
4. **Masking Discrete Diffusion**: 修正τ-leapingサンプラーを提案

## 主要結果
- **Effective Total Correlation**: 実質的な情報量を測る新指標
- $d \log S$で上界されるが、構造化データでは線形以下・定数になり得る
- Hidden Markov Model、画像データ、ランダムグラフで具体例
- スコアエントロピー損失のみを仮定（有界性・滑らかさ不要）

## 注目ポイント
🎯 **離散拡散モデルの理論的基盤**を確立、低次元構造への適応的な収束を証明
