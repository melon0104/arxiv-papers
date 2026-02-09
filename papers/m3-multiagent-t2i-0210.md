# M3: High-fidelity Text-to-Image Generation via Multi-Modal, Multi-Agent, Multi-Round Visual Reasoning

**arXiv**: [2602.06166](https://arxiv.org/abs/2602.06166)  
**日付**: 2026-02-09  
**分野**: cs.CV（コンピュータビジョン）  
**機関**: 複数研究機関

## 概要

複雑な構成的プロンプトに対応するための訓練不要フレームワーク。既存の基盤モデルをマルチエージェントループで協調させ、推論時に反復的に改善。

## 技術的ポイント

- **Multi-Agent Orchestration**: Planner, Checker, Refiner, Editor, Verifierの協調
- **検証可能チェックリスト**: プロンプトを検証可能な制約に分解
- **1制約ずつ修正**: 各エージェントが1つの制約を外科的に修正
- **単調改善保証**: Verifierが品質低下を防止

## 結果

### OneIG-ENベンチマーク（Qwen-Image + M3）
- **総合スコア: 0.532** ← 新SOTA
  - Imagen4 (0.515)を上回る
  - Seedream 3.0 (0.530)を上回る

### GenEval
- 空間推論性能が**2倍**向上
- 強化テストセットでの大幅改善

## 選定理由

- **Imagen4/Seedream 3.0超え**: OSSモデルが商用フラッグシップを上回る
- マルチエージェント推論の実用的成功例
