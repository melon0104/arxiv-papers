---
layout: paper
title: "PerpetualWonder: Long-Horizon Action-Conditioned 4D Scene Generation"
date: 2026-02-06
arxiv_id: "2602.04876"
categories: ["cs.CV"]
project: "https://johnzhan2023.github.io/PerpetualWonder/"
---

# PerpetualWonder: 4D Scene Generation

**arXiv**: https://arxiv.org/abs/2602.04876

**Project**: https://johnzhan2023.github.io/PerpetualWonder/

## 概要

単一画像から長期的・アクション条件付きの4Dシーン生成を可能にするハイブリッド生成シミュレータ「PerpetualWonder」を提案。

## 問題意識

既存手法の失敗原因:
- **物理状態と視覚表現の分離**: 生成的refinementが後続インタラクションのための物理を更新できない

## 提案手法

### 初の真のクローズドループシステム

**統一表現（Unified Representation）**:
- 物理状態と視覚プリミティブの**双方向リンク**を確立
- 生成的refinementがダイナミクスと外見の**両方**を修正可能

**堅牢な更新機構**:
- 複数視点からの教師信号を収集
- 最適化の曖昧性を解消

## 実験結果

- 単一画像から**複雑なマルチステップインタラクション**をシミュレート
- 長期的アクションからの物理的妥当性と視覚的一貫性を維持

## 所感

World Modelの文脈で「生成と物理の乖離」は本質的な問題。PerpetualWonderは統一表現で両者を繋ぐ重要な一歩。ロボティクスへの応用も期待される。
