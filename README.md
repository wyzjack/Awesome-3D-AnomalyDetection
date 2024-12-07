# Awesome-3D-ADL [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Anomaly detection and localization on 3D point cloud data has been a rising topic recently and has wide-range applications in real-world applications, especially in industrial scenarios. This repository summarizes the state-of-the-art methods and the related papers. The literature are listed in alphabet order for each section.

## Dataset 

<div align="center">
  <img src="figures/mvtec_3d-ad.png" width="800px" height="650px">
</div>

 **[MVTec 3D-AD]** | The MVTec 3D-AD Dataset for Unsupervised 3D Anomaly Detection and Localization | **VISAPP' 22** | [[pdf]](https://arxiv.org/pdf/2112.09045.pdf) [[website]](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)

<div align="center">
  <img src="figures/eyecandies.png" width="800px" height="650px">
</div>

 **[Eyecandies]** | The Eyecandies Dataset for Unsupervised Multimodal Anomaly Detection and Localization | **ACCV' 22** | [[pdf]](https://arxiv.org/pdf/2210.04570.pdf) [[website]](https://eyecan-ai.github.io/eyecandies)

<div align="center">
  <img src="figures/real3d-ad.png" width="800px" height="650px">
</div>
 
 **[Real3D-AD]** | Real3D-AD: A Dataset of Point Cloud Anomaly Detection | **NeurIPS' 23** | [[pdf]](https://arxiv.org/pdf/2309.13226.pdf) [[website]](https://github.com/M-3LAB/Real3D-AD)

## Unsupervised 3D Anomaly Detection (and Localization)

