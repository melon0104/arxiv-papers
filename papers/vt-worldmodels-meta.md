---
layout: paper
title: "Visuo-Tactile World Models: 触覚認識によるロボット操作"
date: 2026-02-07
arxiv_id: "2602.06001"
categories: [cs.RO, Manipulation]
---

# Visuo-Tactile World Models

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06001
- **著者**: Carolina Higuera, Sergio Arnaud, **Byron Boots** (UW), **Mustafa Mukadam** (Meta), **Francois Robert Hogan** (Meta), **Franziska Meier** (Meta)
- **機関**: **Meta AI Research**, University of Washington

## 概要
視覚と触覚を融合したマルチタスクWorld Models。**接触物理を触覚推論で捉え**、接触リッチなタスクでの計画を改善。

## Vision-onlyの失敗モード
- オクルージョン下での物体消失
- 物体のテレポーテーション
- 物理法則に反した動き

## 実験結果
| 指標 | 改善（vs vision-only） |
|------|----------------------|
| 物体永続性 | **+33%** |
| 運動法則遵守 | **+29%** |
| ゼロショット実機成功率 | **最大+35%** |

## 技術的ポイント
- 接触リッチな操作タスクセットで訓練
- 自己回帰ロールアウトでの物理的忠実度向上
- 新タスクへの下流適応性を実証

## 注目ポイント
- **Meta AI + UW Byron Boots研究室の共同研究**
- 触覚センシングのWorld Modelsへの統合
- 限られたデモからの効果的な適応
