---
layout: paper
title: "Safe-SAGE: Social-Semantic Adaptive Guidance for Safe Engagement"
date: 2026-03-08
categories: [cs.RO]
---

# Safe-SAGE: Social-Semantic Adaptive Guidance for Safe Engagement

- **arXiv**: [2603.05497](https://arxiv.org/abs/2603.05497)
- **著者**: Lizhi Yang et al.

## 概要

高レベルの意味理解と低レベルの安全クリティカル制御を橋渡しする統一フレームワーク。従来の安全クリティカル制御手法（Control Barrier Functions等）は「意味盲」であり、障害物の文脈的意味に関係なく同じ振る舞いを示す問題を解決。

## 主な貢献

1. **Poisson Safety Function (PSF)**: ラプラス誘導場で変調された安全関数
2. **マルチセンサー融合**: 点群とビジョンベースのインスタンスセグメンテーション・追跡を融合
3. **多層安全フィルタ**: MPC層とCBF層の両方でフラックス変調を利用

## 技術的詳細

- 環境内の異なる障害物に対して異なる保守性レベル
- 複数エージェントの通過規範
- カメラ視野外でも最新の意味論を維持

## 実験結果

- **四足歩行ロボットで実証**
- 意味的に豊かな動的環境でのナビゲーション
- 厳密な安全保証を維持しながらコンテキスト依存の安全マージン

## 注目ポイント

- セマンティクス認識型ロボット安全制御
- 理論的安全保証と実践的性能の両立
