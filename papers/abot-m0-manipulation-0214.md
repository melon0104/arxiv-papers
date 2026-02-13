---
layout: paper
title: "ABot-M0: ロボット操作のためのVLA基盤モデル"
---

# ABot-M0: VLA Foundation Model for Robotic Manipulation with Action Manifold Learning

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11236
- **カテゴリ**: cs.CV, cs.CL, cs.RO
- **著者**: Yandan Yang, Shuang Zeng et al. (AMAP-CVLab)
- **投稿日**: 2026-02-11
- **プロジェクト**: https://amap-cvlab.github.io/ABot-Manipulation/
- **GitHub**: https://github.com/amap-cvlab/ABot-Manipulation

## 選定理由
✅ **コード公開**: GitHubでコード・パイプライン公開
✅ **大規模データセット**: 600万軌跡、9,500時間のデータ

## 概要
「一つの脳、多様な形態」パラダイムにおける汎用具現化エージェント構築の課題に取り組む。断片化されたデータ、一貫性のない表現、訓練目的のミスアライメントが進捗を妨げている。

## 技術的貢献
- **ABot-M0フレームワーク**: 体系的なデータキュレーションパイプラインとモデルアーキテクチャ・訓練戦略の同時最適化
- **UniACT-dataset**: 6つの公開データセットから600万以上の軌跡、9,500時間、多様なロボット形態とタスクシナリオ
- **Action Manifold Hypothesis**: 効果的なロボット動作は低次元の滑らかなマニフォールド上に存在
- **Action Manifold Learning (AML)**: DiTバックボーンで連続的な動作シーケンスを直接予測

## 実験結果
- 統一事前訓練によりプラットフォーム・タスク間の知識転移と汎化が向上
- コンポーネントは独立動作し、付加的な利点を提供

## 所感
「一つの脳、多様な形態」の実現に向けた重要な一歩。Action Manifold Hypothesisは物理法則とタスク制約を活用した効率的な設計。
