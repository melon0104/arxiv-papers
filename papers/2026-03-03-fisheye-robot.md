---
layout: paper
title: "Rethinking Camera Choice: An Empirical Study on Fisheye Camera Properties in Robotic Manipulation"
date: 2026-03-03
arxiv_id: "2603.02139"
arxiv_url: "https://arxiv.org/abs/2603.02139"
pdf_url: "https://arxiv.org/pdf/2603.02139"
authors: ["Han Xue", "Nan Min", "Xiaotong Liu", "Wendi Chen", "Yuan Fang", "Jun Lv", "Cewu Lu", "Chuan Wen"]
categories: ["cs.RO", "cs.CV"]
venue: "CVPR 2026"
---

## 一言まとめ

**CVPR 2026**: ロボットマニピュレーションにおけるフィッシュアイカメラ特性の初の包括的実証研究。広視野角(FoV)の採用がポリシー学習に与える下流効果を系統的に分析。

## 概要

ロボットマニピュレーションにおけるフィッシュアイカメラの採用は、その非常に広い視野角(FoV)によって急速に進んでいるが、ポリシー学習への下流効果についての系統的な理解は遅れている。

### 研究の位置づけ

本論文は、このギャップを埋める**初の包括的実証研究**を提示。手首装着フィッシュアイカメラの模倣学習への特性を厳密に分析。

### 研究課題

シミュレーションと実世界の両方で広範な実験を通じ、3つの重要な研究課題を調査：

1. **FoVの効果**: 広視野角がポリシー性能に与える影響
2. **歪みの効果**: フィッシュアイ特有の歪みがどのように学習に影響するか
3. **最適な設定**: ロボットマニピュレーションタスクでの推奨構成

## 所感

ロボティクスにおけるセンサー選択の実証研究として貴重。フィッシュアイカメラのトレードオフ（広FoV vs 歪み）の定量的な理解は、実システム設計に直結する知見。
