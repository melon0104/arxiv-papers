---
layout: default
title: "Pixel-level Counterfactual Contrastive Learning for Medical Image Segmentation"
---

# Pixel-level Counterfactual Contrastive Learning for Medical Image Segmentation

[arXiv:2603.17110](https://arxiv.org/abs/2603.17110) | cs.CV

## 著者
Raghav Mehta et al.

## 一言まとめ
**ISBI-2026 口頭発表**。反事実生成と密対照学習を組み合わせた医療画像セグメンテーション。Silver-standard注釈活用で**~94% DSC**達成。

## 概要
画像セグメンテーションは大規模注釈データセットに依存するが、これらは高価で作成に時間がかかる。Silver-standard（AI生成）ラベルは取得しやすいがバイアス導入リスクがある。自己教師あり学習は事前学習に重要だが、対照学習と反事実生成を組み合わせた最近の研究は分類向けであり、ピクセルレベルタスクへの拡張は容易でない。本研究はDual-View (DVD-CL)とMulti-View (MVD-CL)手法を提案。

## 注目ポイント
- **ISBI-2026 口頭発表採択**
- **注釈不要版**: DVD-CLは他の密対照学習手法を上回る
- **Silver-standard活用**: 直接訓練より高性能
- **新可視化手法**: Color-coded High Resolution Overlay map (CHRO-map)導入

## 技術的詳細
- 反事実生成 + 密対照学習パイプライン
- DVD-CL: Dual-View密対照学習（注釈不要）
- MVD-CL: Multi-View密対照学習
- 教師あり変種: silver-standard注釈を活用

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17110)
- [PDF](https://arxiv.org/pdf/2603.17110)
