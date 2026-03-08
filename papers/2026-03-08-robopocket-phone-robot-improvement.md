---
layout: paper
title: "RoboPocket: Improve Robot Policies Instantly with Your Phone"
date: 2026-03-08
categories: [cs.RO, cs.AI, cs.LG]
---

# RoboPocket: Improve Robot Policies Instantly with Your Phone

- **arXiv**: [2603.05504](https://arxiv.org/abs/2603.05504)
- **著者**: Wendi Chen et al.
- **プロジェクト**: https://robo-pocket.github.io

## 概要

スマートフォンを使用したRobot-Free Instant Policy Iterationを実現するポータブルシステム。リモート推論とARビジュアルフォーサイトにより、物理ロボットなしでポリシーの弱点を特定し、効率的なデータ収集が可能。

## 主な貢献

1. **Remote Inference Framework**: ARビジュアルフォーサイトでポリシーの予測軌道を可視化
2. **非同期Online Finetuning**: 新着データでポリシーを継続的に更新、数分で学習ループを閉じる
3. **分散収集対応**: 複数人での並列データ収集

## 実験結果

- **データスケーリング則に準拠**
- オフラインスケーリング戦略に比べ**データ効率2倍**
- 分散環境でも**サンプル効率2倍向上**

## 注目ポイント

- 消費者スマートフォン1台で実現
- 物理ロボット不要でポリシー改善
- 即時反復によるインタラクティブ学習
