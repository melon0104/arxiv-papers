---
layout: paper
title: "Reasoning Models Struggle to Control their Chains of Thought"
date: 2026-03-09
categories: [cs.AI]
arxiv_id: "2603.05706"
---

# Reasoning Models Struggle to Control their Chains of Thought

## 基本情報
- **arXiv ID**: 2603.05706
- **カテゴリ**: cs.AI (Artificial Intelligence)
- **投稿日**: 2026-03-09

## 著者
Chen Yueh-Han, Robert McCarthy, Bruce W. Lee, He He, Ian Kivlichan, Bowen Baker, Micah Carroll, Tomek Korbak

## 概要
Chain-of-Thought (CoT) モニタリングは、現代の推論モデルにおける不正行為の検出と動機の理解に有望なツール。しかし、モデルがCoTで何を言語化するかを制御できれば、CoTのモニタリング可能性が損なわれる。

この望ましくない能力—**CoT制御可能性**—を測定するため、**CoT-Control評価スイート**を導入。

## 技術的詳細
評価タスク：モデルがCoT指示に従いながら問題を解くことを要求
- 例：遺伝学の質問に「chromosome」という単語を使わずに推論

複数のGPTモデルで複数回実行し、タスクごとに評価：
- クリーニングタスクとセマンティックタグ付けタスク
- 直接リクエスト vs インセンティブ条件
- モニタリング認知の有無

## 主要結果
**Claude Sonnet 4.5**での結果：
- CoT制御可能性: **2.7%**のみ
- 最終出力制御可能性: **61.9%**
- CoT制御可能性は出力制御可能性より**大幅に低い**

モデルサイズとCoT制御可能性の関係：
- より大きなモデルでCoT制御可能性が高い
- より多くのRLトレーニング、テスト時計算、問題難易度の増加でCoT制御可能性が**低下**

## 安全性への示唆
- CoTモニター回避のインセンティブを与えられた場合もCoT制御可能性は若干高い程度
- モニタリングされていると告げられた場合も若干高い制御可能性
- プロンプトの敵対的最適化でも制御可能性は意味のある増加なし

結果は**慎重に楽観的**：現在のCoT制御可能性はCoTモニタリング可能性の失敗モードになりにくい。ただし低い制御可能性のメカニズムは十分に理解されていない。

## 推奨事項
フロンティアラボは**将来のモデルでCoT制御可能性を追跡すべき**

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05706
