---
layout: paper
title: "EAAE: Energy-Aware Autonomous UAV Exploration"
date: 2026-03-18
arxiv_id: "2603.15604"
categories: ["cs.RO"]
importance: "★★☆"
---

# EAAE: Energy-Aware Autonomous Exploration for UAVs in Unknown 3D Environments

## 基本情報
- **arXiv ID**: 2603.15604
- **タイトル**: EAAE: Energy-Aware Autonomous Exploration for UAVs in Unknown 3D Environments
- **著者**: Moji Shi et al.
- **投稿日**: 2026-03-16
- **分野**: cs.RO

## 概要
バッテリー駆動マルチローターUAVの探索ミッションにおいて、カバレッジや時間だけでなくエネルギーを明示的な意思決定変数として組み込むフレームワークEAAE (Energy-Aware Autonomous Exploration)を提案。

## 技術的貢献
- **フロンティアベースモジュラーアーキテクチャ**: エネルギーを明示的にフロンティア選択に統合
- **ビュー整合領域クラスタリング**: フロンティアを一貫した視点領域にグループ化
- **動的実行可能軌跡計画**: 最も情報量の多いクラスタへの候補軌跡を計画
- **オフライン電力推定**: 軌跡の実行エネルギーを予測
- **二層計画アーキテクチャ**: 安全な実行のための探索進捗とエネルギー最小化のバランス

## 実験結果
- ローター回転速度ベースの電力モデルで複雑な3Dシミュレーション環境を評価
- 距離ベース・情報ゲインベースのベースラインと比較
- **総エネルギー消費を一貫して削減**
- 探索時間と地図品質は競争力を維持

## 意義
フロンティア探索へのエネルギー認識レイヤーをドロップインで追加可能な実用的アプローチを提示。
