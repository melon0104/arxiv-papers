---
layout: paper
title: "FEM: Realistic Face Reconstruction from Facial Embeddings via Diffusion Models"
date: 2026-02-17
arxiv_id: "2602.13168"
category: cs.CV
tags: [face-recognition, privacy, diffusion, security, aaai-2026]
---

# Realistic Face Reconstruction from Facial Embeddings via Diffusion Models

## 基本情報
- **arXiv**: [2602.13168](https://arxiv.org/abs/2602.13168)
- **採択**: AAAI 2026
- **著者**: Dong Han, Yong Li, Joachim Denzler
- **機関**: Friedrich Schiller University Jena

## 🏆 AAAI 2026 採択

## 一言まとめ
顔認識システムの埋め込みから高解像度のリアルな顔画像を再構成する攻撃手法。プライバシー保護型顔認識（PPFR）システムへの攻撃も実証。

## 課題
- 顔認識システムのプライバシーリスク検証が不十分
- 特にPPFRシステムからの再構成は未探索

## 提案手法: Face Embedding Mapping (FEM)
### Kolmogorov-Arnold Network (KAN)
- 埋め込みから顔への攻撃を実行
- 事前学習済みIdentity-Preserving拡散モデルを活用

### 対象システム
- 最先端の顔認識（FR）システム
- プライバシー保護型顔認識（PPFR）システム

## 実験結果
- 再構成された顔で他の実世界FRシステムへのアクセスに成功
- 部分的・保護された埋め込みからの再構成でもロバスト
- FR/PPFRシステムのプライバシー漏洩評価ツールとして利用可能

## キーポイント
- 顔認識システムのセキュリティ評価に重要
- PPFRシステムへの初の本格的攻撃研究
- 公開データセットのみを使用
