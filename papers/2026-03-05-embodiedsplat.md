---
layout: paper
title: "EmbodiedSplat: Online Feed-Forward Semantic 3DGS"
date: 2026-03-05
categories: [cs.CV]
---

# EmbodiedSplat: Online Feed-Forward Semantic 3DGS for Open-Vocabulary 3D Scene Understanding

**arXiv**: [2603.04254](https://arxiv.org/abs/2603.04254)  
**採択**: CVPR 2026  
**プロジェクト**: https://0nandon.github.io/EmbodiedSplat/

## 著者
Seungjun Lee, Zihan Wang, Yunsong Wang, Gim Hee Lee

## 一言まとめ
ストリーミング画像からオンラインで3D再構成+セマンティック理解を同時実現。**CLIP Global Codebook**でメモリ効率化しつつ汎化性を保持。

## 概要
エンボディドタスクでは、エージェントは探索しながらオンライン・ほぼリアルタイムで3Dシーンを構築・理解する必要がある。既存のopen-vocabulary 3DGS手法はオフラインまたはper-scene最適化に限定。

### 主要な技術貢献
1. **Online Sparse Coefficients Field**: CLIP Global Codebookで2D CLIP埋め込みを各3D Gaussianにバインド
2. **3D Geometric-aware CLIP features**: 3D U-Netで部分点群を集約、2D指向言語埋め込みに3D幾何事前を補償
3. **Feed-forward design**: 300以上のストリーミング画像からシーン全体をオンライン再構成

### 実験結果
- **ScanNet, ScanNet++, Replica**:
  - 有効性と効率の両方で優れた性能
- メモリ消費: 最小化しつつCLIP汎化性を完全保持
- ほぼリアルタイム3Dセマンティック再構成

## キーワード
3D Gaussian Splatting, Open-Vocabulary, Embodied AI, CLIP, Online Learning

## 選定理由
- CVPR 2026採択
- エンボディドAI向け実用的技術
- オンライン処理の実現
