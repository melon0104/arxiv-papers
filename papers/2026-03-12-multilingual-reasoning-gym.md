# Multilingual Reasoning Gym: Multilingual Scaling of Procedural Reasoning Environments

- **arXiv**: [2603.10793](https://arxiv.org/abs/2603.10793)
- **分野**: cs.CL（自然言語処理）
- **著者**: Konstantin Dobler et al.
- **キーワード**: 多言語, 推論, RLVR, ベンチマーク

## 概要

Reasoning Gym (Stojanovski et al., 2025)を拡張し、**14言語**にわたって検証可能な推論問題を手続き的に生成するフレームワーク。10言語でネイティブスピーカー検証付きテンプレート翻訳、言語的自然性を確保するためのコード/テンプレート適応を実施。

## 主な特徴

- **94タスク**のテンプレートを翻訳
- 元のReasoning Gymの利点を維持:
  - 事実上無限の問題インスタンス生成
  - 調整可能な難易度
- **Reinforcement Learning from Verifiable Rewards (RLVR)** および評価設定で直接使用可能
- 言語間で問題が並列化されており、手続き的性質による大規模な多言語並列データ生成が可能

## 注目ポイント

多言語推論モデルの研究を支援するための実装を公開。RLVRの多言語展開における重要なインフラストラクチャ。
