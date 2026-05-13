---
layout: paper
title: "VECA: Elastic Attention Cores for Scalable Vision Transformers"
date: 2026-05-14
category: cs.CV
arxiv_id: "2605.12491"
url: https://arxiv.org/abs/2605.12491
authors:
  - Alan Z. Song
  - Yinjie Chen
  - Mu Nan
tags: [vision-transformer, attention, efficiency, scalable, high-resolution]
---

# VECA: Elastic Attention Cores for Scalable Vision Transformers

## 概要

Vision Transformer（ViT）の計算コストが解像度に対して二乗スケールするという基本的制約に挑戦。パッチ間の全対全注意が必要という仮定を覆し、**直接パッチ間インタラクションなしでも効果的な視覚表現が学習可能**であることを実証。

VECA（Visual Elastic Core Attention）はElastic Attention Coresを用いて高解像度ドメインでのViTスケーリングを可能にする新しいビジョントランスフォーマー。

## 選定理由

- Vision Transformerの効率化という重要研究トレンド
- 高解像度ViTの実用的課題への取り組み
- 注意機構の根本的仮定を覆す理論的貢献

## キーポイント

- **挑戦**: 全対全自己注意の二乗コストが高解像度で問題
- **発見**: パッチ間直接インタラクションなしでも豊かな表現学習が可能
- **手法**: Elastic Attention Coresによる効率的視覚表現

## arXiv

https://arxiv.org/abs/2605.12491
