---
layout: default
title: "Anonymous-by-Construction: An LLM-Driven Framework for Privacy-Preserving Text"
---

# Anonymous-by-Construction: An LLM-Driven Framework for Privacy-Preserving Text

[arXiv:2603.17217](https://arxiv.org/abs/2603.17217) | cs.CL

## 著者
Federico Albanese et al.

## 一言まとめ
**オンプレミスLLMによるPII匿名化パイプライン**。Microsoft Presidio、Google DLPを上回り、プライバシー・ユーティリティ・訓練性のフロンティアでSOTA達成。

## 概要
AIの責任ある利用には、データの有用性を損なわずに機密情報を保護することが求められる。本研究はオンプレミス・LLM駆動の置換パイプラインで、個人識別情報(PII)を現実的で型一貫性のあるサロゲートに置換してテキストを匿名化。組織境界内で完全に実行され、データ流出を防止しつつ流暢さとタスク関連セマンティクスを保持。

## 注目ポイント
- **データ流出防止**: オンプレミス実行で外部APIへの機密情報露出なし
- **包括的評価**: プライバシー、セマンティックユーティリティ、訓練性を同時測定
- **エージェンティックQ&A対応**: 匿名化レイヤーを挟んだQ&Aエージェントの品質も評価
- **BERT+LoRA検証**: 匿名化テキストでのファインチューニング性能も確認

## 技術的詳細
- Action-Based Conversation Datasetで系統的多指標評価
- Microsoft Presidio、Google DLP、ZSTS(編集のみ/編集+置換)と比較
- 型保持置換でQ&Aエージェントの責任あるデプロイを実現

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17217)
- [PDF](https://arxiv.org/pdf/2603.17217)
