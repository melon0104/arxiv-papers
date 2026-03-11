# Scale-Plan: Scalable Language-Enabled Task Planning for Multi-Robot Teams

## 基本情報
- **arXiv ID**: 2603.08814
- **タイトル**: Scale-Plan: Scalable Language-Enabled Task Planning for Heterogeneous Multi-Robot Teams
- **著者**: Piyush Gupta, Sangjae Bae, Jiachen Li, David Isele
- **所属**: Honda Research Institute USA
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.08814

## 概要
異種マルチロボットシステムの長期タスク計画は協調チームの実世界展開に不可欠だが、知覚情報の大量性（多くはタスク目標と無関係）が計画の負担となり困難。従来のシンボリックプランナーは手動構築の問題仕様に依存しスケーラビリティと適応性に限界。最近のLLMベースアプローチはハルシネーションとオブジェクトリッチ環境での弱いグラウンディング（生成計画と実際の環境オブジェクト・制約のミスマッチ）に苦戦。

## 提案手法: Scale-Plan
**スケーラブルなLLMアシスト型フレームワーク**で自然言語指示からコンパクトでタスク関連の問題表現を生成：
1. PDDLドメイン仕様からアクショングラフを構築（ドメイン構造をキャプチャ）
2. 浅いLLM推論で構造化グラフ探索をガイド
3. 関連アクションとオブジェクトの最小サブセットを特定
4. 計画前に無関係情報をフィルタリング

## 効果
効率的な分解、割り当て、長期計画生成を可能に。

## 評価
複雑なマルチエージェントタスクで評価し、AI2-THOR上に構築した**MAT2-THOR**ベンチマーク（マルチロボット計画システム用のクリーンベンチマーク）を導入。Scale-Planは純LLMおよびハイブリッドLLM-PDDLベースラインを全指標で上回り、スケーラビリティと信頼性を向上。

## 注目ポイント
- 🏭 **Honda Research**: 産業応用を意識した研究
- 🤖 **異種ロボット**: 異なる能力を持つロボットの協調
- 📐 **PDDL統合**: シンボリック計画とLLMのハイブリッド

## カテゴリ
cs.RO, cs.AI

## 関連タグ
#マルチロボット #タスク計画 #LLM #PDDL #Honda
