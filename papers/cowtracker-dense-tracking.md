---
layout: paper
title: "CoWTracker: Tracking by Warping instead of Correlation"
date: 2026-02-06
arxiv_id: "2602.04877"
categories: ["cs.CV"]
project: "http://cowtracker.github.io"
---

# CoWTracker: Dense Point Tracking by Warping

**arXiv**: https://arxiv.org/abs/2602.04877

**Project**: http://cowtracker.github.io

## 概要

Cost volumeを使わずにwarpingベースで密な点追跡を行う新手法「CoWTracker」を提案。

## 問題意識

- 最新の追跡手法はcost volumeによる特徴マッチングに依存
- **空間解像度に対して2乗の計算量**→スケーラビリティと効率性に限界

## 提案手法

光学フローの進歩にインスパイア:
- 現在の推定に基づいてターゲットフレームからクエリフレームへ特徴を**warp**
- **反復的に洗練**
- Transformerアーキテクチャで全トラックに対する時空間的推論を共同実行
- **特徴相関を計算せずに**長距離対応を確立

## 実験結果

### Dense Point Tracking
- TAP-Vid-DAVIS: **SOTA**
- TAP-Vid-Kinetics: **SOTA**
- Robo-TAP: **SOTA**

### Optical Flow（副次的成果）
- Sintel, KITTI, Spring: 専門手法を**上回る**こともある

## 意義

Warpingベースアーキテクチャが**密な点追跡と光学フロー推定を統一**できる可能性を示す

## 所感

Cost volumeからの脱却という設計選択が功を奏した好例。シンプルな発想でSOTAを達成し、2つのタスクを統一するポテンシャルも興味深い。
