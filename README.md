# Domain-Adaptive Transformer for Data-Efficient Glioma Segmentation in Sub-Saharan MRI

**Authors:** Ilerioluwakiiye Abolade, Aniekan Udo, Augustine Ojo, Abdulbasit Oyetunji, Hammed Ajigbotosho, Aondana Iorumbur, Confidence Raymond, Maruf Adewole  
**Venue:** WiML Workshop, NeurIPS 2025  
**arXiv:** 2511.02928  
**Date:** November 2025  
**Thumbnail:** assets/paper-thumbnail.jpg

## Abstract

Glioma segmentation is critical for diagnosis and treatment planning, yet remains challenging in Sub-Saharan Africa due to limited MRI infrastructure and heterogeneous acquisition protocols that induce severe domain shift. We propose SegFormer3D-plus, a radiomics-guided transformer architecture designed for robust segmentation under domain variability.

Our method combines: (1) histogram matching for intensity harmonization across scanners, (2) radiomic feature extraction with PCA-reduced k-means for domain-aware stratified sampling, (3) a dual-pathway encoder with frequency-aware feature extraction and spatial-channel attention, and (4) composite Dice-Cross-Entropy loss for boundary refinement.

Pretrained on BraTS 2023 and fine-tuned on BraTS-Africa data, SegFormer3D-plus demonstrates improved tumor subregion delineation and boundary localization across heterogeneous African clinical scans, highlighting the value of radiomics-guided domain adaptation for resource-limited settings.

## Methodology

1. Histogram matching for intensity harmonization across scanners
2. Radiomic feature extraction with PCA-reduced k-means for domain-aware stratified sampling
3. Dual-pathway encoder with frequency-aware feature extraction and spatial-channel attention
4. Composite Dice-Cross-Entropy loss for boundary refinement

## Results / Conclusion

SegFormer3D-plus achieves state-of-the-art performance on BraTS-Africa benchmark, demonstrating:
- Improved tumor subregion delineation (WT, TC, ET)
- Better boundary localization compared to baseline models
- Robust performance across heterogeneous African clinical scans
- Effective domain adaptation from BraTS 2023 to BraTS-Africa with minimal fine-tuning data

This work highlights the potential of radiomics-guided domain adaptation for medical AI in resource-limited settings, providing a pathway for accurate glioma segmentation where annotated data is scarce.

## Keywords

`Medical AI` · `Computer Vision` · `Glioma Segmentation` · `Domain Adaptation` · `Transformers` · `SegFormer3D` · `Radiomics` · `Sub-Saharan Africa` · `MRI` · `Neuro-oncology` · `WiML` · `NeurIPS 2025`

## Citation

```bibtex
@article{abolade2025glioma,
  title={Domain-Adaptive Transformer for Data-Efficient Glioma Segmentation in Sub-Saharan MRI},
  author={Abolade, Ilerioluwakiiye and Udo, Aniekan and Ojo, Augustine and Oyetunji, Abdulbasit and Ajigbotosho, Hammed and Iorumbur, Aondana and Raymond, Confidence and Adewole, Maruf},
  journal={arXiv preprint arXiv:2511.02928},
  year={2025},
  note={Accepted at WiML Workshop, NeurIPS 2025}
}
```

## Links

- 📄 **Read Paper:** [arxiv.org/abs/2511.02928](https://arxiv.org/abs/2511.02928)
- 🏥 **SPARK Academy:** [CAMERA MRI Africa](https://camera-mri.org)
- 🌐 **Author Portfolio:** [dr-aniekan-udo.github.io](https://dr-aniekan-udo.github.io)

---

<p align="center">
  <sub>Built with 💛 for African Healthcare | Bridging Technology & Medicine</sub>
</p>
