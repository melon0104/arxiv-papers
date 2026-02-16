---
layout: paper
title: "CoPE-VideoLM: Codec Primitives For Efficient Video Language Models"
date: 2026-02-17
arxiv_id: "2602.13191"
category: cs.CV
tags: [video-understanding, vlm, efficiency, codec]
---

# CoPE-VideoLM: Codec Primitives For Efficient Video Language Models

## 基本情報
- **arXiv**: [2602.13191](https://arxiv.org/abs/2602.13191)
- **プロジェクトページ**: [sayands.github.io/cope](https://sayands.github.io/cope/)
- **著者**: Sayan Deb Sarkar, Rémi Pautrat, Ondrej Miksik, Marc Pollefeys et al.
- **機関**: ETH Zurich, Microsoft

## 一言まとめ
ビデオコーデックのプリミティブ（モーションベクトル・残差）を活用し、VideoLMの効率を大幅に向上。Time-to-First-Token 86%削減、トークン使用量93%削減。

## 課題
- 現在のVideoLMはキーフレームサンプリングに依存
- スパースな時間カバレッジでマクロ・ミクロレベルの詳細を見逃す
- 各フレームのフル画像処理で計算オーバーヘッドが大きい

## 提案手法: CoPE-VideoLM
### ビデオコーデックプリミティブの活用
- **Motion Vectors**: 動きの情報をネイティブにエンコード
- **Residuals**: 変化部分のみを表現

### 軽量Transformerエンコーダ
- コーデックプリミティブを集約
- 画像エンコーダ埋め込みと表現を整列
- End-to-Endファインチューニングで収束を加速

## 実験結果
### 効率性
- **Time-to-First-Token**: 最大86%削減
- **トークン使用量**: 最大93%削減

### 性能（14の動画理解ベンチマーク）
- 一般QA、時間推論、長時間理解、空間シーン理解
- 標準VideoLMと同等以上の性能を維持

## キーポイント
- ビデオコーデックの知識をVLMに活用する新アプローチ
- 大幅な効率改善と性能維持の両立
- 複数ベンチマークでの包括的検証
