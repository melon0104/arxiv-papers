# BEAR: Beam-Search-Aware Optimization for LLM Recommendation

**arXiv**: [2601.22925](https://arxiv.org/abs/2601.22925)  
**カテゴリ**: cs.IR, cs.AI, cs.LG  

## 概要

LLMベースの推薦システムにおける訓練-推論の不整合を解消するbeam search認識型の最適化手法。

## 問題設定

LLM推薦システムでは:
- 訓練: SFT（教師あり微調整）で正アイテムの全体確率を最大化
- 推論: beam searchでtop-B候補を効率的に取得

**問題点**: 正アイテムの全体確率が高くても、prefix確率が低いとbeam searchの貪欲刈り込みで早期に除外される

## BEAR (Beam-SEarch-Aware Regularization)

訓練時にbeam search挙動を明示的に考慮:

- **緩和条件**: 各デコーディングステップで正アイテムの各トークンがtop-B候補内にランクインすることを強制
- **効率性**: 訓練時にbeam searchをシミュレーションせず、計算コストは標準SFTとほぼ同等

## 実験結果

4つの実世界データセットでベースラインを大幅に上回る性能を達成。

## 一言

**beam searchの貪欲刈り込みを訓練時に考慮して、LLM推薦の訓練-推論ギャップを解消**
