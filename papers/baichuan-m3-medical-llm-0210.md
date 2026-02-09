# Baichuan-M3: Modeling Clinical Inquiry for Reliable Medical Decision-Making

**arXiv**: [2602.06570](https://arxiv.org/abs/2602.06570)  
**日付**: 2026-02-09  
**分野**: cs.CL（自然言語処理）  
**機関**: Baichuan

## 概要

受動的な質問応答から能動的な臨床グレード意思決定支援へのパラダイムシフトを目指す医療強化LLM。専用の訓練パイプラインで医師のワークフローをモデル化。

## 技術的ポイント

- **能動的情報取得**: 曖昧さ解消のための積極的な質問
- **長期推論**: 散在するエビデンスを統合した一貫性のある診断
- **適応的ハルシネーション抑制**: 事実の信頼性確保

## 結果

- **HealthBench**: SOTA達成、GPT-5.2を上回る
- **HealthBench-Hallu**: ハルシネーション耐性で優位
- **ScanBench**: 臨床照会・助言・安全性で優れた性能

## モデル公開

HuggingFace: https://huggingface.co/collections/baichuan-inc/baichuan-m3

## 選定理由

- **コード/モデル公開**: HuggingFace
- **GPT-5.2超え**: 主要医療ベンチマークでSOTA
- 医療AI分野の重要な進展
