---
layout: paper
title: "EvoScientist: Towards Multi-Agent Evolving AI Scientists for End-to-End Scientific Discovery"
date: 2026-03-10
categories: [cs.CL]
arxiv_id: "2603.08127"
---

# EvoScientist: Towards Multi-Agent Evolving AI Scientists for End-to-End Scientific Discovery

## 基本情報
- **arXiv ID**: 2603.08127
- **カテゴリ**: cs.CL
- **投稿日**: 2026-03-09

## 著者
Yougang Lyu, Xi Zhang, Xinhao Yi, Yuyue Zhao, Shuyu Guo, Wenxiang Hu, Jan Piotrowski, Jakub Kaliski, Jacopo Urbani, Zaiqiao Meng, Lun Zhou, Xiaohui Yan

## 概要
LLMの採用拡大により、AIサイエンティストがアイデア生成・実験実行など複雑なエンドツーエンド科学発見タスクを実行可能に。しかし、最先端システムの多くは**静的な手設計パイプライン**に依存し、蓄積されたインタラクション履歴に基づく適応に失敗。その結果、有望な研究方向を見落とし、失敗実験を繰り返し、実現不可能なアイデアを追求。

**EvoScientist**の提案：
- **永続的メモリ**と**自己進化**により研究戦略を継続的に改善
- 3つの専門エージェント：
  1. **Researcher Agent (RA)**: 科学的アイデア生成
  2. **Engineer Agent (EA)**: 実験実装・実行
  3. **Evolution Manager Agent (EMA)**: 過去のインタラクションから再利用可能な知識を蒸留

2つの永続メモリモジュール：
1. **Ideation Memory**: 実現可能な研究方向を要約、過去の失敗方向を記録
2. **Experimentation Memory**: 効果的なデータ処理・モデル訓練戦略を蓄積

## 主要結果
- 7つのオープンソース・商用SOTAシステムを上回る
- 自動・人間評価で新規性・実現可能性・関連性・明確さが向上
- マルチエージェント進化によりコード実行成功率が大幅改善

## 実用的意義
- 自律的科学研究の加速
- 研究戦略の継続的改善
- 失敗からの学習と知識蓄積

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08127
