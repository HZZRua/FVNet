# FVNet: Harnessing Liquid Neural Dynamics for Lightweight Visual Representation

This repository contains the official implementation for our paper:

> **FVNet: Harnessing Liquid Neural Dynamics for Lightweight Visual Representation**<br>

## 📢 News

*   **[2025-11]** Our paper, FVNet, has been accepted by AAAI 2026! 🎉
*   **[2025-11]** The initial repository has been created. We are organizing the code and will release it soon.

## 🚀 Introduction

Efficient visual backbone design remains crucial for resource-constrained computer vision applications. Inspired by the adaptive continuous-time dynamics observed in biological neurons, we propose FVNet, a novel lightweight architecture that integrates liquid neural dynamics for efficient and dynamic visual feature extraction. Central to FVNet is the Fluid Temporal Flow Unit (FTFU), which employs continuous-time equations with learnable time constants to capture spatio-temporal dependencies adaptively. By further stacking these units in a Multi-Phase Fluid Block (MPFB), our model processes features across parallel temporal scales, enabling context-aware feature encoding without incurring excessive computational overhead. Through a discrete closed-form solution, FVNet achieves the representational power of continuous-time models while avoiding the instability and overhead of iterative numerical solvers. Extensive experiments on various vision tasks demonstrate that FVNet achieves superior performance and efficiency over existing state-of-the-art lightweight networks.

## 💻 Code Release

The source code, pretrained models, and experiment configurations are currently being organized.
**The code will be released here soon**


## 🙏 Citation

If you find our work useful for your research, please consider citing our paper:

```bibtex
@inproceedings{fvnet2026aaai,
  title     = {FVNet: Harnessing Liquid Neural Dynamics for Lightweight Visual Representation},
  author    = {Zhenzhe Hou and Xiaohui Chu1 and Runze Hu and Yang Li and Yutao Liu},
  booktitle = {AAAI Conference on Artificial Intelligence},
  year      = {2026}
}
```
