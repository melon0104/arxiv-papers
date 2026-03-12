# Beyond the Illusion of Consensus: From Surface Heuristics to Knowledge-Grounded Evaluation in LLM-as-a-Judge

- **arXiv**: [2603.11027](https://arxiv.org/abs/2603.11027)
- **分野**: cs.CL（自然言語処理）
- **著者**: Mingyang Song et al.
- **キーワード**: LLM-as-a-Judge, 評価バイアス, RLAIF

## 概要

LLM-as-a-Judgeパラダイムは「高い評価者間一致＝信頼性の高い評価」という前提に依存している。本研究はこの前提に挑戦する2つの発見を提示。

## 発見1: Evaluation Illusion（評価幻想）

**105,600評価インスタンス**（32 LLM × 3 フロンティアジャッジ × 100タスク × 11温度）の大規模研究:

- モデルレベル一致（Spearman ρ = 0.99）は高いが、サンプルレベル一致（Pearson r̄ = 0.72; ICC = 0.67）は脆弱
- ルーブリック構造の共有だけで全一致の**62%**を復元
- 高品質出力は最も一貫性の**低い**評価を受ける（パラドックス）

## 発見2: MERG（Metacognitive Enhanced Rubric Generation）

ドメイン知識に基づく動的ルーブリック生成が有効:
- **体系化ドメイン**（教育+22%、学術+27%）: 一致度向上
- **主観的ドメイン**: 一致度低下（真の評価的多元性が出現）

## 注目ポイント

RLAIFにおける報酬モデリングへの示唆。評価ルーブリックは汎用的基準ではなく専門知識で動的に強化すべきという提案。
