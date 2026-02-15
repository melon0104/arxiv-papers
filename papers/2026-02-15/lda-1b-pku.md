# LDA-1B: Scaling Latent Dynamics Action Model via Universal Embodied Data Ingestion

## メタ情報
- **arXiv ID**: 2602.12215
- **カテゴリ**: cs.RO
- **投稿日**: 2026-02-12
- **機関**: Peking University, NVIDIA
- **著者**: Ming-Yu Liu（NVIDIA）, He Wang（PKU）他
- **注目理由**: 🏫 北京大学 + 🏢 NVIDIA

## 概要
10億パラメータのロボット基盤モデル。異種データから転移可能なダイナミクス知識を活用し、ダイナミクス・ポリシー・視覚予測を同時学習。

## 主要貢献
1. **EI-30k**: 30,000時間以上の人間・ロボット軌跡を統一フォーマットで整備
2. **DINO潜在空間での予測**: 冗長なピクセル空間外観モデリングを回避
3. **マルチモーダル拡散Transformer**: 非同期ビジョン・行動ストリームを処理

## 実験結果
- **接触リッチタスク**: π₀.₅比で最大+21%
- **器用操作タスク**: 最大+48%
- **長期タスク**: 最大+23%
- **低品質軌跡活用**: 30%の低品質軌跡で+10%改善

## リンク
- 論文: https://arxiv.org/abs/2602.12215
- プロジェクト: https://pku-epic.github.io/LDA
