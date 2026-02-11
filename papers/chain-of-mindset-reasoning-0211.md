# Chain of Mindset: Reasoning with Adaptive Cognitive Modes

## 基本情報
- **arXiv**: [2602.10063](https://arxiv.org/abs/2602.10063)
- **カテゴリ**: cs.AI
- **投稿日**: 2026-02-10
- **コード**: [GitHub](https://github.com/QuantaAlpha/chain-of-mindset)

## 一言まとめ
人間の認知モード切替を模倣した推論フレームワーク。Qwen3-VL-32Bで**+4.96%**、推論効率とのバランスを実現。

## 概要
人間の問題解決は単一のマインドセット（認知処理モード）の繰り返しではなく、解決過程で複数のマインドセットを統合。しかし既存のLLM推論手法は全ステップに同一のマインドセットを適用し、段階ごとに異なるマインドセットが必要という事実を見落としている。

## 技術的貢献
- **4つの機能的マインドセット**: Spatial、Convergent、Divergent、Algorithmic
- **Meta-Agent**: 推論状態に基づき最適なマインドセットを動的選択
- **双方向Context Gate**: モジュール間情報フローをフィルタリングし効果性・効率性を維持
- **訓練不要のエージェンティックフレームワーク**

## 実験結果
- 6つのベンチマーク（数学、コード、科学QA、空間推論）でSOTA
- Qwen3-VL-32B-Instructで総合精度**+4.96%**
- Gemini-2.0-Flashで**+4.72%**
- 推論効率とのバランスを達成

## 選定理由
✅ コード公開 (GitHub)
✅ 幅広いベンチマークで検証
