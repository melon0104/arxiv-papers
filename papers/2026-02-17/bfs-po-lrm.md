# BFS-PO: Best-First Search for Large Reasoning Models

## 基本情報
- **arXiv**: [2602.14917](https://arxiv.org/abs/2602.14917)
- **カテゴリ**: cs.CL, cs.AI
- **投稿日**: 2026-02-16
- **著者**: Fiorenzo Parascandolo, Wenhui Tan, Enver Sangineto, Ruihua Song, Rita Cucchiara

## 概要
OpenAI o1やDeepSeek-R1などのLarge Reasoning Models (LRMs)における「overthinking」問題を解決するRL手法。長い推論チェーンが計算コストの増大と冗長な出力を引き起こす課題に対処。

## 技術的特徴
1. **Best-First Search探索戦略**: 最短の正解を効率的に探索
2. **最大エントロピーノードベースのバックトラッキング**: 効果的な探索空間の削減
3. **漸進的短縮**: 訓練中に徐々に短い応答を生成することで簡潔な推論を学習
4. **GRPO/DAPOの弱点を克服**: 従来のRLアルゴリズムがoverthinkingを悪化させる問題を解決

## 主要結果
- 複数のベンチマークとベースLRMで評価
- **精度向上と回答短縮の両立**を実現
- 推論チェーンを簡潔化しつつ正解率を改善

## 注目ポイント
🎯 **LRMの推論効率化**に直結する実用的手法、テストタイム計算コスト削減に貢献
