# TaTa: Training-Free Test-Time Adaptation with Brownian Distance Covariance

**arXiv**: [2601.23253](https://arxiv.org/abs/2601.23253)  
**カテゴリ**: cs.CV, cs.LG  
**採択**: ICASSP 2026  

## 概要

ブラウン距離共分散を活用した、訓練不要のVision-Language Modelテスト時適応手法。

## 問題設定

Vision-Language Models (VLM) の課題:
- ドメインシフト下で性能低下
- 既存のテスト時適応手法は計算コストが高く、バックプロパゲーション依存

## TaTaの手法

**Brownian Distance Covariance (BDC)**:
- ペアワイズ距離を介して線形・非線形依存性を捕捉する強力な統計的尺度
- 訓練やバックプロパゲーションなしでVLMを新ドメインに動的適応

**主要コンポーネント**:
1. **属性強化プロンプティング**: 記述的視覚キューでVL推論を改善
2. **動的クラスタリング**: 新しい視覚コンテキストへの再較正
3. **疑似ラベル精緻化**: 適応の安定性向上

## 結果

- **計算コスト**: 大幅削減
- **性能**: ドメイン一般化・クロスデータセット一般化でSOTA

## 一言

**ブラウン距離共分散で訓練不要のVLM適応、効率と性能を両立**
