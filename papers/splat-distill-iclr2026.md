---
layout: paper
title: "Splat and Distill: 3D認識蒸留"
date: 2026-02-07
arxiv_id: "2602.06032"
categories: [cs.CV, 3D Vision]
---

# Splat and Distill: Augmenting Teachers with Feed-Forward 3D Reconstruction For 3D-Aware Distillation

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06032
- **著者**: David Shavin, Sagie Benaim
- **採択**: **ICLR 2026**
- **プロジェクト**: https://davidshavin4.github.io/Splat-and-Distill/

## 概要
高速フィードフォワード3D再構成パイプラインで教師モデルを拡張し、2D VFMに**堅牢な3D認識**を注入するフレームワーク。

## 技術的ポイント
- **3D Gaussian表現への特徴リフティング**: フィードフォワードで実現
- **新視点への"Splat"**: 新しい2D特徴マップを生成
- **動的学習プロセス**: 教師の一貫性が学生とともに向上

## 従来手法との違い
- per-scene最適化を排除
- 特徴平均化アーティファクトを回避
- 遅いper-scene最適化からフィードフォワード方式へ移行

## 実験結果
以下のタスクで大幅改善:
- 単眼深度推定
- 表面法線推定
- マルチビュー対応
- セマンティックセグメンテーション

## 注目ポイント
- **ICLR'26採択**
- 3D認識と2Dセマンティクスの両方を向上
- Vision Foundation Modelsの3D拡張手法として汎用的
