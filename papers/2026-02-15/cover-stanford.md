# CoVer: Scaling Verification Can Be More Effective than Scaling Policy Learning for Vision-Language-Action Alignment

## メタ情報
- **arXiv ID**: 2602.12281
- **カテゴリ**: cs.RO, cs.AI
- **投稿日**: 2026-02-12
- **機関**: Stanford
- **著者**: Chelsea Finn, Marco Pavone他
- **注目理由**: 🏫 Stanford（Finn, Pavone）+ VLA最新研究

## 概要
Vision-Language-Action（VLA）モデルの「意図-行動ギャップ」を縮小するテスト時検証フレームワーク。ポリシー事前学習のスケーリングより検証のスケーリングが効果的であることを実証。

## 主要貢献
1. **テスト時スケーリング則**: 言い換え指示と生成行動の同時スケーリングがサンプル多様性を大幅向上
2. **CoVer**: 対照的検証器によるVLAアライメント
3. **ブート時計算**: 階層的検証推論パイプライン

## 実験結果
- **SIMPLER**: 分布内+22%、分布外+13%（ポリシースケーリング比）
- **実世界実験**: さらに+45%改善
- **PolaRiS**: タスク進捗+14%、成功率+9%

## リンク
- 論文: https://arxiv.org/abs/2602.12281
