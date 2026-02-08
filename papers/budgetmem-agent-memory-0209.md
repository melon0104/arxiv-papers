# BudgetMem: Query-Aware Budget-Tier Routing for Runtime Agent Memory

- **arXiv**: [2602.06025](https://arxiv.org/abs/2602.06025)
- **カテゴリ**: cs.CL, cs.AI, cs.LG
- **投稿日**: 2026-02-05
- **GitHub**: https://github.com/ViktorAxelsen/BudgetMem

## 概要

LLMエージェントのランタイムメモリにおいて、性能-コストの明示的なクエリ認識制御を行うフレームワーク「BudgetMem」を提案。

## 主要な貢献

- **3段階予算ティア**: 各メモリモジュールにLow/Mid/Highの3ティアを提供
- **軽量ルーター**: 強化学習で訓練したコンパクトなニューラルポリシー
- **3つのティアリング戦略**: 実装（メソッド複雑度）、推論（推論動作）、容量（モデルサイズ）

## 実験結果

- LoCoMo、LongMemEval、HotpotQAで評価
- 高予算設定で強力なベースラインを上回る
- タイトな予算下でも優れた精度-コストフロンティアを提供

## コード公開

GitHubでコード公開済み

## リンク

- [PDF](https://arxiv.org/pdf/2602.06025)
- [GitHub](https://github.com/ViktorAxelsen/BudgetMem)
