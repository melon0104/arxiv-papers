---
layout: paper
title: "MiroThinker-1.7 & H1: Heavy-Duty Research Agents via Verification"
date: 2026-03-19
arxiv_id: "2603.15726"
categories: ["cs.CL", "cs.AI", "cs.IR", "cs.LG"]
---

# MiroThinker-1.7 & H1: Towards Heavy-Duty Research Agents via Verification

## 基本情報

| 項目 | 内容 |
|------|------|
| arXiv | [2603.15726](https://arxiv.org/abs/2603.15726) |
| 組織 | MiroMind Team |
| オープンソース | MiroThinker-1.7, MiroThinker-1.7-mini 公開 |

## 概要

複雑な長期推論タスク向けの新しいリサーチエージェント**MiroThinker-1.7**と、重負荷推論機能を追加した**MiroThinker-H1**を提案。検証機構を推論プロセスに統合。

## MiroThinker-1.7

### エージェント中間訓練ステージ
- 構造化された計画立案
- コンテキスト推論
- ツールインタラクション

### 効果
- より効果的な多段階インタラクション
- 複雑なタスク全体での持続的な推論

## MiroThinker-H1 (Heavy-Duty)

### ローカルレベル検証
- 中間推論決定を推論中に評価・改善
- リアルタイムの軌道修正

### グローバルレベル検証
- 全体の推論軌跡を監査
- 最終回答が一貫した証拠チェーンに裏付けられているかを確認

## 主要な結果

| ベンチマーク | 性能 |
|------------|------|
| オープンWeb研究 | **SOTA** |
| 科学推論 | SOTA |
| 金融分析 | SOTA |
| 専門ドメイン | 強い結果 |

## 技術的貢献

1. 検証を推論プロセスに統合した新しいアーキテクチャ
2. ローカル・グローバル両レベルでの信頼性保証
3. 競争力のある効率で研究エージェント機能を提供

## オープンソース

- **MiroThinker-1.7**: フルサイズモデル
- **MiroThinker-1.7-mini**: 軽量版

両モデルともオープンソースで公開。

## 意義

深層研究タスクでの信頼性の高い推論を実現。検証機構がLLMエージェントの品質保証に重要であることを実証。
