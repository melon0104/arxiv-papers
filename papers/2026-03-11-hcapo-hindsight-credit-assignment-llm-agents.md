# HCAPO: Hindsight Credit Assignment for Long-Horizon LLM Agents

## 基本情報
- **arXiv ID**: 2603.08754
- **タイトル**: Hindsight Credit Assignment for Long-Horizon LLM Agents
- **著者**: Hui-Ze Tan, Xiao-Wen Yang, Hao Chen, Jie-Jing Shao, Yi Wen 他
- **所属**: Nanjing University, ByteDance
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.08754

## 概要
LLMエージェントは長期マルチステップタスクでスパース報酬による重大なクレジット割り当て問題に直面。GRPO（Group Relative Policy Optimization）などの既存の値フリー手法には2つの根本的ボトルネック：
1. 不正確なステップレベルQ値推定
2. 中間状態での誤整列した値ベースライン

## 提案手法: HCAPO
**Hindsight Credit Assignment**をLLMエージェントに初めて統合したフレームワーク：
1. LLM自身を事後批評家として活用
2. 後知恵推論でステップレベルQ値を精緻化
3. **マルチスケールアドバンテージ機構**: 重要な決定状態での不正確な値ベースラインを補完

## 実験結果
WebShop、ALFWorldを含む3つの挑戦的ベンチマークで評価：
- WebShopで成功率**+7.7%**（GRPO比、Qwen2.5-7B-Instruct）
- ALFWorldで成功率**+13.8%**
- 探索効率の大幅向上
- 簡潔な意思決定を促進

## 注目ポイント
- 🎯 **ByteDance共著**: 産学連携研究
- 🔄 **後知恵クレジット割り当て**: LLMエージェント初適用
- 📊 **複雑タスク**: 長期マルチステップでスケーラビリティ実証

## カテゴリ
cs.LG, cs.AI

## 関連タグ
#LLMエージェント #強化学習 #クレジット割り当て #GRPO #ByteDance
