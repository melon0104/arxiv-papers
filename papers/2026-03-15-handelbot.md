# HandelBot: Real-World Piano Playing via Fast Adaptation of Dexterous Robot Policies

- **arXiv**: https://arxiv.org/abs/2603.12243
- **PDF**: https://arxiv.org/pdf/2603.12243
- **Project Page**: https://amberxie88.github.io/handelbot
- **Categories**: cs.RO
- **Published**: 2026-03-12

## Authors
Amber Xie, Haozhi Qi, Dorsa Sadigh (Stanford University)

## Abstract
Mastering dexterous manipulation with multi-fingered hands has been a **grand challenge in robotics** for decades. Despite its potential, the difficulty of collecting high-quality data remains a primary bottleneck for high-precision tasks.

While reinforcement learning and simulation-to-real-world transfer offer a promising alternative, the transferred policies often fail for tasks demanding **millimeter-scale precision**, such as bimanual piano playing.

## HandelBot Framework
We introduce **HandelBot**, a framework that combines a simulation policy and rapid adaptation through a **two-stage pipeline**:

### Stage 1: Simulation Policy
- Train robust piano-playing policy in simulation
- Learn general dexterous manipulation skills

### Stage 2: Fast Adaptation
Starting from a simulation-trained policy:
- Rapid adaptation to real-world piano
- Handles sim-to-real gap with minimal real-world data
- Achieves millimeter-precision required for piano keys

## Key Capabilities
- **Bimanual coordination**: Both hands play together
- **Millimeter precision**: Accurate key pressing
- **Musical expression**: Not just hitting keys but making music

## Results
- Successfully plays complex pieces in the real world
- Adapts quickly with few real-world trials
- Demonstrates sim-to-real transfer for precision tasks

## Why Notable
- **Stanford**: Top robotics research group (Dorsa Sadigh)
- **Impressive demo**: Piano playing requires extreme precision
- **Practical sim-to-real**: Addresses key challenge in robot learning
