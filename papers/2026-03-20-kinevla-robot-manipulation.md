---
layout: default
title: "KineVLA: Towards Kinematics-Aware Vision-Language-Action Models"
---

# KineVLA: Towards Kinematics-Aware Vision-Language-Action Models with Bi-Level Action Decomposition

[arXiv:2603.17524](https://arxiv.org/abs/2603.17524) | cs.RO

## 著者
Gaoge Han et al.

## 一言まとめ
**運動学認識VLAタスク**を新規定義。方向・軌跡・姿勢・相対変位を言語コマンドに密にエンコードし、きめ細かい操作制御を実現。

## 概要
本研究は運動学リッチなVision-Language-Action (VLA)タスクを導入。言語コマンドが開始から完了まで、キーモーメントにおける多様な運動学属性（方向、軌跡、姿勢、相対変位）を密にエンコード。従来のアクション指示が運動学を粗くまたは部分的にしか捉えないのと対照的に、きめ細かいパーソナライズ操作をサポート。

## 注目ポイント
- **新規タスク定義**: 運動学認識VLAという新パラダイム
- **Bi-Level分解**: ゴールレベル不変性と運動学レベル可変性を明示的に分離
- **シミュレーション+実機**: LIBERO + Realman-75ロボットで評価
- **データセット構築**: シミュレーション・実世界両プラットフォーム対応

## 技術的詳細
- Bi-Level行動表現: 目標達成は不変、実行軌跡は指示に応じて適応
- Bi-Level推論トークン: 言語とアクションを整列させる明示的・教師付き中間変数
- 運動学認識VLAデータセット: 指示レベル運動学変動とBi-Levelアノテーション付き

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17524)
- [PDF](https://arxiv.org/pdf/2603.17524)
