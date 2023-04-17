# Awesome-3D-AnomalyDetection [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Anomaly detection on 3D point cloud data has been a rising topic recently and has wide-range applications in real-world applications, especially industrial manufacturing. This repository summarizes the state-of-the-art methods and the related papers.

### Dataset 

<div align="center">
  <img src="figures/mvtec_3d-ad.png" width="600px" height="350px">
</div>

 **[MVTec 3D-AD]** | The MVTec 3D-AD Dataset for Unsupervised 3D Anomaly Detection and Localization | **VISAPP' 22** | [[pdf]](https://arxiv.org/pdf/2112.09045.pdf) [[website]](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)

### Unsupervised 3D Anomaly Detection (and Localization) on MVTEC 3D Dataset
- <span id = "01">**[3D-Only-Voxel-VM, 3D+RGB-Voxel-VM]** The MVTec 3D-AD Dataset for Unsupervised 3D Anomaly Detection and Localization</span> | **VISAPP' 22** | [[pdf]](https://arxiv.org/pdf/2112.09045.pdf) [[website]](https://www.mvtec.com/company/research/datasets/mvtec-3d-ad)
- <span id = "01">**[M3DM]** Multimodal Industrial Anomaly Detection via Hybrid Fusion</span>  | **CVPR' 23** | [[pdf]](https://arxiv.org/pdf/2303.00601.pdf)  [[code]](https://github.com/nomewang/M3DM)
- <span id = "01">**[CPMF]** Complementary Pseudo Multimodal Feature for Point Cloud Anomaly Detection</span>   | **Pattern Recognition' 23 (under review)** | [[pdf]](https://arxiv.org/pdf/2303.13194.pdf) [[code]](https://github.com/caoyunkang/CPMF)
- **[BTF]** Back to the Feature: Classical 3D Features are (Almost) All You Need for 3D Anomaly Detection   | **arXiv' 22** | [[pdf]](https://arxiv.org/pdf/2203.05550.pdf) [[code]](https://github.com/eliahuhorwitz/3D-ADS)
- **[CDO]** Collaborative Discrepancy Optimization for Reliable Image Anomaly Localization   | **IEEE Transactions on Industrial Informatics** | [[pdf]](https://arxiv.org/pdf/2302.08769.pdf) [[code]](https://github.com/caoyunkang/CDO) 
- **[3D-ST]** Anomaly Detection in 3D Point Clouds Using Deep Geometric Descriptors   | **WACV' 23** | [[pdf]](https://openaccess.thecvf.com/content/WACV2023/papers/Bergmann_Anomaly_Detection_in_3D_Point_Clouds_Using_Deep_Geometric_Descriptors_WACV_2023_paper.pdf) 
- Benchmarking Unsupervised Anomaly Detection and Localization  | **arXiv' 22** | [[pdf]](https://arxiv.org/pdf/2205.14852.pdf) 
- Asymmetric Student-Teacher Networks for Industrial Anomaly Detection  | **WACV' 23** | [[pdf]](https://arxiv.org/pdf/2303.13194.pdf) [[code]](https://github.com/marco-rudolph/ast)
- Position Encoding Enhanced Feature Mapping for Image Anomaly Detection  | ** IEEE 18th International Conference on Automation Science and Engineering (CASE)** | [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926547) 

### 3D Anomaly Detection on Other Datasets
- Anomaly detection in 3D space for autonomous driving | **** |
  
## Performance Comparison on MvTEC 3D 
| Method | Image-level AUROC (%) | Pixel-level AUPRO (%) |
| ------- | ----------- | ------- |
| [M3DM](#01)| 94.5   | 96.4  |
| [CPMF](#02)| 95.2   | 92.9  |
| [CPMF](#02)| 95.2   | 92.9  |
| AST | 93.7   |       |
| BTF | 86.5   | 95.9  |
| PEFM|        | 94.2 |
｜ ｜ 81.1｜ 93.0｜


