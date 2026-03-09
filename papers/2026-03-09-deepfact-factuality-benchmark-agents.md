---
layout: paper
title: "DeepFact: Co-Evolving Benchmarks and Agents for Deep Research Factuality"
date: 2026-03-09
categories: [cs.AI]
arxiv_id: "2603.05912"
---

# DeepFact: Co-Evolving Benchmarks and Agents for Deep Research Factuality

## 基本情報
- **arXiv ID**: 2603.05912
- **カテゴリ**: cs.AI (Artificial Intelligence)
- **投稿日**: 2026-03-09

## 著者
Yukun Huang, Leonardo F. R. Ribeiro, Momchil Hardalov, Bhuwan Dhingra, Markus Dreyer, Venkatesh Saligrama

## 概要
検索拡張LLMエージェントは詳細な調査レポート（DRR）を生成できるが、**クレームレベルの事実性検証**は依然として困難。既存のファクトチェッカーは主に一般ドメインのファクトイドスタイル原子クレーム向けに設計されており、DRRに転移するかテストするベンチマークがない。

そしてそのようなベンチマークを構築すること自体も困難：管理された研究で、支援なしの専門家は検証可能クレームの隠しマイクロゴールドセットで**60.8%精度**のみ達成。

## 技術的詳細
**Evolving Benchmarking via Audit-then-Score (AtS)** を提案：
- ベンチマークラベルと根拠が明示的に改訂可能
- 検証器がベンチマークに異議がある場合、エビデンスを提出
- 監査人が紛争を裁定
- 承認された改訂がモデルスコアリング前にベンチマークを更新

4ラウンドのAtSで専門家マイクロゴールド精度が60.8%から**90.9%**に向上。

**DeepFact-Bench**: 監査可能な根拠を持つバージョン管理されたDRR事実性ベンチマーク

**DeepFact-Eval**: ドキュメントレベル検証エージェント（グループ化liteバリアントあり）
- DeepFact-Benchで既存検証器を上回る
- 外部事実性データセットにもよく転移

## 主要結果
- ワンショットラベラーとしてよりも**監査人としての専門家がはるかに信頼性が高い**
- AtSアプローチにより専門家精度が大幅向上
- DeepFact-Evalは既存手法を一貫して上回る

## 実用的意義
- 自動調査レポートの品質保証
- LLM生成コンテンツのファクトチェック
- 進化するベンチマーク手法の確立
- 専門家評価プロセスの改善

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05912
