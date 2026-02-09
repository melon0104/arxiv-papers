# The Condensate Theorem: Transformers are O(n), Not O(n²)

**arXiv**: [2602.06317](https://arxiv.org/abs/2602.06317)  
**日付**: 2026-02-09  
**分野**: cs.LG（機械学習）  
**機関**: 独立研究

## 概要

「Condensate Theorem」を提示：アテンションスパース性は学習されたトポロジカル特性であり、アーキテクチャ的制約ではない。訓練済みLLMの分析により、アテンション質量が特定のトポロジカル多様体（Condensate Manifold）に集中することを発見。

## 技術的ポイント

- **Condensate Manifold**: Anchor + Window + Dynamic Top-k
- **100%出力等価性**: O(n²)フルアテンションと**ビット完全一致**
- **動的識別**: 全位置をチェックせずに多様体を識別可能
- **Topological Attention Kernel**: ハードウェア実装

## 結果

### 検証モデル
GPT-2, Pythia, Qwen2, TinyLlama, Mistral（1,500+トークン生成で検証）

### 性能
- **131Kトークン**: 628ms → 3.94ms（**159倍高速**）
- **1Mトークン（推定）**: **1,200倍以上**高速化
- **コスト削減**: Flash Attention比で**99.9%以上**削減

## 選定理由

- Transformer効率化の理論的ブレークスルー
- 二次ボトルネックが実装の問題であることを実証