### Performance Comparison on MvTEC 3D 
| Time | Method | Image-level AUROC (%) | Pixel-level AUPRO (%) |
| --- | ------- | ----------- | ------- |
| 2021 | [3D-Only-Voxel-VM](#1)| 69.9   | 49.2  |
| 2021 | [3D+RGB-Voxel-VM](#1)| 51.7   | 63.9  |
| 2022 | [BTF](#2) | 86.5   | 96.4  |
| 2022 | [3D-ST](#3)| -   | 83.3 |
| 2022 | [RGB+PaDim](#4)| 76.4   |  93.0 |
| 2022 | [RGB+PatchCore](#4)| 81.1  | 91.0  |
| 2022 | [AST](#5) | 93.7   |   -   |
| 2022 | [PEFM](#6)|    -   | 94.2 |
| 2023 | [CDO](#7)| -   | 93.8 |
| 2023 | [M3DM](#8)| 94.5   | 96.4  |
| 2023 | [CPMF](#9)| **95.2**   | 92.9  |
| 2023 | [Shape-Guided](#10)| 94.7   | **97.6**  |

- <span id = "1">**[3D-Only-Voxel-VM,3D+RGB-Voxel-VM]** The MVTec 3D-AD Dataset for Unsupervised 3D Anomaly Detection and Localization</span> | **VISAPP' 22** | [[pdf]](https://arxiv.org/pdf/2112.09045.pdf) [[website]](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)
- <span id = "2">**[BTF]** Back to the Feature: Classical 3D Features are (Almost) All You Need for 3D Anomaly Detection</span>   | **arXiv' 22** | [[pdf]](https://arxiv.org/pdf/2203.05550.pdf) [[code]](https://github.com/eliahuhorwitz/3D-ADS)
- <span id = "3">**[3D-ST]** Anomaly Detection in 3D Point Clouds Using Deep Geometric Descriptors</span>   | **WACV' 23** | [[pdf]](https://openaccess.thecvf.com/content/WACV2023/papers/Bergmann_Anomaly_Detection_in_3D_Point_Clouds_Using_Deep_Geometric_Descriptors_WACV_2023_paper.pdf) 
- <span id = "4">**[RGB+PaDim,RGB+PatchCore]** Benchmarking Unsupervised Anomaly Detection and Localization</span>  | **arXiv' 22** | [[pdf]](https://arxiv.org/pdf/2205.14852.pdf) 
- <span id = "5">**[AST]** Asymmetric Student-Teacher Networks for Industrial Anomaly Detection</span>  | **WACV' 23** | [[pdf]](https://arxiv.org/pdf/2210.07829.pdf) [[code]](https://github.com/marco-rudolph/ast)
- <span id = "6">**[PEFM]** Position Encoding Enhanced Feature Mapping for Image Anomaly Detection</span>  | **IEEE 18th International Conference on Automation Science and Engineering (CASE)** | [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926547) 
- <span id = "7">**[CDO]** Collaborative Discrepancy Optimization for Reliable Image Anomaly Localization</span>   | **IEEE Transactions on Industrial Informatics** | [[pdf]](https://arxiv.org/pdf/2302.08769.pdf) [[code]](https://github.com/caoyunkang/CDO) 
- <span id = "8">**[M3DM]** Multimodal Industrial Anomaly Detection via Hybrid Fusion</span>  | **CVPR' 23** | [[pdf]](https://arxiv.org/pdf/2303.00601.pdf)  [[code]](https://github.com/nomewang/M3DM)
- <span id = "9">**[CPMF]** Complementary Pseudo Multimodal Feature for Point Cloud Anomaly Detection</span>   | **Pattern Recognition' 23 (under review)** | [[pdf]](https://arxiv.org/pdf/2303.13194.pdf) [[code]](https://github.com/caoyunkang/CPMF)
- <span id = "10">**[Shape-Guided]** Complementary Pseudo Multimodal Feature for Point Cloud Anomaly Detection</span>   | **ICML' 23** | [[pdf]](https://proceedings.mlr.press/v202/chu23b/chu23b.pdf) [[code]](https://github.com/jayliu0313/Shape-Guided)
- <span id = "11">**[IMRNet]** Towards Scalable 3D Anomaly Detection and Localization: A Benchmark via 3D
Anomaly Synthesis and A Self-Supervised Learning Network</span>   | **CVPR' 24** | [[pdf]](https://arxiv.org/pdf/2311.14897) [[code]](https://github.com/Chopper-233/Anomaly-ShapeNet)
- <span id = "12">**[Looking3D]** Looking 3D: Anomaly Detection with 2D-3D Alignment</span>   | **CVPR' 24** | [[pdf]](https://openaccess.thecvf.com/content/CVPR2024/papers/Bhunia_Looking_3D_Anomaly_Detection_with_2D-3D_Alignment_CVPR_2024_paper.pdf) [[code]](https://github.com/VICO-UoE/Looking3D)
- <span id = "13">**[R3D-AD]** R3D-AD: Reconstruction via Diffusion for 3D
Anomaly Detection</span>   | **ECCV' 24** | [[pdf]](https://arxiv.org/pdf/2407.10862)
- <span id = "14">**[DM-Multi-view-AD]** Learning Diffusion Models for Multi-View
Anomaly Detection</span>   | **ECCV' 24** | [[pdf]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04907.pdf) [[code]](https://github.com/jayliu0313/Diffusion_Multi-View_AD) 





## Zero-shot 3D Anomaly Detection (and Localization)
- <span id = "15">**[PointAD]** PointAD: Comprehending 3D Anomalies from Points and Pixels for Zero-shot 3D Anomaly Detection</span>   | **NeurIPS' 24** | [[pdf]](https://arxiv.org/pdf/2410.00320) [[code]](https://github.com/zqhang/PointAD)
- <span id = "16">**[3DzAL]** Towards Zero-shot 3D Anomaly Localization</span>   | **WACV' 25** | [[pdf]](https://arxiv.org/pdf/2412.04304) [[project page]](https://wyzjack.github.io/3DzAL/)

## Unified 3D Anomaly Detection (and Localization)
- <span id = "17">**[HGAD]** Hierarchical Gaussian Mixture Normalizing Flow
Modeling for Unified Anomaly Detection</span>   | **ECCV' 24** | [[pdf]](https://arxiv.org/pdf/2403.13349) [[code]](https://github.com/xcyao00/HGAD)


## 3D Anomaly Detection on Other Datasets

- Anomaly detection in 3D space for autonomous driving | **KIT Dissertation Paper** | [[PDF]](https://publikationen.bibliothek.kit.edu/1000148848/149058936)
- Toward Unsupervised 3d Point Cloud Anomaly Detection Using Variational Autoencoder | **ICIP' 21**| [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9506795)
  




