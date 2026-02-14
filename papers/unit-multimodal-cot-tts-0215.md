# UniT: Unified Multimodal Chain-of-Thought Test-time Scaling

[📄 arXiv:2602.12279](https://arxiv.org/abs/2602.12279)

## 概要
統一マルチモーダルモデルのテストタイムスケーリングを実現。理解と生成を単一アーキテクチャで処理しつつ、複数ラウンドで推論・検証・精緻化。

## 提案手法
**UniT**：
- **Agentic data synthesis**：エージェント型データ合成
- **Unified model training**：統一モデル訓練
- **Flexible test-time inference**：柔軟なテストタイム推論
- 検証・サブゴール分解・コンテンツ記憶などの認知的振る舞いを引き出す

## 主な発見
1. 短い推論軌跡で訓練したモデルが、テストタイムに**長い推論チェーンに汎化**
2. 逐次的Chain-of-Thought推論が並列サンプリングより**スケーラブルで計算効率的**
3. 生成・編集軌跡での訓練が**分布外視覚推論を改善**

## 注目ポイント
- 👥 Felix Juefei-Xu氏（Meta関連）他
- マルチモーダルテストタイムスケーリングの新パラダイム
- 生成と理解の両方を向上

## カテゴリ
cs.CV, cs.AI, cs.LG
