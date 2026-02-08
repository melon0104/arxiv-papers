# DFPO: Distributional Value Flow Policy Optimization

- **arXiv**: [2602.05890](https://arxiv.org/abs/2602.05890)
- **カテゴリ**: cs.LG, cs.CL
- **投稿日**: 2026-02-05
- **著者**: Fudan大学チーム (Tao Gui, Xipeng Qiu, Xuanjing Huang他)

## 概要

LLMポストトレーニングにおいて、ノイズのある監督信号とOOD汎化の問題に対処するロバストな分布型RLフレームワーク「DFPO」を提案。

## 主要な貢献

- **Value Flow Field学習**: 孤立した分位点予測ではなく、時間ステップにわたる連続的なフローとして価値をモデル化
- **条件付きリスク制御**: ノイズフィードバック下での訓練安定化
- **一貫性制約**: 価値フロー軌跡に沿った制約

## 実験結果

- 対話、数学推論、科学タスクでPPO、FlowRL、他のロバストベースラインを上回る
- ノイズ監督下での訓練安定性と汎化性能の向上

## リンク

- [PDF](https://arxiv.org/pdf/2602.05890)
