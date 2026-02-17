# PhyScensis: Physics-Augmented LLM Agents for Complex Physical Scene Arrangement

## 基本情報
- **arXiv**: [2602.14968](https://arxiv.org/abs/2602.14968)
- **カテゴリ**: cs.RO, cs.AI
- **投稿日**: 2026-02-16
- **著者**: Yian Wang, Han Yang, Minghao Guo, Xiaowen Qiu, Tsun-Hsuan Wang, Wojciech Matusik, **Joshua B. Tenenbaum**, Chuang Gan (MIT)
- **会議**: **ICLR 2026 採択**

## 概要
複雑な物理シーン配置のためのLLMエージェントベースフレームワーク。ロボット操作シミュレーションのスケールアップに必要な3D環境の自動生成を実現。

## 技術的特徴
1. **LLMエージェント**: 空間的・物理的述語を持つアセットを反復的に提案
2. **物理エンジン連携ソルバー**: 述語を3Dシーンとして実現
3. **フィードバックループ**: ソルバーからのフィードバックでエージェントが構成を改善
4. **確率的プログラミング**: 安定性を保証
5. **細粒度制御**: テキスト記述と数値パラメータ（相対位置、シーン安定性）

## 主要結果
- シーン複雑度、視覚品質、物理精度で従来手法を上回る
- 接触、支持、バランス、包含などの物理的関係をモデル化

## 注目ポイント
🎯 **MIT Tenenbaum研**によるICLR 2026採択論文、ロボットマニピュレーション用シーン生成の統一パイプライン
