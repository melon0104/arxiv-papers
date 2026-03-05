---
layout: paper
title: "GarmentPile++: Affordance-Driven Cluttered Garments Retrieval"
date: 2026-03-05
categories: [cs.RO, cs.AI]
---

# GarmentPile++: Affordance-Driven Cluttered Garments Retrieval with Vision-Language Reasoning

**arXiv**: [2603.04158](https://arxiv.org/abs/2603.04158)  
**採択**: ICRA 2026  
**プロジェクト**: https://garmentpile2.github.io/

## 著者
Mingleyang Li, Yuran Wang, Yue Chen, Tianxing Chen, Jiaqi Liang, Zishun Shen, Haoran Lu, Ruihai Wu, Hao Dong

## 一言まとめ
VLM推論×視覚アフォーダンスで積み重なった衣類から安全に1枚取り出し。言語指示に従い、**SAM2セグメンテーション+双腕協調**で下流タスク対応。

## 概要
衣類操作は家庭用ロボットで重要だが、既存研究は単一衣類を仮定。実世界では積み重なった衣類が一般的で、1回の試行で正確に1枚を取り出す必要がある。

### 主要な技術貢献
1. **VLM reasoning + Visual affordance**: 高レベル推論とlow-levelアクションの統合
2. **SAM2 segmentation**: 衣類パイル上のオブジェクトセグメンテーション、VLM推論の視覚的手がかり
3. **Mask fine-tuning mechanism**: 初期セグメンテーションが最適でない場合の対処
4. **Dual-arm cooperation**: 大型/長い衣類、過度の垂れ下がりへの対応

### 実験結果
- 実世界・シミュレーション両方で有効性を実証
- 多様なタスク・シナリオで一貫した性能
- 下流タスク（畳み、掛け、着用）への堅牢な基盤

## キーワード
Garment Manipulation, VLM, Dual-arm, Affordance, ICRA

## 選定理由
- ICRA 2026採択
- VLM×ロボティクスの実用応用
- 実世界検証済み
