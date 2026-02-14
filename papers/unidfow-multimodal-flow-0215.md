# UniDFlow: Unified Discrete Flow-Matching for Multimodal Reasoning and Generation

[📄 arXiv:2602.12221](https://arxiv.org/abs/2602.12221)

## 概要
マルチモーダル理解・生成・編集を統一するDiscrete Flow-Matchingフレームワーク。

## 提案手法
**UniDFlow**：
- **タスク固有Low-Rank Adapters**で理解と生成を分離
- 目的関数の干渉と表現の絡まりを回避
- **Reference-based multimodal preference alignment**：同一条件下で相対的な結果を最適化
- 大規模再訓練なしで忠実度・制御性を向上

## 実験結果
- **8つのベンチマークでSOTA性能**
- 強力なゼロショット汎化：
  - インペインティング
  - In-context画像生成
  - 参照ベース編集
  - 構成的生成
  （明示的なタスク固有訓練なしで達成）

## 注目ポイント
- 統一フレームワークでの多タスク対応
- ゼロショット汎化能力の高さ

## カテゴリ
cs.CV
