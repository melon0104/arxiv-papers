---
layout: paper
title: "SafeFlowMPC: Predictive and Safe Trajectory Planning with Learning-based Policies"
date: 2026-02-17
arxiv_id: "2602.12794"
category: cs.RO
tags: [robotics, mpc, flow-matching, safety, icra-2026, github]
---

# SafeFlowMPC: Predictive and Safe Trajectory Planning for Robot Manipulators with Learning-based Policies

## 基本情報
- **arXiv**: [2602.12794](https://arxiv.org/abs/2602.12794)
- **採択**: ICRA 2026
- **GitHub**: [TU-Wien-ACIN-CDS/SafeFlowMPC](https://github.com/TU-Wien-ACIN-CDS/SafeFlowMPC)
- **デモ動画**: [acin.tuwien.ac.at/42d6](http://www.acin.tuwien.ac.at/42d6)
- **著者**: Thies Oelerich, Gerald Ebmer, Christian Hartl-Nesic, Andreas Kugi
- **機関**: TU Wien

## 🏆 ICRA 2026 採択

## 一言まとめ
Flow MatchingとオンラインMPCを組み合わせ、学習の柔軟性と最適化の安全保証を両立するロボット軌道計画フレームワーク。

## 課題
- 日常環境でのロボット統合には柔軟性とリアルタイム反応性が必要
- 学習ベース手法：強力だが解釈性と安全保証が欠如
- 最適化ベース手法：保証はあるが柔軟性・汎化能力が不足

## 提案手法: SafeFlowMPC
### Flow Matching + オンライン最適化
- 学習と最適化の強みを組み合わせ
- **常時安全性を保証**
- 劣最適MPC定式化でリアルタイム実行

## 実験結果
### KUKA 7-DoFマニピュレータ（3つの実世界タスク）
1. グラスピング実験（2種）
2. 動的人間-ロボット物体受け渡し

### 性能
- 強力な性能を達成
- 実行速度を犠牲にしない

## キーポイント
- 学習と最適化のハイブリッドアプローチ
- 安全保証付きの柔軟な制御
- ICRA 2026採択とコード公開で信頼性・再現性を確保
