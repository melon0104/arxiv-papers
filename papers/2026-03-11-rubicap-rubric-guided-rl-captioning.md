# RubiCap: Rubric-Guided Reinforcement Learning for Dense Image Captioning

## 基本情報
- **arXiv ID**: 2603.09160
- **タイトル**: RubiCap: Rubric-Guided Reinforcement Learning for Dense Image Captioning
- **著者**: Tzu-Heng Huang, Sirajul Salekin, Javier Movellan, Frederic Sala, Manjot Bilkhu
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.09160

## 概要
密な画像キャプショニングはビジョン-言語事前学習とテキスト-画像生成のクロスモーダルアライメントに不可欠だが、専門家品質のアノテーションのスケーリングは高コスト。強力VLMによる合成キャプショニングは実用的代替だが、教師あり蒸留は出力多様性が限定的で汎化が弱い。

RLはこれらの制限を克服できるが、その成功は**決定論的チェッカー**に依存する検証可能ドメインに集中しており、オープンエンドキャプショニングには適用困難。

## 提案手法: RubiCap
**LLM記述のルーブリックから細粒度でサンプル固有の報酬信号を導出**するRLフレームワーク：
1. 多様な候補キャプション委員会を構成
2. LLMルーブリックライターで合意の強みと現ポリシーの欠陥を抽出
3. 洞察を明示的評価基準に変換
4. LLMジャッジが構造化された多面的評価で粗いスカラー報酬を置換

## 実験結果
- **CapArena**: 全手法中最高勝率（教師あり蒸留、既存RL、人間専門家アノテーション、GPT-4V拡張出力を上回る）
- **CaptionQA**: 優れた単語効率（7Bで32B-Instructモデルにマッチ、3Bで7B超え）
- **事前学習への応用**: RubiCap-3Bキャプショナーでプロプライエタリモデルのキャプションより強力なVLMを事前学習

## 注目ポイント
- 📋 **ルーブリック駆動報酬**: オープンエンドタスクへのRL適用の新パラダイム
- 🏆 **人間専門家超え**: CapArenaでアノテーション品質を上回る
- ⚡ **効率的**: 小モデルで大モデル性能にマッチ

## カテゴリ
cs.CV, cs.AI, cs.LG

## 関連タグ
#画像キャプション #RL #ルーブリック #VLM #効率的学習
