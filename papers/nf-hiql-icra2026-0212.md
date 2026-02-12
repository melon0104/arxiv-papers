---
layout: paper
title: "NF-HIQL: Data-Efficient Hierarchical Goal-Conditioned RL via Normalizing Flows"
arxiv_id: "2602.11142"
date: 2026-02-12
categories: [cs.RO, cs.AI, cs.LG]
conference: "ICRA 2026"
---

# NF-HIQL: Normalizing Flow for Hierarchical RL

## 基本情報
- **arXiv**: [2602.11142](https://arxiv.org/abs/2602.11142)
- **カテゴリ**: cs.RO, cs.AI, cs.LG
- **著者**: Shaswat Garg et al.
- **採択**: ICRA 2026

## 概要

階層的ゴール条件付き強化学習において、単峰ガウスポリシーを表現力豊かなNormalizing Flowポリシーに置き換え。データ効率とポリシー表現力を両立。

## 技術的貢献

### RealNVPベースポリシー
- 高レベル・低レベル両方の階層でFlow使用
- 計算可能な対数尤度
- 効率的サンプリング
- リッチなマルチモーダル行動のモデリング

### 理論的保証
- RealNVPポリシーのKLダイバージェンス明示的バウンド
- PACスタイルサンプル効率結果

## 評価

OGBenchの多様な長期タスクで検証：
- ロコモーション
- ボールドリブル
- マルチステップ操作

## 結果

先行するゴール条件付き・階層的ベースライン一貫して上回る性能。限られたデータ下での優れたロバスト性を実証。
