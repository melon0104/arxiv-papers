# CATTS: Confidence-Aware Test-Time Scaling for WebAgents

## メタ情報
- **arXiv ID**: 2602.12276
- **カテゴリ**: cs.AI, cs.CL
- **投稿日**: 2026-02-12
- **機関**: UC Berkeley
- **著者**: Kurt Keutzer, Michael W. Mahoney他
- **注目理由**: 🏫 UC Berkeley

## 概要
Webエージェント向けの信頼度認識テスト時スケーリング技術。マルチステップエージェントタスクでの推論時スケーリングの挙動を分析し、動的計算割り当てを実現。

## 主要貢献
1. **投票分布からの不確実性統計**: エントロピーとtop-1/top-2マージンが下流成功と相関
2. **動的計算割り当て**: 本当に争点となる決定にのみ計算を割り当て
3. **LLMベースArbiter**: ナイーブ投票を上回る集約戦略

## 実験結果
- **WebArena-Lite/GoBrowse**: Reactより最大+9.1%
- **トークン効率**: 均一スケーリングの2.3倍少ないトークンで達成
- 効率性向上と解釈可能な決定ルールを両立

## リンク
- 論文: https://arxiv.org/abs/2602.12276
