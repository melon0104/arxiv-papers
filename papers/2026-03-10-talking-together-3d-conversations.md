---
layout: paper
title: "Talking Together: Synthesizing Co-Located 3D Conversations"
date: 2026-03-10
categories: [cs.CV, cs.GR]
arxiv_id: "2603.08252"
conference: "CVPR 2026"
---

# Talking Together: Synthesizing Co-Located 3D Conversations

## 基本情報
- **arXiv ID**: 2603.08252
- **カテゴリ**: cs.CV, cs.GR
- **投稿日**: 2026-03-09
- **採択**: CVPR 2026

## 著者
Mengdi Fan, Chen Zhang, Sifan Fu, Shiwen Wu, Shunlin Lu, Shi Qiu, Yi Zhou, Zhigang Tu

## 概要
人間の会話はコミュニケーション以上のもの：対話に伴う非言語的行動が豊かな意味を伝える。しかしほとんどの研究は**単体のジェスチャー生成**に焦点を当て、マルチスピーカー環境での**協調ダイナミクス**を無視。

**Talk Together**の提案：
- 非言語的キューが**マルチスピーカー設定でどのように調整されるか**を検証
- 会話シナリオにおける**複数人同期3D会話合成**

**主要貢献**：
1. **Talk Together Dataset**: 27,000クリップ以上、会話音声・転写・最大4人の同期SMPL-X動き
2. **TalkDiff**: 各参加者の正確なリップシンク・関連ジェスチャー・自然な全身動き・適切なインタラクションを生成

## 技術的詳細
- SMPLモデルによる3Dヒューマンポーズ表現
- 拡散モデルベースの生成
- マルチスピーカー協調の明示的モデリング

## 主要結果
- ジェスチャー・リップシンク・全身動き品質で既存手法を上回る
- 適切な相互インタラクションの生成
- 自然な会話ダイナミクスの再現

## 実用的意義
- バーチャルアバター会議システム
- 映画・ゲームでの群衆会話シーン生成
- ソーシャルVR/メタバース応用

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08252
