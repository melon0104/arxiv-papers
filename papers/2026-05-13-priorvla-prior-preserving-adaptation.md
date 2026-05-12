# PriorVLA: Prior-Preserving Adaptation for Vision-Language-Action Models

- **arXiv ID**: 2605.10925
- **カテゴリ**: cs.RO (ロボティクス)
- **投稿日**: 2026-05-11
- **URL**: https://arxiv.org/abs/2605.10925

## 著者
Xinyu Guo, Bin Xie, Wei Chai, Xianchi Deng et al.

## 選定理由
✅ **技術的重要性**: VLAモデルのファインチューニング時の「事前学習知識の崩壊」問題への解決策
✅ **実用性**: 汎用ロボットマニピュレーションの精度向上に直結

## 概要
大規模事前訓練されたVLA（Vision-Language-Action）モデルはロボットマニピュレーションの汎用基盤として有望だが、ダウンストリームタスクへの適応が必要。フルファインチューニングは事前訓練知識（Prior）を損なう問題がある。PriorVLAは凍結Prior Expertと学習可能なTask Expertを組み合わせ、事前訓練知識を保ちながら効果的な適応を実現。

## 主要な貢献
1. **Prior Expert（凍結）**: 広汎な事前訓練知識を保護するモジュール
2. **Task Expert（学習可能）**: タスク固有の適応を担当するモジュール
3. **Dynamic Gating**: タスクに応じて両Expertの寄与を動的に調整
4. **効率的適応**: フルファインチューニングより少ないパラメータ更新で高性能

## 実験結果
- LIBERO・RLBench等の標準ベンチマークでフルファインチューニングを上回る
- 分布外タスクでの一般化能力が特に優秀

## インパクト
VLAモデルの実用的なロボット展開を加速。家庭用ロボットや産業用ロボットへの応用に期待。
