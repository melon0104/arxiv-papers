# CM2: Reinforcement Learning with Checklist Rewards for Multi-Turn and Multi-Step Agentic Tool Use

## メタ情報
- **arXiv ID**: 2602.12268
- **カテゴリ**: cs.AI
- **投稿日**: 2026-02-12
- **注目理由**: 💻 コード公開 + エージェント的ツール使用

## 概要
マルチターン・マルチステップのエージェント的ツール使用向けRL フレームワーク。検証可能報酬をチェックリスト報酬で置き換え、オープンエンドな振る舞いを安定した分類スタイルの判定に変換。

## 主要貢献
1. **チェックリスト報酬**: 各ターンの意図を細粒度バイナリ基準に分解
2. **スパース報酬・密評価**: 安定性と情報量のバランス
3. **LLMシミュレート環境**: 大規模ツールセット向けのスケーラブルな学習

## 実験結果
- **τ-Bench**: SFT比 +8ポイント
- **BFCL-V4**: SFT比 +10ポイント
- **ToolSandbox**: SFT比 +12ポイント
- 判定モデルを含む同サイズベースラインと同等以上

## リンク
- 論文: https://arxiv.org/abs/2602.12268
- コード: https://github.com/namezhenzhang/CM2-RLCR-Tool-Agent
