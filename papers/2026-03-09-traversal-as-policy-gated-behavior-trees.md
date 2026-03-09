---
layout: paper
title: "Traversal-as-Policy: Log-Distilled Gated Behavior Trees as Externalized, Verifiable Policies for Safe, Robust, and Efficient Agents"
date: 2026-03-09
categories: [cs.LG, cs.AI, cs.CR, cs.SE]
arxiv_id: "2603.05517"
---

# Traversal-as-Policy: Log-Distilled Gated Behavior Trees as Externalized, Verifiable Policies for Safe, Robust, and Efficient Agents

## 基本情報
- **arXiv ID**: 2603.05517
- **カテゴリ**: cs.LG, cs.AI, cs.CR, cs.SE
- **投稿日**: 2026-03-09

## 著者
Peiran Li, Jiashuo Sun, Fangzhou Lin, Shuo Xing, Tianfu Fu, Suofei Feng, Chaoqun Ni, Zhengzhong Tu

## 概要
自律型LLMエージェントが失敗する理由は、長期的なポリシーがモデルの重みとトランスクリプトに暗黙的に残り、安全性が後付けで追加されるから。

**Traversal-as-Policy**を提案：サンドボックス化されたOpenHands実行ログを単一の実行可能な**Gated Behavior Tree (GBT)** に蒸留し、タスクがカバレッジ内にある場合は制約のない生成ではなく**木のトラバーサル**を制御ポリシーとして扱う。

## 技術的詳細
各ノードは成功した軌跡からマイニング・マージチェックされた状態条件付きアクションマクロをエンコード。unsafe tracesに関与したマクロは、構造化ツールコンテキストと制限された履歴に対する決定論的事前実行ゲートを付加。

ランタイムでは：
- 軽量トラバーサーがベースモデルの意図を子マクロにマッチ
- グローバルおよびノードローカルゲーティング下で一度に1つのマクロを実行
- スタック時はリスク認識最短経路回復を実行
- 訪問パスがトランスクリプトリプレイを置き換えるコンパクトなスパインメモリを形成

## 主要結果
統一OpenHandsサンドボックスで15+のソフトウェア、Web、推論、安全性/セキュリティベンチマークで評価：

**SWE-bench Verified (Protocol A, 500 issues)**:
- 成功率: 34.6% → **73.6%**
- 違反率: 2.8% → **0.2%**
- トークン/文字使用量: 208k/820k → **126k/490k**

**8B executorsで同じ蒸留木使用時**:
- SWE-bench Verified: 14.0% → **58.8%** (4倍以上)
- WebArena: 9.1% → **37.3%** (4倍以上)

## 実用的意義
- 安全でコスト効率の良いLLMエージェント
- 外部化された検証可能なポリシー
- 小規模モデルでの大幅な性能向上
- セキュリティクリティカルなソフトウェア開発タスク

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05517
