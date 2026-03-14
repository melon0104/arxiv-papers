# Spatial-TTT: Streaming Visual-based Spatial Intelligence with Test-Time Training

- **arXiv**: https://arxiv.org/abs/2603.12255
- **PDF**: https://arxiv.org/pdf/2603.12255
- **Project Page**: https://liuff19.github.io/Spatial-TTT
- **Categories**: cs.CV, cs.LG
- **Published**: 2026-03-12

## Authors
Fangfu Liu, Diankun Wu, Jiawei Chi, Yimo Cai, Yi-Hsin Hung, et al.

## Abstract
Humans perceive and understand real-world spaces through a **stream of visual observations**. Therefore, the ability to streamingly maintain and update spatial evidence from potentially unbounded video streams is essential for spatial intelligence.

The core challenge is not simply longer context windows but **how spatial information is selected, organized, and retained over time**.

## Spatial-TTT Framework
We propose **Spatial-TTT** towards streaming visual-based spatial intelligence with **test-time training (TTT)**:

### Approach
- Adapts a subset of parameters (**fast weights**) to capture and organize spatial evidence over long sequences
- **No retraining required**: Adapts on-the-fly during inference
- Handles potentially unbounded video streams

### Key Capabilities
- **Spatial memory**: Maintains coherent spatial understanding over time
- **Streaming processing**: No need to process entire videos at once
- **Adaptive**: Updates spatial model as new evidence arrives

## Applications
- 3D scene understanding
- Spatial navigation
- Long-horizon video comprehension
- Robotics perception

## Why Notable
- **Novel TTT for spatial tasks**: First application of test-time training to streaming spatial intelligence
- **Unbounded sequences**: Handles arbitrarily long video streams
- **Project page available**: Demos and code forthcoming
