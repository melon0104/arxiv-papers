# Modeling Distinct Human Interaction in Web Agents

- **arXiv ID**: 2602.17588
- **カテゴリ**: cs.CL, cs.HC
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.17588

## 著者
Faria Huq, Zora Zhiruo Wang, Zhanqiu Guo, Venu Arvind Arangarajan, Tianyue Ou, Frank Xu, Shuyan Zhou, **Graham Neubig**, Jeffrey P. Bigham

## 選定理由
✅ **有名研究機関**: CMU (Graham Neubig)

## 概要
Webエージェントにおける人間の介入パターンをモデル化し、協調的なタスク実行を支援。ユーザーインタラクションスタイルに基づいて介入タイミングを予測する言語モデルを学習。

## 主要な貢献
1. **CowCorpus**: 400の実ユーザーWeb navigation軌跡（4,200+の人間・エージェント交互アクション）
2. **4つの介入パターン**: Hands-off supervision、Hands-on oversight、Collaborative task-solving、Full user takeover
3. **Intervention-aware Models**: 介入予測精度61.4-63.4%改善（ベースLM比）

## 実験結果
- **ユーザースタディ**: エージェント有用性が**26.5%向上**
- 4,200+のinterleaved human-agent actionsを含むデータセット

## 技術的詳細
- ユーザーのinteraction styleに基づく介入予測
- Live web navigationでデプロイ・評価

## 関連研究
- Web agents
- Human-AI collaboration
- Interactive machine learning
