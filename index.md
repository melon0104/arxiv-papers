---
layout: default
title: Home
---

# arXiv AI Papers

検索・推薦・マッチング系のAI論文サマリー

---

## 2026-01-30 検索・マッチング特集

### 🔍 LEMUR: Learned Multi-Vector Retrieval
**[arXiv:2601.21853](https://arxiv.org/abs/2601.21853)**

ColBERTなどのlate interactionモデルはトークンごとに埋め込みを生成し、MaxSimで類似度を計算するため高精度だが、レイテンシが大きい課題があった。LEMURは2段階の問題変換でこれを解決：

1. マルチベクトル検索を1層NNの教師あり学習問題に定式化
2. その潜在空間での単一ベクトル検索に帰着させ、既存のANNSアルゴリズムを活用可能に

ColBERTv2だけでなく、最新のマルチベクトルテキストモデルや視覚文書検索モデルでも評価し、**従来手法より1桁高速化**を達成。

---

### 📊 LANCER: LLM Reranking for Nugget Coverage
**[arXiv:2601.22008](https://arxiv.org/abs/2601.22008)** | ECIR 2026

従来の検索は「関連度ランキング」に最適化されているが、レポート自動生成などのlong-form RAGでは「情報カバレッジ」が重要。LANCERは3ステップで動作：

1. 情報ニーズを満たすサブクエスチョンを予測
2. 各文書がどのサブクエスチョンに回答するか予測
3. 情報ナゲットを最大限カバーするようリランク

α-nDCGと情報カバレッジで他のLLMリランカーを上回る。**サブクエスチョン生成が性能の鍵**。

---

### 🎭 Rank-Nexus: When Vision Meets Texts in Listwise Reranking
**[arXiv:2601.20623](https://arxiv.org/abs/2601.20623)**

画像+テキストのマルチモーダル文書リランキングは、モダリティギャップとアラインドデータ不足が課題。既存手法は7B-32Bの大規模モデルに依存し計算コストが高い。

Rank-Nexusは段階的クロスモーダル訓練を提案：
1. テキストブランチは豊富なリランキングデータで蒸留
2. 画像ブランチはMLLMキャプションから蒸留ペアを構築
3. 最後に画像+テキスト統合データで蒸留

**2Bパラメータ**の軽量VLMでTREC/BEIR（テキスト）とINQUIRE/MMDocIR（画像）の両方で高性能。

---

### 🎯 SpecTran: Spectral-Aware Transformer-based Adapter
**[arXiv:2601.21986](https://arxiv.org/abs/2601.21986)**

逐次推薦モデルにLLMのセマンティック埋め込みを注入する際の課題：
- Adapter方式は次元崩壊（情報が少数次元に集中）
- SVD方式は主成分のみ使用し情報損失

SpecTranはスペクトル領域で動作するTransformerアダプタで、全スペクトルにattentionして有用な成分を選択・集約。学習可能なスペクトル位置エンコーディングが特異値情報を帰納バイアスとして注入し、次元間の多様性を促進。

4データセット×3バックボーンで**平均+9.17%改善**。

---

### 🛒 OneMall: End-to-End Generative Recommender at Kuaishou
**[arXiv:2601.21770](https://arxiv.org/abs/2601.21770)**

Kuaishou ECの生成的推薦フレームワーク。商品カード/ショート動画/ライブ配信を統一的に扱う。

**3つの柱：**
1. **E-commerce Semantic Tokenizer**: 実世界のセマンティクスとビジネス固有のアイテム関係を捉える
2. **Transformer基盤**: Query-Formerで長シーケンス圧縮、Cross-Attentionでマルチ行動シーケンス融合、Sparse MoEでスケーラブルな自己回帰生成
3. **RLパイプライン**: ランキングモデルを報酬信号として検索モデルをend-to-end最適化

**成果**: GMV+13%、注文+15%（動画）、+2.8%（ライブ）。4億DAUで運用中。

---

### 🧠 TREC 2025 Tip-of-the-Tongue Track Overview
**[arXiv:2601.20671](https://arxiv.org/abs/2601.20671)**

「あの映画、タイトル思い出せないけど、こういう内容で...」というknown-item検索タスク。

クエリが冗長で複雑な現象（曖昧な記憶、部分的情報、誤記憶など）を含むため既存IRには困難。2025年は一般ドメインに拡張し、以下の3種のテストセットを導入：
- MS-ToTデータセット
- 手動トピック開発
- LLM合成クエリ

9チーム32ランが参加。検索の「人間らしい」ユースケースへの対応が今後の課題。

---

## 2026-02-01 AI全般

### 🔐 RedSage
サイバーセキュリティ特化LLM。11.8B tokensのセキュリティデータで訓練。プライバシーリスクなしでオープンに使える点が実用的。

### 🖼️ pixel MeanFlow
1ステップで画像生成可能なflow model。latent空間を使わずpixel直接生成。推論の高速化に期待。

### 💎 Hidden Gems
HuggingFaceの2000+モデルを調査。人気モデルより優れた「隠れた名作」が多数存在することを実証。Llama-3.1-8Bでは人気上位より高性能なモデルを発見。

### 🧠 Hybrid Linear Attention
Transformerの知識蒸留でRNNブロックに変換。超長文脈を効率的に処理。

### 🤖 Agent-RRM
エージェントのRL訓練用報酬モデル。中間ステップの推論品質も評価でき、スパースな報酬の問題を解決。

### 🦾 DynamicVLA
動的物体のロボット操作向けVLAモデル。0.4Bとコンパクトながら、動く対象の把持に成功。
