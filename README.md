# Awesome-3D-AnomalyDetection [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Anomaly detection on 3D point cloud data has been a rising topic recently and has wide-range applications in real-world applications, especially in industrial scenarios. This repository summarizes the state-of-the-art methods and the related papers. The literature are listed in alphabet order for each section.

## Dataset 

<div align="center">
  <img src="figures/mvtec_3d-ad.png" width="800px" height="650px">
</div>

 **[MVTec 3D-AD]** | The MVTec 3D-AD Dataset for Unsupervised 3D Anomaly Detection and Localization | **VISAPP' 22** | [[pdf]](https://arxiv.org/pdf/2112.09045.pdf) [[website]](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)

## Unsupervised 3D Anomaly Detection (and Localization) on MVTec 3D-AD Dataset

### Performance Comparison on MvTEC 3D 
| Time | Method | Image-level AUROC (%) | Pixel-level AUPRO (%) |
| --- | ------- | ----------- | ------- |
| 2021 | [3D-Only-Voxel-VM](#1)| 69.9   | 49.2  |
| 2021 | [3D+RGB-Voxel-VM](#1)| 51.7   | 63.9  |
| 2022 | [BTF](#2) | 86.5   | **96.4**  |
| 2022 | [3D-ST](#3)| -   | 83.3 |
| 2022 | [RGB+PaDim](#4)| 76.4   |  93.0 |
| 2022 | [RGB+PatchCore](#4)| 81.1  | 91.0  |
| 2022 | [AST](#5) | 93.7   |   -   |
| 2022 | [PEFM](#6)|    -   | 94.2 |
| 2023 | [CDO](#7)| -   | 93.8 |
| 2023 | [M3DM](#7)| 94.5   | **96.4**  |
| 2023 | [CPMF](#8)| **95.2**   | 92.9  |

- <span id = "1">**[3D-Only-Voxel-VM,3D+RGB-Voxel-VM]** The MVTec 3D-AD Dataset for Unsupervised 3D Anomaly Detection and Localization</span> | **VISAPP' 22** | [[pdf]](https://arxiv.org/pdf/2112.09045.pdf) [[website]](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)
- <span id = "2">**[BTF]** Back to the Feature: Classical 3D Features are (Almost) All You Need for 3D Anomaly Detection</span>   | **arXiv' 22** | [[pdf]](https://arxiv.org/pdf/2203.05550.pdf) [[code]](https://github.com/eliahuhorwitz/3D-ADS)
- <span id = "3">**[3D-ST]** Anomaly Detection in 3D Point Clouds Using Deep Geometric Descriptors</span>   | **WACV' 23** | [[pdf]](https://openaccess.thecvf.com/content/WACV2023/papers/Bergmann_Anomaly_Detection_in_3D_Point_Clouds_Using_Deep_Geometric_Descriptors_WACV_2023_paper.pdf) 
- <span id = "4">**[RGB+PaDim,RGB+PatchCore]** Benchmarking Unsupervised Anomaly Detection and Localization</span>  | **arXiv' 22** | [[pdf]](https://arxiv.org/pdf/2205.14852.pdf) 
- <span id = "5">**[AST]** Asymmetric Student-Teacher Networks for Industrial Anomaly Detection</span>  | **WACV' 23** | [[pdf]](https://arxiv.org/pdf/2210.07829.pdf) [[code]](https://github.com/marco-rudolph/ast)
- <span id = "6">**[PEFM]** Position Encoding Enhanced Feature Mapping for Image Anomaly Detection</span>  | **IEEE 18th International Conference on Automation Science and Engineering (CASE)** | [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926547) 
- <span id = "7">**[CDO]** Collaborative Discrepancy Optimization for Reliable Image Anomaly Localization</span>   | **IEEE Transactions on Industrial Informatics** | [[pdf]](https://arxiv.org/pdf/2302.08769.pdf) [[code]](https://github.com/caoyunkang/CDO) 
- <span id = "8">**[M3DM]** Multimodal Industrial Anomaly Detection via Hybrid Fusion</span>  | **CVPR' 23** | [[pdf]](https://arxiv.org/pdf/2303.00601.pdf)  [[code]](https://github.com/nomewang/M3DM)
- <span id = "9">**[CPMF]** Complementary Pseudo Multimodal Feature for Point Cloud Anomaly Detection</span>   | **Pattern Recognition' 23 (under review)** | [[pdf]](https://arxiv.org/pdf/2303.13194.pdf) [[code]](https://github.com/caoyunkang/CPMF)

## 3D Anomaly Detection on Other Datasets

- Anomaly detection in 3D space for autonomous driving | **KIT Dissertation Paper** | [[PDF]](https://publikationen.bibliothek.kit.edu/1000148848/149058936)
- Toward Unsupervised 3d Point Cloud Anomaly Detection Using Variational Autoencoder | **ICIP' 21**| [[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9506795)
  




