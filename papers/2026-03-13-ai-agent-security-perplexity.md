---
layout: paper
title: "Security Considerations for Artificial Intelligence Agents"
date: 2026-03-13
arxiv_id: "2603.12230"
categories: [cs.LG, cs.AI, cs.CR]
---

# Security Considerations for AI Agents

## 基本情報
- **arXiv ID**: 2603.12230
- **カテゴリ**: cs.LG, cs.AI, cs.CR
- **投稿日**: 2026年3月12日
- **注目ポイント**: 🏢 **Perplexity** (NIST/CAISI RFI対応)

## 概要
Perplexityによる、フロンティアAIエージェントのセキュリティに関する包括的分析。数百万ユーザー・数千企業での運用経験に基づく。

## 主要な攻撃表面
1. **ツール・コネクタ**: 外部システムとの接続点
2. **ホスティング境界**: 権限の分離
3. **マルチエージェント協調**: カスケード障害

## 特に重要な脅威
- **間接プロンプトインジェクション**
- **Confused-deputy問題**: 権限の混同
- **長時間ワークフローでのカスケード障害**

## 防御の階層スタック
1. 入力レベルの緩和
2. モデルレベルの緩和
3. サンドボックス化された実行
4. 高影響アクションへの決定論的ポリシー強制

## 今後の課題
- 適応型セキュリティベンチマーク
- 委任・権限制御のポリシーモデル
- セキュアなマルチエージェントシステム設計ガイダンス

## リンク
- [arXiv](https://arxiv.org/abs/2603.12230)
- [PDF](https://arxiv.org/pdf/2603.12230)
