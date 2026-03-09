---
layout: paper
title: "EvoESAP: Non-Uniform Expert Pruning for Sparse MoE"
date: 2026-03-09
categories: [cs.LG]
arxiv_id: "2603.06003"
---

# EvoESAP: Non-Uniform Expert Pruning for Sparse MoE

## 基本情報
- **arXiv ID**: 2603.06003
- **カテゴリ**: cs.LG (Machine Learning)
- **投稿日**: 2026-03-09

## 著者
Zongfang Liu, Shengkun Tang, Boyang Sun, Zhiqiang Shen, Xin Yuan

## 概要
Sparse Mixture of Experts (SMoE) 言語モデルは低いper-tokenコンピュートで強力な性能を達成するが、フルエキスパートプールの保存と提供が必要なため、デプロイはメモリとスループットに制約される。

既存のポストトレーニングエキスパートプルーニング手法は**どのエキスパートを各層でプルーニングするか**に焦点を当て、均一な層間スパース性割り当てをデフォルトとするが、この割り当ては性能に強く影響する。

**EvoESAP**を提案：プルーニングを**層内エキスパートランキング**と**層間予算割り当て**に分離。

## 技術的詳細
**ESAP (Expected Speculative Acceptance Proxy)** を導入：
- スペキュラティブデコーディングにインスパイアされた教師強制メトリック
- プルーニングモデルがフルモデルにどれだけマッチするかを測定
- 有界で安定、コストのかかるオートレグレッシブデコーディングなしで多数の候補を比較可能

EvoESAPは進化的検索フレームワーク：
- 固定グローバル予算下で非均一層間スパース性割り当てを最適化
- 層内プルーニング順序を固定したまま
- Frequency、EAN、SEER、REAPなどの基準とプラグアンドプレイ

## 主要結果
7B-30B SMoE LLMで25%および50%スパース性で評価：
- 均一プルーニングと比較して、EvoESAPは一貫して優れた非均一割り当てを発見
- オープンエンド生成を改善: MATH-500で50%スパース性時**+19.6%**
- 多肢選択精度を維持しつつ競争力維持

## 実用的意義
- MoEモデルの効率的デプロイ
- メモリ制約環境でのLLM運用
- 既存プルーニング手法との互換性
- 大規模言語モデルの実用化促進

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.06003
