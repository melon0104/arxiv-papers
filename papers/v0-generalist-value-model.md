# V0: A Generalist Value Model for Any Policy at State Zero

## 概要
LLMのActor-Critic学習（PPO等）において、Valueモデルのコスト問題を解決する汎用Value Modelを提案。

## 主要貢献
- **同期的更新不要**: ポリシー進化に追従するValue Model学習の高コストを排除
- 任意のポリシーに対して初期状態で適用可能な汎用設計
- 相対的アドバンテージ推定の効率化

## 技術詳細
- ポリシー勾配法におけるベースライン推定を改善
- ポリシーと同サイズのValueモデルの必要性を排除
- 非同期・汎用的なValue推定

## 注目ポイント
⚡ LLM強化学習の計算コスト削減に直結

## リンク
- arXiv: https://arxiv.org/abs/2602.03584
