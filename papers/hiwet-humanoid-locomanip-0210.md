# HiWET: Hierarchical World-Frame End-Effector Tracking for Long-Horizon Humanoid Loco-Manipulation

**arXiv**: [2602.06341](https://arxiv.org/abs/2602.06341)  
**日付**: 2026-02-09  
**分野**: cs.RO（ロボティクス）  
**機関**: 複数大学

## 概要

ヒューマノイドロコマニピュレーションを世界座標系でのエンドエフェクタ追跡問題として再定式化。従来のボディ中心座標系では累積ドリフトを補正できない課題を解決。

## 技術的ポイント

- **World-Frame Tracking**: グローバル座標系での推論
- **階層的強化学習**: グローバル推論と動的実行を分離
  - **High-level Policy**: サブゴール生成（エンドエフェクタ精度＋ベース位置の同時最適化）
  - **Low-level Policy**: 安定性制約下での実行
- **Kinematic Manifold Prior (KMP)**: 残差学習でマニピュレーション多様体を埋め込み

## 結果

- **長時間タスク**: 世界座標系での精確で安定したトラッキング
- **Sim-to-Real転移**: 低レベルポリシーの物理ヒューマノイドへのゼロショット転移を実証
- **多様なコマンド**: 様々なマニピュレーション指示に対する安定歩行

## 選定理由

- ヒューマノイドロコマニピュレーションの新手法
- Sim-to-Real転移の実証
