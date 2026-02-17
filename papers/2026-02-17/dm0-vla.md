# DM0: An Embodied-Native Vision-Language-Action Model towards Physical AI

## 基本情報
- **arXiv**: [2602.14974](https://arxiv.org/abs/2602.14974)
- **カテゴリ**: cs.RO
- **投稿日**: 2026-02-16
- **著者**: En Yu, Haoran Lv, et al. (Dexmal)
- **コード**: [GitHub](https://github.com/Dexmal/dexbotic)

## 概要
Physical AI向けの**Embodied-Native Vision-Language-Action (VLA)フレームワーク**。インターネット事前訓練モデルの物理タスクへの適応という従来パラダイムから脱却。

## 技術的特徴
1. **3段階パイプライン**: Pretraining → Mid-Training → Post-Training
2. **統合事前訓練**: Webテキスト、自動運転、身体化インタラクションログを統合
3. **Flow-Matchingアクションエキスパート**: VLM上に構築
4. **ハイブリッド訓練戦略**: 身体化データではアクション勾配を非伝播、汎化表現を保持
5. **Embodied Spatial Scaffolding**: 空間的Chain-of-Thought推論を構築

## 主要結果
- **RoboChallengeベンチマークでSOTA達成**
- SpecialistとGeneralistの両設定で最高性能
- Table30で優れた結果

## 注目ポイント
🎯 **身体化AI向けの新しいVLAパラダイム**、マニピュレーションとナビゲーションを統合
