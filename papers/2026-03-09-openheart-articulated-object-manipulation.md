---
layout: paper
title: "OpenHEART: Opening Heterogeneous Articulated Objects with a Legged Manipulator"
date: 2026-03-09
categories: [cs.RO]
arxiv_id: "2603.05830"
---

# OpenHEART: Opening Heterogeneous Articulated Objects with a Legged Manipulator

## 基本情報
- **arXiv ID**: 2603.05830
- **カテゴリ**: cs.RO (Robotics)
- **投稿日**: 2026-03-09
- **プロジェクトページ**: https://openheart-icra.github.io/OpenHEART/

## 著者
Seonghyeon Lim, Hyeonwoo Lee, Seunghyun Lee, I Made Aswin Nahrendra, Hyun Myung

## 概要
脚付きマニピュレータは高い機動性と多様な操作を提供するが、ドア、引き出し、キャビネットなど**異種関節オブジェクト**との堅牢なインタラクションは、オブジェクトの多様な関節タイプと脚ロボットの複雑なダイナミクスのため困難が残る。

**OpenHEART**フレームワークを提案：強化学習ベースのアプローチで、異種関節オブジェクトの開閉操作を実現。

## 技術的詳細
**SAFE (Sampling-based Abstracted Feature Extraction)** を提案：
- ハンドルとパネルの幾何学を低次元表現にコンパクトにエンコード
- クロスドメイン汎化を改善

**ArtIEst (Articulation Information Estimator)** を導入：
- 固有受容感覚と外受容感覚を適応的にミックス
- 各オブジェクトの開閉方向と可動範囲を推定

## 主要結果
シミュレーションと実世界ロボットシステムで多様な異種関節オブジェクトの操作を検証：
- 様々なタイプのドア、引き出し、キャビネットに対応
- 実世界への転移成功

## 実用的意義
- 家庭・オフィス環境でのロボット操作
- 脚ロボットの実用的応用拡大
- 多様なオブジェクトへの汎化能力
- 移動マニピュレーションの高度化

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05830
- プロジェクトページ: https://openheart-icra.github.io/OpenHEART/
