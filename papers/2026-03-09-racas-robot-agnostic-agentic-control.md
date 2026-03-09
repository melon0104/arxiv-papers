---
layout: paper
title: "RACAS: Controlling Diverse Robots With a Single Agentic System"
date: 2026-03-09
categories: [cs.RO, cs.AI, cs.CL, cs.LG, cs.MA]
arxiv_id: "2603.05621"
---

# RACAS: Controlling Diverse Robots With a Single Agentic System

## 基本情報
- **arXiv ID**: 2603.05621
- **カテゴリ**: cs.RO, cs.AI, cs.CL, cs.LG, cs.MA
- **投稿日**: 2026-03-09

## 著者
Dylan R. Ashley, Jan Przepióra, Yimeng Chen, Ali Abualsaud, Nurzhan Yesmagambet, Shinkyu Park, Eric Feron, Jürgen Schmidhuber

## 概要
多くのロボットプラットフォームは外部ソフトウェアがアクチュエータを指令しセンサを読み取るAPIを公開。しかし、これらの低レベルインターフェースから高レベルの自律行動への移行には、異なる専門分野を要求するコンポーネントを持つ複雑なパイプラインが必要。

既存アプローチはエンボディメントごとの再トレーニングが必要か、構造的に類似したプラットフォーム間でのみ検証されている。

**RACAS (Robot-Agnostic Control via Agentic Systems)** を導入：3つのLLM/VLMベースモジュール（Monitors、Controller、Memory Curator）が自然言語のみで通信し、閉ループロボット制御を提供する協調エージェントアーキテクチャ。

## 技術的詳細
RACASが必要とするのは：
- ロボットの自然言語記述
- 利用可能アクションの定義
- タスク仕様

**変更不要**：ソースコード、モデル重み、報酬関数

プラットフォーム間移動時に修正なしで動作。

## 主要結果
3種類の根本的に異なるプラットフォームで評価：
- 車輪付き地上ロボット
- 最近発表された新しい多関節ロボットリム
- 水中車両

RACASは**すべてのプラットフォームで割り当てられたすべてのタスクを一貫して解決**。

## 実用的意義
- ロボットソリューションのプロトタイピング障壁を大幅に低減
- 単一システムで多様なロボットを制御
- 自動化のプログラミングなしでの実現可能性
- 新規ロボットプラットフォームへの即座の適用

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05621
