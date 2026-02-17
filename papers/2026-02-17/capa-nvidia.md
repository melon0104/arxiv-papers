# CAPA: Depth Completion as Parameter-Efficient Test-Time Adaptation

## 基本情報
- **arXiv**: [2602.14751](https://arxiv.org/abs/2602.14751)
- **カテゴリ**: cs.CV
- **投稿日**: 2026-02-16
- **著者**: Bingxin Ke, Qunjie Zhou, et al., Laura Leal-Taixé, Shengyu Huang (NVIDIA)
- **プロジェクト**: research.nvidia.com/labs/dvl/projects/capa

## 概要
事前訓練済み3D基盤モデルをスパースな幾何情報で深度補完に適応させる**テストタイム最適化フレームワーク**。

## 技術的特徴
1. **Parameter-Efficient Fine-Tuning**: LoRAやVPTで最小限のパラメータのみ更新
2. **基盤モデルの幾何事前知識を活用**: 歪みや誤配置構造を補正
3. **シーケンスレベルパラメータ共有**: 動画の全フレームを同時適応
4. **時間相関の活用**: ロバスト性と多フレーム一貫性を向上
5. **モデル非依存**: 任意のViTベース基盤モデルと互換

## 主要結果
- 屋内・屋外データセットの両方でSOTA達成
- 多様な条件パターンに対応

## 注目ポイント
🎯 **NVIDIA**による3D基盤モデル活用の実用的手法、深度補完タスクのパラダイムシフト
