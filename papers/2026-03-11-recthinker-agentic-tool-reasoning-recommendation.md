# RecThinker: An Agentic Framework for Tool-Augmented Reasoning in Recommendation

## 基本情報
- **arXiv ID**: 2603.09843
- **タイトル**: RecThinker: An Agentic Framework for Tool-Augmented Reasoning in Recommendation
- **著者**: Haobo Zhang, Yutao Zhu, Kelong Mao, Tianhao Li, Zhicheng Dou
- **所属**: Renmin University of China
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.09843

## 概要
LLMベースの推薦エージェントは優れた推論と柔軟な意思決定を提供するが、既存手法は「パッシブな情報取得パラダイム」に留まっている。静的なワークフローや制限された情報での推論に依存し、情報の十分性を判断できないため、ユーザープロファイルやアイテムメタデータが断片的な場合に準最適な推薦を行う。

## 提案手法: RecThinker
**Analyze-Plan-Act**パラダイムを採用したエージェントフレームワーク：
1. まずユーザー・アイテム情報の十分性を分析
2. 情報ギャップを埋めるために自律的にツールを呼び出す
3. より良い推論・マッチングのための特化ツールスイートを開発

### ツールスイート
- **ユーザーサイド**: ユーザー情報の取得
- **アイテムサイド**: アイテムメタデータの取得
- **協調フィルタリング**: 協調情報の取得

### 学習パイプライン
- **Supervised Fine-Tuning (SFT)**: 高品質な推論軌跡の内部化
- **Reinforcement Learning (RL)**: 決定精度とツール使用効率の最適化

## 実験結果
複数のベンチマークデータセットで、RecThinkerは強力なベースラインを一貫して上回り、推薦シナリオでSOTA達成。

## 注目ポイント
- 🔧 **ツール拡張推論**: 推薦に特化したツールで情報ギャップを埋める
- 🤖 **自律的調査**: パッシブ処理から能動的調査へのパラダイムシフト
- 📈 **SFT+RLパイプライン**: 二段階学習で推論と効率を両立

## カテゴリ
cs.IR

## 関連タグ
#LLM推薦 #エージェント #ツール拡張 #推論 #情報検索
