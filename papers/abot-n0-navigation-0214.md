---
layout: paper
title: "ABot-N0: 汎用具現化ナビゲーションのためのVLA基盤モデル"
---

# ABot-N0: Technical Report on the VLA Foundation Model for Versatile Embodied Navigation

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11598
- **カテゴリ**: cs.RO, cs.AI, cs.CV
- **著者**: Zedong Chu, Shichao Xie et al. (AMAP-CVLab)
- **投稿日**: 2026-02-12
- **プロジェクト**: https://amap-cvlab.github.io/ABot-Navigation/ABot-N0/

## 選定理由
✅ **大規模データセット**: 1,690万エキスパート軌跡、500万推論サンプル
✅ **統一アーキテクチャ**: 5つのコアタスクを単一モデルで統合

## 概要
具現化ナビゲーションは長らくタスク固有アーキテクチャにより断片化されてきた。ABot-N0は5つのコアタスク（Point-Goal、Object-Goal、Instruction-Following、POI-Goal、Person-Following）を統合する「Grand Unification」を達成するVLA基盤モデル。

## 技術的貢献
- **Brain-Actionアーキテクチャ**: LLMベースのCognitive Brainによる意味推論 + Flow MatchingベースのAction Expertによる連続軌跡生成
- **ABot-N0 Data Engine**: 7,802の高忠実度3Dシーン（10.7 km²）から1,690万エキスパート軌跡と500万推論サンプルをキュレーション
- **Agentic Navigation System**: 階層的トポロジカルメモリを持つプランナーにより、動的な実世界環境での頑健な長期ミッションを実現

## 実験結果
- 7つのベンチマークで新SOTA性能
- 専門モデルを大幅に上回る

## 所感
ナビゲーションの「Grand Unification」を実現する野心的なプロジェクト。大規模データエンジンと階層的アーキテクチャの組み合わせが鍵。
