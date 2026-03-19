---
layout: default
title: "MHPO: Modulated Hazard-aware Policy Optimization for Stable Reinforcement Learning"
---

# MHPO: Modulated Hazard-aware Policy Optimization for Stable Reinforcement Learning

[arXiv:2603.16929](https://arxiv.org/abs/2603.16929) | cs.LG

## 著者
Hongjun Wang et al.

## 一言まとめ
GRPOベースフレームワークの訓練安定性を改善する**ハザード認識ポリシー最適化**。テキスト・VL両タスクで既存手法を一貫して上回る。

## 概要
GRPO系フレームワークでは重要度比の制御が訓練安定性に重要だが、ハードクリッピング等の従来手法は非微分可能境界と勾配消失領域に苦しむ。MHPOはLog-Fidelity Modulator (LFM)で無界重要度比を有界微分可能領域にマップし、Decoupled Hazard Penalty (DHP)で生存分析の累積ハザード関数を活用して正負のポリシーシフトを独立に制御。

## 注目ポイント
- **勾配忠実性維持**: LFMで高分散外れ値トークンの損失ランドスケープ不安定化を防止
- **非対称シフト制御**: 過膨張によるモード崩壊と壊滅的収縮によるポリシー侵食を同時緩和
- **包括的評価**: テキストベース・VLタスクの多様な推論ベンチマークで優位性実証
- **訓練安定性向上**: 安定化された信頼領域内での最適化

## 技術的詳細
- Log-Fidelity Modulator (LFM): 重要度比を有界微分可能領域にマップ
- Decoupled Hazard Penalty (DHP): 生存分析からの累積ハザード関数で非対称ペナルティ
- グローバル勾配安定性を確保しつつきめ細かい制御を実現

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.16929)
- [PDF](https://arxiv.org/pdf/2603.16929)
