# CoIn3D: Revisiting Configuration-Invariant Multi-Camera 3D Object Detection

**arXiv ID**: [2603.05042](https://arxiv.org/abs/2603.05042)

**カテゴリ**: cs.CV, cs.RO (コンピュータビジョン (CV))

**著者**: Zhaonian Kuang, Rui Ding, Haotian Wang, Xinhu Zheng, Meng Yang...

**投稿日**: 2026-03-05

---

## 概要

Multi-camera 3D object detection (MC3D) has attracted increasing attention with the growing deployment of multi-sensor physical agents, such as robots and autonomous vehicles. However, MC3D models still struggle to generalize to unseen platforms with new multi-camera configurations. Current solutions simply employ a meta-camera for unified representation but lack comprehensive consideration. In this paper, we revisit this issue and identify that the devil lies in spatial prior discrepancies across source and target configurations, including different intrinsics, extrinsics, and array layouts. To address this, we propose CoIn3D, a generalizable MC3D framework that enables strong transferability from source configurations to unseen target ones. CoIn3D explicitly incorporates all identified spatial priors into both feature embedding and image observation through spatial-aware feature modulation (SFM) and camera-aware data augmentation (CDA), respectively. SFM enriches feature space by integrating four spatial representations, such as focal length, ground depth, ground gradient, and Plücker coordinate. CDA improves observation diversity under various configurations via a training-free dynamic novel-view image synthesis scheme. Extensive experiments demonstrate that CoIn3D achieves strong cross-configuration performance on landmark datasets such as NuScenes, Waymo, and Lyft, under three dominant MC3D paradigms represented by BEVDepth, BEVFormer, and PETR.

---

## コメント

Accepted to CVPR 2026 main track

---

**リンク**: https://arxiv.org/abs/2603.05042
