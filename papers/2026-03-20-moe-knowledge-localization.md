---
layout: default
title: "Knowledge Localization in Mixture-of-Experts LLMs Using Cross-Lingual Inconsistency"
---

# Knowledge Localization in Mixture-of-Experts LLMs Using Cross-Lingual Inconsistency

[arXiv:2603.17102](https://arxiv.org/abs/2603.17102) | cs.CL

## 著者
Lucas Bandarkar et al.

## 一言まとめ
多言語間の不整合を活用したMoE LLMの**知識局在化手法**。約20/6000エキスパートを無効化するだけで**40%以上のケースで正答不能に**。

## 概要
現代のLLMは言語間で動作に大きなばらつきを示す（ある言語では事実を想起できるが別言語ではできない等）。本研究はこの多言語間不整合を、問題として緩和するのではなく、MoE LLMの解釈可能性ツールとして活用。モデルが情報を正しく想起できる言語セットとできない言語セットのルーティングを対比し、知識に機能的役割を果たすコンポーネントを分離。

## 注目ポイント
- **新しいアプローチ**: 多言語不整合を解釈可能性ツールとして転用
- **効率的局在化**: 統計的対比分析でルーターロジットから重要エキスパートを特定
- **実験的検証**: 約20エキスパート無効化で40%以上が正答不能
- **スケーラブル**: 複雑化するLLMに対応可能な現実的手法

## 技術的詳細
- 2段階: (1) 多言語で困難な事実質問を投げ「成功」「失敗」活性化バケットを生成
- (2) MoEルーターロジットに統計的対比分析を適用して重要エキスパートを特定
- 検証: 特定したエキスパートを無効化して再質問

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17102)
- [PDF](https://arxiv.org/pdf/2603.17102)
