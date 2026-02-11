# Code2World: A GUI World Model via Renderable Code Generation

## 基本情報
- **arXiv**: [2602.09856](https://arxiv.org/abs/2602.09856)
- **カテゴリ**: cs.CV, cs.AI, cs.CL, cs.HC
- **投稿日**: 2026-02-10
- **機関**: AMAP-ML (高徳地図)
- **コード**: [GitHub](https://github.com/AMAP-ML/Code2World)

## 一言まとめ
GUIエージェント向けWorld Modelをレンダリング可能コード生成で実現。AndroidWorldナビで**Gemini-2.5-Flash+9.5%**向上。

## 概要
自律GUIエージェントはインターフェース認識とアクション実行で相互作用。GUIワールドモデルは人間のような先見性を提供するが、既存のテキスト・ピクセルベース手法は視覚的忠実度と構造的制御性の両立が困難。

## 技術的貢献
- **レンダリング可能コード生成**: 次の視覚状態をコード生成でシミュレート
- **AndroidCodeデータセット**: GUI軌跡を高忠実度HTMLに変換、80K以上の高品質スクリーン-アクションペア
- **視覚フィードバック修正**: 合成コードをレンダリング結果で改善
- **Render-Aware強化学習**: レンダリング結果を報酬信号として使用

## 実験結果
- 次のUI予測でSOTA達成（GPT-5、Gemini-3-Pro-Imageに匹敵）
- AndroidWorldナビでGemini-2.5-Flash比**+9.5%**向上
- 下流ナビゲーションを柔軟に改善

## 選定理由
✅ 有名機関 (AMAP/Alibaba系)
✅ コード公開 (GitHub)
