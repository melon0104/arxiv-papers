---
layout: paper
title: "Share: 継続学習のための共有LoRAサブスペース"
date: 2026-02-07
arxiv_id: "2602.06043"
categories: [cs.LG, cs.CV, Continual Learning]
---

# Shared LoRA Subspaces for almost Strict Continual Learning

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06043
- **著者**: Prakhar Kaushik, Ankit Vaidya, Shravan Chaudhari, **Rama Chellappa** (JHU), **Alan Yuille** (JHU)
- **機関**: Johns Hopkins University

## 概要
単一の共有低ランクサブスペースを学習・動的更新することで、**データリプレイや複数アダプターなしに**継続的ファインチューニングを実現。

## 技術的ポイント
- **基盤サブスペース**: 過去タスクのコア知識を抽出
- **増分統合**: 新情報を本質的なサブスペース方向として識別
- **前方知識転移**: 破壊的干渉を最小化しながら新タスク知識を統合

## 実験結果
| 指標 | 改善 |
|------|------|
| パラメータ削減 | **100倍** |
| メモリ節約 | **281倍** |
| 性能 | 共同訓練モデルと同等 |

- 画像分類、NLU、3Dポーズ推定、Text-to-Imageで検証
- 単一Shareモデルが数百のタスク固有LoRAアダプターを置換可能

## 注目ポイント
- **JHUの著名研究者による研究**
- スケーラブルな非同期継続学習をサポート
- 大規模AIシステムでの生涯学習に実践的
