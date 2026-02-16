---
layout: paper
title: "SCOPE: Selective Conformal Optimized Pairwise LLM Judging"
date: 2026-02-17
arxiv_id: "2602.13110"
category: cs.CL
tags: [llm, evaluation, conformal-prediction, preference-learning]
---

# SCOPE: Selective Conformal Optimized Pairwise LLM Judging

## 基本情報
- **arXiv**: [2602.13110](https://arxiv.org/abs/2602.13110)
- **著者**: Sher Badshah, Ali Emami, Hassan Sajjad
- **機関**: Dalhousie University等

## 一言まとめ
LLM-as-Judgeのための有限サンプル統計保証付き選択的評価フレームワーク。バイアス中立な不確実性シグナルでエラー率を制御。

## 課題
- LLM Judgeはミスキャリブレーションと系統的バイアスが発生
- 人間のラベルを代替する際の信頼性問題

## 提案手法: SCOPE
### Conformal Prediction
- 交換可能性の下で、棄却しない判定のエラー率をユーザー指定レベルα以下に保証

### Bidirectional Preference Entropy (BPE)
- 両方向の応答位置でジャッジにクエリ
- 順序不変性を強制して集約
- エントロピーベースの不確実性スコアに変換

## 実験結果
### MT-Bench, RewardBench, Chatbot Arena
- α=0.10でリスク境界を一貫して満たす（経験リスク≈0.097〜0.099）
- 高いカバレッジを維持（RewardBench+Qwen-32Bで0.98）
- MT-Bench+Qwen-7Bでナイーブベースライン比2.4倍の判定を受理

## キーポイント
- LLM評価の統計的信頼性を確保
- バイアス中立な不確実性推定
- 高カバレッジと低エラー率の両立
