# AgentCPM-Explore: Realizing Long-Horizon Deep Exploration for Edge-Scale Agents

**arXiv**: [2602.06485](https://arxiv.org/abs/2602.06485)  
**日付**: 2026-02-09  
**分野**: cs.AI（AI全般）  
**機関**: 清華大学（Tsinghua）、OpenBMB

## 概要

4Bパラメータスケールでのエージェントモデル訓練に関する初の系統的研究。エッジスケールモデルの3つのボトルネック（SFT時の壊滅的忘却、RL時の報酬ノイズ感度、長コンテキストでの推論劣化）を特定し解決。

## 技術的ポイント

- **Parameter-Space Model Fusion**: 壊滅的忘却を防止
- **Reward Signal Denoising**: RL時の安定性向上
- **Contextual Information Refinement**: 長コンテキスト推論の改善
- **Deep Exploration**: 包括的な訓練フレームワーク

## 結果

### ベンチマーク性能
- **GAIA (テキストベース)**: pass@64で**97.09%**精度
- **4Bクラス**: 全モデル中SOTA
- **8Bクラス**: SOTAモデルに匹敵または上回る

### 大規模モデルとの比較（5ベンチマーク）
- **Claude-4.5-Sonnet**を上回る
- **DeepSeek-v3.2**を上回る

## 選定理由

- **有名研究機関**: 清華大学
- **4Bで大規模モデル超え**: エッジ展開への重要な示唆
