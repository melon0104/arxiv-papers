---
layout: paper
title: "Dr.Kernel: RL強化によるTritonカーネル生成"
date: 2026-02-07
arxiv_id: "2602.05885"
categories: [cs.LG, cs.CL, Code Generation]
---

# Dr. Kernel: Reinforcement Learning Done Right for Triton Kernel Generations

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.05885
- **著者**: Wei Liu, Jiawei Xu, **Junxian He** (HKUST) 他
- **機関**: HKUST NLP
- **コード**: https://github.com/hkust-nlp/KernelGYM

## 概要
GPUカーネル生成のための強化学習フレームワーク。リワードハッキングと怠惰な最適化を防ぎ、**Claude-4.5-Sonnet競争力のある性能**を達成。

## 技術的ポイント
- **KernelGYM**: 分散GPUでのRL訓練環境、リワードハッキング検出機能付き
- **TRLOO (Turn-level Reinforce-Leave-One-Out)**: GRPOのself-inclusionバイアスを解消
- **Profiling-based Rewards (PR)**: 怠惰な最適化を防止
- **Profiling-based Rejection Sampling (PRS)**: 訓練安定性向上

## 実験結果
| モデル | 1.2x高速化達成率 |
|--------|------------------|
| Claude-4.5-Sonnet | 26.7% |
| GPT-5 | 28.6% |
| **Dr.Kernel-14B** | **31.6%** |
| Dr.Kernel (best across turns) | **47.8%** |

## 注目ポイント
- **オープンソース14Bモデルが最先端プロプライエタリモデルを上回る**
- 環境・訓練コード・モデル・データセット全て公開
- AI for AI Systemsの実践的成果
