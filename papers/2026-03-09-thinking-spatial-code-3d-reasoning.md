---
layout: paper
title: "Thinking with Spatial Code for Physical-World Video Reasoning"
date: 2026-03-09
categories: [cs.CV]
arxiv_id: "2603.05591"
---

# Thinking with Spatial Code for Physical-World Video Reasoning

## 基本情報
- **arXiv ID**: 2603.05591
- **カテゴリ**: cs.CV (Computer Vision)
- **投稿日**: 2026-03-09
- **コード**: https://github.com/Beckschen/spatialcode

## 著者
Jieneng Chen, Wenxin Ma, Ruisheng Yuan, Yunzhi Zhang, Jiajun Wu, Alan Yuille

## 概要
RGB動画を明示的で時間的に一貫した3D表現に変換するフレームワーク**Thinking with Spatial Code**を導入。物理世界のビジュアル質問応答のために設計。

## 技術的詳細
**Spatial Encoder**を提案：
- 画像と幾何学的特徴をエンコード
- 6Dオブジェクト解析・追跡バックボーンと幾何学予測を統合
- 動画フレームを明示的3D向き境界ボックスとセマンティックラベルを持つ構造化**空間コード**に解析

LLMがこれらの空間変数上で直接推論可能：
- **GRPO（Group Relative Policy Optimization）** による強化学習でファインチューニング
- 視点認識、幾何学的根拠付け推論を奨励する**空間ルブリック報酬**

## 主要結果
**VSI-Bench**（空間推論ベンチマーク）で評価：
- プロプライエタリなVision-Languageモデルを**上回る新SOTA**達成
- 明示的3D表現が空間推論タスクで優位性を示す

## 実用的意義
- ロボティクスでの空間理解
- 自動運転の環境認識
- AR/VRでの物理世界インタラクション
- ビデオ理解・質問応答システム
- 3D空間での論理的推論

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05591
- GitHub: https://github.com/Beckschen/spatialcode
