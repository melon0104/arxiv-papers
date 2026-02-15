# T3D: Few-Step Diffusion Language Models via Trajectory Self-Distillation

## メタ情報
- **arXiv ID**: 2602.12262
- **カテゴリ**: cs.CL, cs.LG
- **投稿日**: 2026-02-12
- **注目理由**: 💻 コード公開

## 概要
Diffusion大規模言語モデル（DLLMs）の少ステップデコーディングを改善する軌跡自己蒸留フレームワーク。Direct Discriminative Optimization (DDO)による逆KL目的でモード探索蒸留を促進。

## 主要貢献
1. **軌跡自己蒸留**: モデル自身の生成軌跡からの蒸留
2. **Direct Discriminative Optimization (DDO)**: 高確率教師モードへの集中を促進
3. **少ステップDLLMへの道筋**: フルステップとのギャップを大幅縮小

## 実験結果
- 厳しいステップ予算下で強力な少ステップベースラインと標準学習を一貫して上回る
- 実用的な少ステップDLLMの基盤を確立

## リンク
- 論文: https://arxiv.org/abs/2602.12262
- コード: https://github.com/Tyrion58/T3D
