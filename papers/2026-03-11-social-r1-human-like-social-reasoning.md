# Social-R1: Towards Human-like Social Reasoning in LLMs

## 基本情報
- **arXiv ID**: 2603.09249
- **タイトル**: Social-R1: Towards Human-like Social Reasoning in LLMs
- **著者**: Jincenzi Wu, Yuxuan Lei, Jianxun Lian, Yitian Huang 他
- **所属**: Chinese University of Hong Kong, Microsoft Research Asia
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.09249

## 概要
LLMは多数のドメインで顕著な能力を示すが、**社会的知性**（社会的手がかりの知覚、精神状態の推論、適切な応答生成）は依然として重大な課題。現在のモデルは真の社会的推論ではなく表層パターンに依存することが多い。

人間のような社会的知性を養うには、**ショートカット解法に抵抗する困難なケース**での訓練が必要と主張。

## ToMBench-Hard
社会的推論のハード訓練例を提供するために設計された**敵対的ベンチマーク**を導入。

## 提案手法: Social-R1
**多次元報酬を通じてモデル推論を人間の認知に整合させる**RLフレームワーク：
- 結果ベースRLと異なり、**推論プロセス全体を監督**
- 構造的アラインメント
- 論理的整合性
- 情報密度

## 実験結果
- 4Bパラメータモデルがはるかに大きなモデルを上回る
- 8つの多様なベンチマークで堅牢に汎化
- 困難な訓練ケース＋軌跡レベルアラインメントが効率的で信頼性のある社会的知性への道筋を提供

## 注目ポイント
- 🧠 **Microsoft Research Asia共著**: Theory of Mind研究
- 🎯 **ハード例学習**: ショートカット解法を防止
- 📊 **8ベンチマーク汎化**: 堅牢な社会的推論能力

## カテゴリ
cs.AI

## 関連タグ
#社会的推論 #TheoryOfMind #RL #LLM #Microsoft
