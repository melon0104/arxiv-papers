---
layout: default
title: "Abstraction as a Memory-Efficient Inductive Bias for Continual Learning"
---

# Abstraction as a Memory-Efficient Inductive Bias for Continual Learning

[arXiv:2603.17198](https://arxiv.org/abs/2603.17198) | cs.LG

## 著者
Elnaz Rahmati et al.

## 一言まとめ
構造的抽象化を継続学習の**メモリフリー帰納バイアス**として活用。リプレイバッファ不要で強力なER(Experience Replay)ベースラインと同等以上の性能を達成。

## 概要
実世界は非定常かつ無限に複雑であり、知的エージェントはゼロからの再訓練という法外なコストなしに継続的に学習する必要がある。オンライン継続学習はこの設定のフレームワークを提供するが、新情報の学習は既獲得知識と干渉し、忘却と汎化劣化を引き起こす。Abstraction-Augmented Training (AAT)は、例間で共有される潜在的関係構造を捉えるようモデルを促すロスレベル修正。

## 注目ポイント
- **メモリゼロ**: リプレイバッファ完全不要
- **最小限の変更**: 訓練目的への僅かな修正のみ
- **ERと同等以上**: 強力なExperience Replayベースラインと比較
- **抽象化の多面性**: 関係データセット（エンティティマスキング）とナラティブデータセット（共有諺）で評価

## 技術的詳細
- 具体インスタンスとその抽象表現の両方で同時最適化
- 厳密なオンラインデータストリームで学習を安定化
- 2つのベンチマーク: 制御された関係データセット + ナラティブデータセット

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17198)
- [PDF](https://arxiv.org/pdf/2603.17198)
