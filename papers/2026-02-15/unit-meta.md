# UniT: Unified Multimodal Chain-of-Thought Test-time Scaling

## メタ情報
- **arXiv ID**: 2602.12279
- **カテゴリ**: cs.CV, cs.AI, cs.LG
- **投稿日**: 2026-02-12
- **機関**: Meta, Stanford
- **著者**: Animesh Sinha, Xiaoliang Dai（Meta）, Serena Yeung-Levy（Stanford）他
- **注目理由**: 🏢 Meta + 🏫 Stanford

## 概要
マルチモーダル理解と生成を単一アーキテクチャで扱う統合モデル向けの、Chain-of-Thoughtテスト時スケーリングフレームワーク。複数ラウンドでの推論・検証・精緻化を実現。

## 主要貢献
1. **エージェント的データ合成**: 認知的振る舞いを引き出す学習データ生成
2. **テスト時の長推論チェーン汎化**: 短い推論軌跡での学習から長い推論チェーンへ汎化
3. **計算効率的TTS戦略**: 逐次CoT推論が並列サンプリングより効率的でスケーラブル

## 主要発見
- 生成・編集軌跡での学習が分布外視覚推論を改善
- マルチモーダルテスト時スケーリングが統合モデルの有効なパラダイムとして確立

## リンク
- 論文: https://arxiv.org/abs/2602.12279
