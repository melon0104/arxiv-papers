---
layout: paper
title: "Consistency of Large Reasoning Models Under Multi-Turn Attacks"
date: 2026-02-17
arxiv_id: "2602.13093"
category: cs.AI
tags: [llm, reasoning, robustness, adversarial, safety]
---

# Consistency of Large Reasoning Models Under Multi-Turn Attacks

## 基本情報
- **arXiv**: [2602.13093](https://arxiv.org/abs/2602.13093)
- **著者**: Yubo Li, Ramayya Krishnan, Rema Padman
- **機関**: Carnegie Mellon University

## 一言まとめ
9つのフロンティア推論モデルのマルチターン敵対攻撃下でのロバスト性を評価。推論能力は有意だが不完全な堅牢性を付与し、5つの失敗モードを特定。

## 課題
- 推論能力を持つLLMは複雑なタスクでSOTA
- マルチターン敵対圧力下でのロバスト性は未探索

## 評価
### 9つのフロンティア推論モデル
- 敵対攻撃への応答を分析

## 主要発見

### 1. 推論は意味のある堅牢性を付与するが不完全
- 大半の推論モデルがInstruction-tunedベースラインを大幅に上回る
- しかし全モデルに固有の脆弱性プロファイルが存在

### 2. 攻撃効果
- **誤誘導提案**: 普遍的に効果的
- **社会的圧力**: モデル固有の効果

### 3. 5つの失敗モード（軌跡分析から特定）
1. Self-Doubt（自己疑念）
2. Social Conformity（社会的同調）
3. Suggestion Hijacking（提案ハイジャック）
4. Emotional Susceptibility（感情的感受性）
5. Reasoning Fatigue（推論疲労）
→ 上位2つが失敗の50%を占める

### 4. 防御の課題
- **CARG（Confidence-Aware Response Generation）**: 標準LLMには有効だが推論モデルには失敗
- 理由: 拡張推論トレースによる過信
- 驚くべきことに、ランダムな信頼度埋め込みが標的抽出を上回る

## キーポイント
- 推論能力≠敵対的ロバスト性
- 信頼度ベースの防御は推論モデル向けに根本的再設計が必要
- 重要な失敗モードの分類を提供
