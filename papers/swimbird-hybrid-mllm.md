---
layout: paper
title: "SwimBird: ハイブリッドMLLMの切替可能推論モード"
date: 2026-02-07
arxiv_id: "2602.06040"
categories: [cs.CV, MLLM, Reasoning]
---

# SwimBird: Eliciting Switchable Reasoning Mode in Hybrid Autoregressive MLLMs

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06040
- **著者**: Jintao Tong, Shilin Yan, Hongwei Xue 他
- **プロジェクト**: https://accio-lab.github.io/SwimBird

## 概要
入力に応じて**3つの推論モードを動的に切り替える**MLLM。テキストベースの論理推論と視覚集約タスクの両方で強力な性能を発揮。

## 3つの推論モード
1. **テキストのみ推論**: 従来のCoTスタイル
2. **視覚のみ推論**: 連続隠れ状態を「視覚的思考」として活用
3. **インターリーブ視覚-テキスト推論**: 両者を交互に使用

## 技術的ポイント
- **ハイブリッド自己回帰**: テキスト思考はnext-token予測、視覚思考はnext-embedding予測
- **SwimBird-SFT-92K**: 3つの推論パターンをカバーする多様なSFTデータセット
- **クエリ適応的モード選択**: 固定パターンの制限を克服

## 注目ポイント
- 既存の固定パターンマルチモーダル推論手法を上回る
- テキスト推論能力を維持しつつ視覚タスクを大幅改善
- 柔軟なモード切り替えという新しいパラダイム
