# Safe RLHF Beyond Expectation: Stochastic Dominance for Universal Spectral Risk Control

- **arXiv**: [2603.10938](https://arxiv.org/abs/2603.10938)
- **分野**: cs.LG（機械学習）、cs.AI
- **著者**: Yaswanth Chittepu et al.
- **キーワード**: RLHF, 安全性, 確率優位, リスク制御

## 概要

Safe RLHFは通常、期待コスト制約で安全性を強制するが、期待値はコスト分布の単一統計量のみを捕捉し、ヘビーテールや稀な壊滅的イベントにおける分布の不確実性を考慮できない。本研究は確率優位（Stochastic Dominance）による代替アプローチを提案。

## 手法: RAD (Risk-sensitive Alignment via Dominance)

- スカラー期待コスト制約を**一次確率優位（FSD）制約**に置き換え
- ターゲットポリシーのコスト分布を参照ポリシーと**Optimal Transport（OT）フレームワーク**内で比較
- エントロピー正則化とSinkhorn反復で微分可能かつ計算効率的な目的関数
- **分位加重FSD制約**: 広範な**Spectral Risk Measures (SRMs)**を普遍的に制御

## 実験結果

- ベースライン比で**有害性改善**しつつ有用性を維持
- OOD有害性評価でより**ロバスト**な性能

## 注目ポイント

テール分布まで考慮したRLHF安全性フレームワーク。分位加重関数でモデルのリスクプロファイルを原理的に調整可能。
