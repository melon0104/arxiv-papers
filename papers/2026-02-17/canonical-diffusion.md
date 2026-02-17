# Rethinking Diffusion Models with Symmetries through Canonicalization

## 基本情報
- **arXiv**: [2602.15022](https://arxiv.org/abs/2602.15022)
- **カテゴリ**: cs.LG, cs.AI
- **投稿日**: 2026-02-16
- **著者**: Cai Zhou, Zijie Chen, et al., Rose Yu, Muhan Zhang, Stephen Bates, **Tommi Jaakkola** (MIT)

## 概要
分子グラフ生成などの対称性を持つ生成タスクに対する新しいアプローチ。従来の等変デノイザー＋不変事前分布による制約ではなく、**正準化（canonicalization）**の観点から問題を解決。

## 技術的特徴
1. **商空間視点**: 正準拡散の正確性・普遍性・表現力の理論証明
2. **訓練高速化**: グループ混合による拡散スコア複雑性を削減
3. **幾何スペクトルベース正準化**: $S_n \times SE(3)$対称性下で具現化
4. **Canonアーキテクチャ**: CanonFlowとして実装

## 主要結果
- 3D分子生成で等変ベースラインを大幅に上回る
- **GEOM-DRUGデータセットでSOTA達成**
- 同等以下の計算量で性能向上
- Few-step生成でも優位性を維持

## 注目ポイント
🎯 **MIT Tommi Jaakkola**らによる分子生成の新パラダイム、理論と実践の両面で貢献
