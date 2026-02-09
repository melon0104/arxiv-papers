# Driving with DINO: Vision Foundation Features as Unified Bridge for Sim-to-Real

**arXiv**: [2602.06159](https://arxiv.org/abs/2602.06159)  
**日付**: 2026-02-09  
**分野**: cs.CV（コンピュータビジョン）  
**機関**: 複数大学・企業

## 概要

Sim2Realビデオ生成における根本的な「一貫性-リアリズムのジレンマ」を解決。VFM特徴をシミュレーションと実世界ドメイン間の統一的なブリッジとして活用。

## 技術的ポイント

- **Principal Subspace Projection**: "texture baking"の原因となる高周波成分を除去
- **Random Channel Tail Drop**: 剛体的次元削減による構造損失を緩和
- **Spatial Alignment Module**: DINOv3の高解像度特性を活用した制御精度向上
- **Causal Temporal Aggregator**: フレーム単位のDINO特徴を因果的畳み込みで統合、モーションブラー抑制

## 結果

- **一貫性-リアリズムの両立**: 低レベル信号の制御精度＋高レベル事前知識のリアリズム
- **時間的安定性**: 長時間ビデオでの一貫性保持
- **汎用性**: 様々なシーン・条件に対応

## プロジェクトページ

https://albertchen98.github.io/DwD-project/

## 選定理由

- DINOv3を活用した自動運転Sim2Realの新手法
- 実用的な自動運転データ生成に貢献
