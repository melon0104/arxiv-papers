# CoVer: Contrastive Verifier for Vision-Language-Action Alignment

[📄 arXiv:2602.12281](https://arxiv.org/abs/2602.12281)

## 概要
汎用ロボットの「意図-行動ギャップ」を解消するテストタイム検証。VLAモデルの生成行動が指示と不整合になる問題に対処。

## 提案手法
**CoVer (Contrastive Verifier)**：
- テストタイムスケーリング則を特定：言い換え指示数×生成行動数のスケーリングがサンプル多様性を大幅に増加
- 計算リソース・データでスケールする対照的検証器アーキテクチャ
- **Boot-time compute**：デプロイ前にVLMで多様な言い換え指示を事前計算
- **階層的検証推論パイプライン**：最適な高レベルプロンプト＋低レベル行動チャンクを選択

## 実験結果
- SIMPLERベンチマーク：
  - In-distribution: **+22%**（ポリシー事前訓練比）
  - Out-of-distribution: **+13%**
- 実世界実験: **+45%**
- PolaRiSベンチマーク：タスク進行**+14%**、成功率**+9%**

## 注目ポイント
- VLAのテストタイムスケーリング
- 検証によるポリシースケーリングの代替
- 実世界での大幅な性能向上

## カテゴリ
cs.RO, cs.AI, eess.SY
