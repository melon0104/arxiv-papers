# SAGEO Arena: A Realistic Environment for Evaluating Search-Augmented Generative Engine Optimization

[📄 arXiv:2602.12187](https://arxiv.org/abs/2602.12187)

## 概要
Search-Augmented Generative Engine (SAGE) 向けの最適化評価環境。既存ベンチマークの限界を克服し、現実的なSAGEO評価を可能にする。

## 課題認識
- 既存ベンチマークは事前選定された候補文書に依存
- 実際のWeb文書に存在する構造情報（スキーママークアップ等）を無視
- エンドツーエンドの可視性評価が不足

## 提案手法
**SAGEO Arena**：
- フル生成検索パイプラインを統合
- 大規模コーパス上でリッチな構造情報を保持
- 検索・リランキング・生成の各ステージを個別分析可能

## 主な発見
- 既存最適化手法は現実条件下で非実用的
- 検索・リランキングで性能低下が頻発
- 構造情報がこれらの限界を緩和
- 効果的なSAGEOは各パイプラインステージに合わせた最適化が必要

## 注目ポイント
- SEO + GEO を統合した新評価パラダイム
- AIベース検索時代の最適化指針

## カテゴリ
cs.IR, cs.AI
