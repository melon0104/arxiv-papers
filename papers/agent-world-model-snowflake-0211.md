# Agent World Model: Infinity Synthetic Environments for Agentic Reinforcement Learning

## 基本情報
- **arXiv**: [2602.10090](https://arxiv.org/abs/2602.10090)
- **カテゴリ**: cs.AI, cs.CL, cs.LG
- **投稿日**: 2026-02-10
- **機関**: Snowflake Labs
- **コード**: [GitHub](https://github.com/Snowflake-Labs/agent-world-model)

## 一言まとめ
完全合成環境生成パイプラインで1,000環境を構築。合成環境のみの訓練で強いOOD汎化を実証。

## 概要
LLMエージェントのスケーラブルな訓練は、多様で信頼性の高い環境の不足が制限要因。本研究は完全合成のコード駆動環境生成パイプライン(AWM)を提案。

## 技術的貢献
- **完全合成環境パイプライン**: 1,000の日常シナリオ環境を生成
- **コード駆動＋DB連携**: LLMシミュレーションより信頼性の高い状態遷移
- **平均35ツール/環境**: 豊富なツールセットとの相互作用
- **信頼性の高い報酬関数設計**: 実行可能環境とDBアクセスを活用

## 実験結果
- 3つのベンチマークで強いOOD汎化を実証
- ベンチマーク特化訓練より合成環境のみの訓練が優位
- 効率的なエージェント相互作用を実現

## 選定理由
✅ コード公開 (GitHub)
✅ 有名機関 (Snowflake Labs)
