# BPP: Long-Context Robot Imitation Learning by Focusing on Key History Frames

## 基本情報
- **arXiv**: [2602.15010](https://arxiv.org/abs/2602.15010)
- **カテゴリ**: cs.RO, cs.LG
- **投稿日**: 2026-02-16
- **著者**: Max Sobol Mark, Jacky Liang, Maria Attarian, Chuyuan Fu, **Debidatta Dwibedi**, **Dhruv Shah**, **Aviral Kumar** (Google DeepMind / CMU)

## 概要
履歴情報を必要とするロボットタスクのための**長文脈模倣学習手法**。過去観測への単純な条件付けでは偽相関にラッチしてしまう問題を解決。

## 技術的特徴
1. **Big Picture Policies (BPP)**: VLMが検出した意味的キーフレームのみに条件付け
2. **偽相関の分析**: 訓練時の履歴空間カバレッジ不足が根本原因
3. **コンパクトなタスク関連イベント集合**: 多様なロールアウトを少数の意味的イベントに射影
4. **分布シフトの大幅削減**: 表現力を犠牲にせずに汎化

## 主要結果
- 4つの実世界マニピュレーションタスクで評価
- 3つのシミュレーションタスクでも検証
- **最良比較手法より70%高い成功率**（実世界評価）

## 注目ポイント
🎯 **Google DeepMind/CMU**による実世界ロボット学習の重要な進歩、履歴依存タスクでの汎化を実現
