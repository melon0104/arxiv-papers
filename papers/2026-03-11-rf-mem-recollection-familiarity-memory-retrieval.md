# RF-Mem: Recollection-Familiarity Memory Retrieval for Personalized LLMs

## 基本情報
- **arXiv ID**: 2603.09250
- **タイトル**: Evoking User Memory: Personalizing LLM via Recollection-Familiarity Adaptive Retrieval
- **著者**: Yingyi Zhang, Junyi Li, Wenlin Zhang, Penyue Jia, Xianneng Li 他
- **所属**: University of Illinois Chicago, Tsinghua University
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.09250

## 概要
パーソナライズLLMはメモリ検索に依存するが、既存手法は全履歴をプロンプトに投入（コスト高・スケール不可）するか、単純な類似度検索（表層マッチングのみ）に頼る。認知科学では、人間の記憶は**二重プロセス**で動作：
- **Familiarity**: 高速だが粗い認識
- **Recollection**: 意図的な連鎖的再構成

## 提案手法: RF-Mem
**Familiarity不確実性ガイド型二経路メモリ検索器**：
1. 平均スコアとエントロピーでFamiliarity信号を測定
2. 高Familiarity → 直接Top-K検索
3. 低Familiarity → Recollectionパス：
   - 候補メモリをクラスタリング
   - α-mixでクエリと反復的に証拠を展開
   - 意図的な文脈再構成をシミュレート

## 実験結果
3つのベンチマークとコーパススケールで、RF-Memは固定予算・レイテンシ制約下で：
- ワンショット検索より高性能
- フルコンテキスト推論より効率的

## 注目ポイント
- 🧠 **認知科学ベース**: 人間の記憶メカニズムをLLMに適用
- ⚡ **適応的切り替え**: 不確実性に応じて検索戦略を動的選択
- 📈 **スケーラブル**: フルコンテキストのオーバーヘッドを回避

## カテゴリ
cs.IR

## 関連タグ
#パーソナライズ #メモリ検索 #認知科学 #LLM #適応的検索
