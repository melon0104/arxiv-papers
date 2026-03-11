# Chow-Liu Ordering for Long-Context Reasoning in Chain-of-Agents

## 基本情報
- **arXiv ID**: 2603.09835
- **タイトル**: Chow-Liu Ordering for Long-Context Reasoning in Chain-of-Agents
- **著者**: Naman Gupta, Vaibhav Singh, Arun Iyer, Kirankumar Shiragur, Pratham Grover 他
- **所属**: Microsoft Research India
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.09835

## 概要
Chain-of-Agents（CoA）のような逐次マルチエージェント推論フレームワークは、入力をチャンクに分解し、LLMベースのワーカーエージェントで順次処理する。確率論的観点では、CoAは全文コンテキストの条件付き分布を近似するが、**有限メモリ近似**は情報ボトルネックを生み、最終的な証拠状態はチャンク処理順序に依存する。

## 提案手法
**Chow-Liu木**を活用したチャンク順序最適化：
1. 強く関連するチャンクを優先する依存構造を学習
2. 結果の木を幅優先探索でチャンク順序を決定
3. エージェント間の情報損失を削減

## 実験結果
3つの長文コンテキストベンチマークで評価：
- デフォルトのドキュメントチャンク順序を上回る
- セマンティックスコアベースの順序付けも上回る
- 回答関連性と完全一致精度で一貫した改善

## 注目ポイント
- 🔬 **Microsoft Research**: 理論的基盤を持つ手法
- 🌳 **Chow-Liu木**: 情報理論に基づくチャンク順序最適化
- 📊 **長文コンテキスト**: 情報損失を最小化

## カテゴリ
cs.CL

## 関連タグ
#マルチエージェント #長文コンテキスト #情報理論 #LLM #Microsoft
