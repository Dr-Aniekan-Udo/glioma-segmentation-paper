# Domain-Adaptive Transformer for Data-Efficient Glioma Segmentation in Sub-Saharan MRI

[![arXiv](https://img.shields.io/badge/arXiv-2511.02928-f59e0b?style=flat-square&logo=arxiv&logoColor=white&labelColor=0a0a0a)](https://arxiv.org/abs/2511.02928)
[![WiML](https://img.shields.io/badge/WiML-NeurIPS_2025-0a0a0a?style=flat-square&logoColor=f59e0b&labelColor=0a0a0a)]()
[![Python](https://img.shields.io/badge/Python-3.10+-0a0a0a?style=flat-square&logo=python&logoColor=f59e0b&labelColor=0a0a0a)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-0a0a0a?style=flat-square&logo=pytorch&logoColor=f59e0b&labelColor=0a0a0a)](https://pytorch.org)
[![Medical AI](https://img.shields.io/badge/Medical_AI-Computer_Vision-0a0a0a?style=flat-square&logoColor=f59e0b&labelColor=0a0a0a)]()

> **Accepted at WiML Workshop, NeurIPS 2025** | SPARK Academy by CAMERA MRI Africa | Nov 2025

## Authors

**Ilerioluwakiiye Abolade**, **Aniekan Udo**, Augustine Ojo, Abdulbasit Oyetunji, Hammed Ajigbotosho, Aondana Iorumbur, Confidence Raymond, Maruf Adewole

## Overview

Glioma segmentation is critical for diagnosis and treatment planning, yet remains challenging in Sub-Saharan Africa due to limited MRI infrastructure and heterogeneous acquisition protocols that induce severe domain shift. We propose **SegFormer3D-plus**, a radiomics-guided transformer architecture designed for robust segmentation under domain variability.

## Problem Statement

- **Limited MRI Infrastructure**: Sub-Saharan Africa faces scarcity of advanced MRI scanners and trained radiologists
- **Heterogeneous Protocols**: Different scanners and acquisition settings create severe domain shift between institutions
- **Data Scarcity**: Insufficient annotated datasets for training robust deep learning models
- **Clinical Impact**: Inaccurate segmentation compromises treatment planning and patient outcomes

## Our Solution: SegFormer3D-plus

### Architecture Components

Our method combines four key innovations:

### 1. Histogram Matching for Intensity Harmonization
Standardizes intensity distributions across different MRI scanners to reduce inter-scanner variability.

### 2. Radiomic Feature Extraction with PCA-Reduced K-Means
- Extracts radiomic features from MRI volumes
- Applies PCA dimensionality reduction
- Uses k-means clustering for domain-aware stratified sampling
- Ensures balanced representation across different acquisition protocols

### 3. Dual-Pathway Encoder
- **Frequency-aware feature extraction**: Captures multi-scale frequency information
- **Spatial-channel attention**: Focuses on relevant anatomical regions and feature channels
- Transformer-based architecture for global context modeling

### 4. Composite Dice-Cross-Entropy Loss
Combines Dice coefficient and Cross-Entropy loss for:
- Improved boundary refinement
- Better handling of class imbalance
- Enhanced tumor subregion delineation

## Datasets

- **Pre-training**: BraTS 2023 (Brain Tumor Segmentation Challenge)
- **Fine-tuning**: BraTS-Africa data (Sub-Saharan African clinical scans)
- **Modalities**: Multi-modal MRI (T1, T1ce, T2, FLAIR)

## Results

SegFormer3D-plus demonstrates:
- ✅ Improved tumor subregion delineation
- ✅ Better boundary localization
- ✅ Robust performance across heterogeneous African clinical scans
- ✅ Effective domain adaptation from BraTS 2023 to BraTS-Africa

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Deep Learning Framework | PyTorch 2.0+ |
| Medical Imaging | MONAI, NiBabel, SimpleITK |
| Vision Transformers | SegFormer3D architecture |
| Radiomics | PyRadiomics |
| Data Processing | NumPy, Pandas, Scikit-learn |
| Visualization | Matplotlib, Seaborn |

## Citation

If you use this work in your research, please cite:

```bibtex
@article{abolade2025glioma,
  title={Domain-Adaptive Transformer for Data-Efficient Glioma Segmentation in Sub-Saharan MRI},
  author={Abolade, Ilerioluwakiiye and Udo, Aniekan and Ojo, Augustine and Oyetunji, Abdulbasit and Ajigbotosho, Hammed and Iorumbur, Aondana and Raymond, Confidence and Adewole, Maruf},
  journal={arXiv preprint arXiv:2511.02928},
  year={2025},
  note={Accepted at WiML Workshop, NeurIPS 2025}
}
```

## Publication Details

- **arXiv**: [2511.02928](https://arxiv.org/abs/2511.02928)
- **Date**: November 4, 2025
- **Venue**: Women in Machine Learning (WiML) Workshop at NeurIPS 2025
- **Pages**: 4 pages, 2 figures
- **Subjects**: Image and Video Processing (eess.IV); Computer Vision and Pattern Recognition (cs.CV)

## Related Links

- 📄 **Read Full Paper**: [arxiv.org/abs/2511.02928](https://arxiv.org/abs/2511.02928)
- 🏥 **SPARK Academy**: [CAMERA MRI Africa](https://camera-mri.org)
- 🌐 **Author Portfolio**: [dr-aniekan-udo.github.io](https://dr-aniekan-udo.github.io)
- 💼 **LinkedIn**: [Aniekan Etim Udo](https://www.linkedin.com/in/aniekan-etim-udo)

## Keywords

`Medical AI` · `Computer Vision` · `Glioma Segmentation` · `Domain Adaptation` · `Transformers` · `SegFormer3D` · `Radiomics` · `Sub-Saharan Africa` · `Healthcare Technology` · `MRI` · `Neuro-oncology` · `WiML` · `NeurIPS 2025`

---

<p align="center">
  <sub>Built with 💛 for African Healthcare | Bridging Technology & Medicine</sub>
</p>
