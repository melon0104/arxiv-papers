---
layout: paper
title: "AgenticOCR: Parsing Only What You Need for Efficient RAG"
date: 2026-03-02
arxiv_id: "2602.24134"
categories: [cs.CV, cs.CL]
github: "https://github.com/OpenDataLab/AgenticOCR"
---

# AgenticOCR: Parsing Only What You Need for Efficient Retrieval-Augmented Generation

## 基本情報
- **arXiv**: [2602.24134](https://arxiv.org/abs/2602.24134)
- **カテゴリ**: cs.CV, cs.CL
- **コード**: [GitHub](https://github.com/OpenDataLab/AgenticOCR)

## 概要
RAGがマルチモーダルに拡張され、財務報告書などの複雑な視覚文書処理が課題に。ページレベルチャンキングは過剰なコンテキストを生成器に渡し、attentionを過負荷にしてハルシネーションリスクを増加。本研究では**AgenticOCR**を提案。

## 主要貢献
1. **クエリ駆動オンデマンド抽出**: 静的なフルテキストOCRから動的パース paradigmへ
2. **"Thinking with Images"**: 文書レイアウトを自律的に分析、関心領域を選択的に認識
3. **視覚RAGの第3ビルディングブロック**: EmbeddingとRerankingモジュールを補完・強化

## 技術的特徴
- 必要な場所で視覚トークンをオンデマンドで解凍
- 検索粒度をページレベルチャンキングから分離
- 標準的なEmbedding/Rerankingモジュールと連携

## 実験結果
- 視覚RAGシステムの**効率と精度を同時改善**
- 長文書理解で**エキスパートレベル性能**達成

## 注目ポイント
📄 **文書理解**: 複雑な視覚文書のRAGを効率化
🎯 必要な部分だけをパース - 効率と精度の両立
🔧 **GitHub公開** - 実用可能なツール
