# Overthinking Loops in Agents: A Structural Risk via MCP Tools

## 基本情報
- **arXiv**: [2602.14798](https://arxiv.org/abs/2602.14798)
- **カテゴリ**: cs.CL, cs.CR
- **投稿日**: 2026-02-16
- **著者**: Yohan Lee, Jisoo Jang, Seoyeon Choi, Sangyeop Kim, Seungtaek Choi

## 概要
ツール使用LLMエージェントにおける**新しい攻撃ベクター**の発見。悪意あるMCPツールサーバーがoverthinkingループを誘発し、トークンとレイテンシを爆発的に増大させる。

## 技術的特徴
1. **Structural Overthinking Attack**: トークンレベルの冗長性とは異なる構造的攻撃
2. **3種類の攻撃パターン**: Repetition、Forced refinement、Distraction
3. **14種の悪意あるツール**: 3つのサーバーにわたって実装
4. **サプライチェーン攻撃**: 正常なツールと共存して検出困難

## 主要結果
- 異種レジストリと複数のツール対応モデルで評価
- **最大142.4倍のトークン増幅**
- タスク結果の劣化も確認
- Decoding時の簡潔性制御はループ誘発を防げない

## 注目ポイント
🎯 **エージェントセキュリティの重要な脆弱性**を特定、ツール呼び出し構造の防御が必要
