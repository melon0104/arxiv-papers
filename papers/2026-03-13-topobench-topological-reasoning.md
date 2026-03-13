---
layout: paper
title: "TopoBench: Benchmarking LLMs on Hard Topological Reasoning"
date: 2026-03-13
arxiv_id: "2603.12133"
categories: [cs.AI, cs.CL]
---

# TopoBench: Topological Reasoning Benchmark

## 基本情報
- **arXiv ID**: 2603.12133
- **カテゴリ**: cs.AI, cs.CL
- **投稿日**: 2026年3月12日
- **注目ポイント**: 🏆 **ICLR 2026 Workshop採択** (Logical Reasoning of LLMs)

## 概要
トポロジカルグリッドパズルの解決は、接続性、ループ閉鎖、領域対称性などの大域的空間不変量上での推論を必要とし、最強のLLMでも困難。これを制御された設定で研究するベンチマーク「TopoBench」を提案。

## ベンチマーク構成
- **6つのパズルファミリー**
- **3つの難易度レベル**

## 主要な発見
- フロンティアモデルでも**困難インスタンスの25%未満**しか解けない
- 2つのファミリーは**ほぼ未解決**

## エラー分析
750のChain-of-Thoughtトレースを4つの候補失敗モードでアノテーション:
1. **早期コミットメント**: 直接的影響あり
2. **制約忘却**: 直接的影響あり
3. **繰り返し推論**: 探索の良性効果

## 緩和戦略
- プロンプトガイダンス
- セル整列グリッド表現
- ツールベース制約チェック

**結論**: ボトルネックは空間表現からの制約抽出にあり、制約上の推論自体ではない。

## リンク
- [arXiv](https://arxiv.org/abs/2603.12133)
- [GitHub](http://github.com/mayug/topobench-benchmark)
