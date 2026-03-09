---
layout: paper
title: "MLLMRec-R1: Incentivizing Reasoning Capability in Large Language Models for Multimodal Sequential Recommendation"
date: 2026-03-09
categories: [cs.IR]
arxiv_id: "2603.06243"
---

# MLLMRec-R1: Incentivizing Reasoning Capability in Large Language Models for Multimodal Sequential Recommendation

## 基本情報
- **arXiv ID**: 2603.06243
- **カテゴリ**: cs.IR (Information Retrieval)
- **投稿日**: 2026-03-09
- **コード**: https://github.com/wangyu0627/MLLMRec-R1

## 著者
Yu Wang, Yonghui Yang, Le Wu, Jiancan Wu, Hefei Xu, Hui Lin

## 概要
GRPO（Group Relative Policy Optimization）はLLMの推論とpreference alignmentの標準的ポストトレーニング手法だが、**マルチモーダル逐次推薦（MSR）**への拡張には根本的な障壁がある。

主要課題と解決策：
1. **視覚トークン支配問題**: MSRは履歴インタラクションと複数候補アイテムの視覚コンテンツを同時にエンコードする必要があり、視覚トークンが入力を支配→グループベースrolloutコストが履歴長と候補セットサイズに比例してスケール
2. **報酬インフレーション**: 既存のChain-of-Thought監督は推薦シナリオで報酬インフレーションに悩まされ、高い学習報酬がランキング性能向上に確実に変換されない

## 技術的詳細
- **視覚信号テキスト化**: 高価な視覚トークンを排除しつつマルチモーダル意味を保持
- **高品質CoT監督構築**: 精製と信頼度認識評価による高品質マルチモーダルCoTサンプル生成
- **Mixed-Grained Data Augmentation**: 信頼性の高いCoTサンプルを選択的に注入し標準学習データを保持、報酬インフレーションを軽減

## 主要結果
3つのベンチマークデータセットで評価：
- 既存のSOTA手法を一貫して上回る
- マルチモーダル逐次推薦向けの実用的で効果的なGRPOベース推論パイプラインを確立

## 実用的意義
- Eコマース・コンテンツ推薦でのマルチモーダル理解向上
- LLMベース推薦システムの推論能力強化
- 視覚と言語の統合による次世代推薦システム設計

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.06243
- GitHub: https://github.com/wangyu0627/MLLMRec-R1
