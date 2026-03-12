# Trajectory-Informed Memory Generation for Self-Improving Agent Systems

- **arXiv**: [2603.10600](https://arxiv.org/abs/2603.10600)
- **分野**: cs.AI（AI全般）、cs.DB、cs.IR
- **著者**: K. R. Jayaram et al.
- **キーワード**: LLMエージェント, メモリ, 自己改善

## 概要

LLMエージェントは実行経験から学習して将来のパフォーマンスを改善することが困難。多くのタスクを成功させても、非効率なパターンを繰り返し、類似エラーからの回復に失敗し、過去の成功戦略を適用する機会を逃している。

## フレームワーク（4コンポーネント）

1. **Trajectory Intelligence Extractor**: エージェント推論パターンのセマンティック分析
2. **Decision Attribution Analyzer**: どの決定・推論ステップが失敗・回復・非効率につながったかを特定
3. **Contextual Learning Generator**: 3種類のガイダンス生成
   - 成功パターンからの**戦略ヒント**
   - 失敗処理からの**回復ヒント**
   - 非効率だが成功した実行からの**最適化ヒント**
4. **Adaptive Memory Retrieval System**: 多次元類似性に基づき関連学習をプロンプトに注入

## AppWorld ベンチマーク結果

- 保留タスクで最大**+14.3pp**シナリオゴール完了改善
- 複雑タスクで特に強力: **+28.5pp**（149%相対改善）

## 注目ポイント

汎用的な会話事実ではなく、実行パターンを理解し、出所付き構造化学習を抽出する新しいメモリシステム。
