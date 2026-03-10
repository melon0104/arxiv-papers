---
layout: paper
title: "CARE-Edit: Condition-Aware Routing of Experts for Contextual Image Editing"
date: 2026-03-10
categories: [cs.CV]
arxiv_id: "2603.08024"
conference: "CVPR 2026"
---

# CARE-Edit: Condition-Aware Routing of Experts for Contextual Image Editing

## 基本情報
- **arXiv ID**: 2603.08024
- **カテゴリ**: cs.CV
- **投稿日**: 2026-03-09
- **採択**: CVPR 2026

## 著者
Zeyu Liu, Yihan Hu, Yunyao Mao, Jun-Yan Zhu

## 概要
文脈に応じた画像編集は、編集のタイプ、粒度、影響範囲で自然に異なる多様なユーザー要件を持つ。既存モデルは特定の編集タイプに特化するか、限られたシナリオで汎用的に扱うかのいずれか。

**CARE-Edit**の提案：
- **Condition-Aware Routing of Experts**により異質な編集タスクを処理
- 入力条件を動的に分析し、最適なエキスパートサブセットを活性化

**主要貢献**：
1. **多様な編集タイプ**（属性変更、オブジェクト追加/削除、背景変更など）の統一処理
2. **粒度・影響範囲の動的調整**
3. **MoEアーキテクチャ**による効率的な専門化

## 技術的詳細
- Mixture of Experts (MoE) ベースのアーキテクチャ
- 条件認識ルーティング機構
- 拡散モデルとの統合

## 主要結果
- 複数の編集タイプで一貫した高品質
- 特化モデルの精度 + 汎用モデルの柔軟性
- 効率的な推論（スパースエキスパート活性化）

## 実用的意義
- 統一画像編集ツールの開発
- ユーザー意図に応じた適応的編集
- 写真編集・クリエイティブツールへの応用

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08024
