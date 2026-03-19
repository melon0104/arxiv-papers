---
layout: default
title: "CRE-T1 Preview: Beyond Contrastive Learning for Reasoning-Intensive Retrieval"
---

# CRE-T1 Preview Technical Report: Beyond Contrastive Learning for Reasoning-Intensive Retrieval

[arXiv:2603.17387](https://arxiv.org/abs/2603.17387) | cs.IR

## 著者
Guangzhi Wang et al.

## 一言まとめ
対照学習の限界を超える**生成型検索モデルT1**。推論集約的検索で静的表現アライメントを動的推論に置き換え、GRPOで最適導出戦略を学習。

## 概要
推論集約的検索の核心課題は、クエリとドキュメント間の暗黙的推論関係の特定にある。対照学習パラダイムは本質的に静的表現統合技術であり、各クエリの推論要求に応じた動的調整ができない。T1は関連性モデリングを静的アライメントから動的推論へシフトさせる生成型検索モデル。

## 注目ポイント
- **動的推論生成**: クエリごとに中間推論軌跡を動的生成
- **GRPO導入**: 強化学習で最適導出戦略を試行錯誤学習
- **BRIGHTベンチマーク**: 4Bパラメータで大型対照学習モデルを上回る
- **マルチステージパイプライン相当性能**: 単一モデルで達成

## 技術的詳細
- クエリ側: 暗黙的推論関係を橋渡しする中間推論軌跡を動的生成
- <embtoken>を推論出力の意味集約点として使用
- ドキュメント側: instruction + text + <embtoken>形式で高スループットインデックス
- 3段階訓練カリキュラムで動的推論能力を内在化

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17387)
- [PDF](https://arxiv.org/pdf/2603.17387)
