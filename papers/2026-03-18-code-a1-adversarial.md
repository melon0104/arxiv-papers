---
layout: paper
title: "Code-A1: Adversarial Co-Evolution of Code LLM and Test LLM"
date: 2026-03-18
arxiv_id: "2603.15611"
categories: ["cs.CL"]
importance: "★★★"
---

# Code-A1: Adversarial Evolving of Code LLM and Test LLM via Reinforcement Learning

## 基本情報
- **arXiv ID**: 2603.15611
- **タイトル**: Code-A1: Adversarial Evolving of Code LLM and Test LLM via Reinforcement Learning
- **著者**: Aozhe Wang et al.
- **投稿日**: 2026-03-16
- **分野**: cs.CL
- **コード**: https://github.com/ZJU-REAL/Code-A1
- **プロジェクトページ**: https://zju-real.github.io/Code-A1

## 概要
コード生成のための強化学習において、Code LLMとTest LLMを敵対的に共進化させるフレームワークCode-A1を提案。単一モデルでの自己対戦における「自己共謀」（簡単なテストを生成して報酬を得る）問題を、モデル分離により解決。

## 技術的貢献
- **敵対的共進化**: Code LLMは「より多くのテストをパス」、Test LLMは「より多くの欠陥を発見」という相反する目的で最適化
- **ホワイトボックステスト生成**: Test LLMがCode LLMの候補コードを検査し、ターゲットを絞った敵対的テストを生成
- **Mistake Book**: 経験リプレイ機構で過去の失敗パターンを活用
- **複合報酬**: テストの有効性と敵対的難易度をバランス

## 実験結果
- Qwen2.5-Coderモデルで検証
- 人間アノテーションテストで訓練したモデルと同等以上のコード生成性能
- テスト生成能力も大幅に向上

## 意義
自己対戦の共謀リスクなしにホワイトボックステスト生成を可能にする新アーキテクチャ。コード生成の品質保証に新たなアプローチを提示。
