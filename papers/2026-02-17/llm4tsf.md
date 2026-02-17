# Rethinking the Role of LLMs in Time Series Forecasting

## 基本情報
- **arXiv**: [2602.14744](https://arxiv.org/abs/2602.14744)
- **カテゴリ**: cs.CL
- **投稿日**: 2026-02-16
- **著者**: Xin Qiu, Junlong Tong, Yirong Sun, Yunpu Ma, Wei Zhang, Xiaoyu Shen
- **コード**: [GitHub](https://github.com/EIT-NLP/LLM4TSF)

## 概要
「LLMは時系列予測に本当に役立たないのか？」という疑問に大規模実験で回答。既存研究の否定的結論は限定的な評価設定に起因すると主張。

## 技術的特徴
1. **大規模スタディ**: 80億観測値、17予測シナリオ、4ホライズン
2. **複数アライメント戦略**: Pre-alignmentとPost-alignmentの比較
3. **In-domain/Out-of-domain設定**: 汎化性能の詳細分析
4. **トークンレベルルーティング分析**: LLMの貢献を解析

## 主要結果
- **LLM4TSは予測性能を改善する**ことを実証（既存の否定的評価を覆す）
- 特に**クロスドメイン汎化で大きな効果**
- Pre-alignmentが90%以上のタスクでPost-alignmentを上回る
- 事前学習知識とアーキテクチャが相補的役割を果たす
- 大規模混合分布下では完全なLLMが不可欠

## 注目ポイント
🎯 **LLM時系列予測の否定的評価を覆す**大規模実証研究、実装公開
