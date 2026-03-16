# Structured Distillation: エージェントメモリの11x圧縮

**arXiv**: [2603.13017](https://arxiv.org/abs/2603.13017)
**カテゴリ**: cs.AI, cs.CL, cs.IR

## 概要

AIエージェントとの長期会話履歴を**11倍圧縮**しながら検索品質を維持。構造化蒸留でパーソナライズされたエージェントメモリを効率化。

## 問題設定

- 1ユーザーとの会話履歴は有用だが、そのまま保持するとトークンコストが高い
- 単純な要約では検索品質が劣化

## 手法: Structured Distillation

各やり取りを4フィールドの複合オブジェクトに圧縮:
1. **exchange_core**: 核心
2. **specific_context**: 具体的コンテキスト
3. **thematic room_assignments**: テーマ別分類
4. **files_touched**: 正規表現抽出されたファイル

検索可能な蒸留テキスト: 平均**38トークン/やり取り**（元371トークン）

## 実験結果

- **データセット**: 6ソフトウェアプロジェクト、4,182会話、14,340やり取り
- **11x圧縮**: 371→38トークン
- **検索品質**: ベストMRR 0.717（verbatim最良の96%）
- **クロスレイヤー**: MRR 0.759でverbatimを上回る

## GitHub

https://github.com/Process-Point-Technologies-Corporation/searchat

## 注目ポイント

- 実用的なエージェントメモリ管理
- 214,519クエリ結果ペアで評価
- OSS公開
