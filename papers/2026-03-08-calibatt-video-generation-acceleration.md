---
layout: paper
title: "CalibAtt: Accelerating Text-to-Video Generation with Calibrated Sparse Attention"
date: 2026-03-08
categories: [cs.CV]
---

# CalibAtt: Accelerating Text-to-Video Generation with Calibrated Sparse Attention

- **arXiv**: [2603.05503](https://arxiv.org/abs/2603.05503)
- **著者**: Shai Yehezkel et al.

## 概要

動画生成Diffusionモデルの高速化手法。時空間アテンションがボトルネックとなっている問題に対し、訓練不要のキャリブレートされたスパースアテンションを提案。

## 主な発見

- トークン間接続の大部分は一貫して無視できるスコアを生成
- これらのパターンは入力間で繰り返される
- ブロックレベルのスパース性と繰り返しパターンを利用可能

## 技術的詳細

1. **オフラインキャリブレーション**: ブロックレベルのスパース性・繰り返しパターンを特定
2. **最適化されたアテンション操作にコンパイル**: レイヤー、ヘッド、拡散タイムステップごと
3. **ハードウェア効率的なスキップ**: 選択された入力依存接続のみ密に計算

## 実験結果

- **Wan 2.1 14B, Mochi 1** など大規模モデルで評価
- **最大1.58倍のエンドツーエンド高速化**
- 動画生成品質とテキスト-動画整合性を維持

## 注目ポイント

- 訓練不要で既存モデルに適用可能
- 大規模商用モデルでの実証
- 既存の訓練不要手法を上回る性能
