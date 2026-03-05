---
layout: paper
title: "Pointer-CAD: Unifying B-Rep and Command Sequences via Pointer-based Selection"
date: 2026-03-05
categories: [cs.CV, cs.CL]
---

# Pointer-CAD: Unifying B-Rep and Command Sequences via Pointer-based Edges & Faces Selection

**arXiv**: [2603.04337](https://arxiv.org/abs/2603.04337)  
**採択**: CVPR 2026

## 著者
Dacheng Qi, Chenyu Wang, Jingwei Xu, Tianzhe Chu, Zibo Zhao, Wen Liu, Wenrui Ding, Yi Ma, Shenghua Gao

## 一言まとめ
LLMベースCAD生成でエンティティ選択（面・エッジ）を実現。Pointer機構でB-Rep幾何情報をシーケンスモデリングに統合し、**トポロジーエラーを大幅削減**。

## 概要
LLMベースのCAD生成はコマンドシーケンス表現を使用するが、chamfer/filletのような複雑な編集操作に必要なエンティティ選択をサポートできない。また、連続変数の離散化は位相エラーを引き起こす。

### 主要な技術貢献
1. **Pointer-based command sequence**: B-Rep幾何情報を明示的にシーケンスモデリングに組み込み
2. **Step-by-step decomposition**: 各ステップをテキスト記述と前ステップB-Repで条件付け
3. **Data annotation pipeline**: 575K CADモデルのエキスパートレベル自然言語記述データセット

### 実験結果
- 複雑な幾何構造生成を効果的にサポート
- セグメンテーションエラー: 極めて低レベルに削減
- 従来のコマンドシーケンス手法を大幅に上回る
- 量子化エラーによる位相不正確さを大幅軽減

## キーワード
CAD Generation, LLM, B-Rep, Pointer Network, CVPR

## 選定理由
- CVPR 2026採択
- CAD×LLMの新しいアプローチ
- 実用的な産業応用可能性
