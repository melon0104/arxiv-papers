---
layout: default
title: "EVA: Aligning Video World Models with Executable Robot Actions"
---

# EVA: Aligning Video World Models with Executable Robot Actions via Inverse Dynamics Rewards

[arXiv:2603.17808](https://arxiv.org/abs/2603.17808) | cs.RO

## 著者
Ruixiang Wang et al.

## 一言まとめ
ビデオワールドモデルの**実行可能性ギャップを強化学習で解消**。逆動力学報酬でロボット制約適合を促進、RoboTwin+実機で成功率向上。

## 概要
ビデオ生成モデルはロボティクスのワールドモデルとして利用が進むが、現行のビデオワールドモデルには明示的な実行可能性制約がない。視覚的に一貫したロールアウトでも剛体・運動学的整合性に違反し、逆動力学モデル(IDM)でデコード時に不安定または実行不能な制御コマンドを生成することがある。この視覚生成と物理実行可能制御の不一致を「実行可能性ギャップ」と呼ぶ。

## 注目ポイント
- **実行可能性ギャップ活用**: 訓練シグナルとして利用
- **RLポストトレーニング**: 逆動力学モデルを報酬モデルとして転用
- **滑らかな動作促進**: 速度・加速度・ジャークを測定、エンボディメント制約違反をペナルティ
- **アーティファクト耐性**: 重度視覚アーティファクトも不安定アクションに変換され報酬シグナルとして有効

## 技術的詳細
- Executable Video Alignment (EVA): 強化学習ポストトレーニングフレームワーク
- 実ロボット軌跡でIDMを訓練、報酬モデルとして再利用
- 生成ビデオを誘導するアクションシーケンスで評価
- RoboTwinベンチマーク + 実双腕ロボットで検証

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17808)
- [PDF](https://arxiv.org/pdf/2603.17808)
- [Project](https://eva-project-page.github.io/)
