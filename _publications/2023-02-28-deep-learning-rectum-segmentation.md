---
title: "Deep Learning-Based Rectum Segmentation on Low-field Prostate MRI to Assist Image-guided Biopsy"
collection: publications
category: conferences
permalink: /publication/2023-02-28-deep-learning-rectum-segmentation
excerpt: "This study presents a deep learning approach for automatic rectum segmentation in low-field (58–74 mT) prostate MRI scans. Utilizing a U-Net architecture, the model achieved a Dice similarity coefficient of 0.89, demonstrating its potential to enhance the accuracy and efficiency of image-guided prostate biopsies in low-resource settings."
date: 2023-02-28
venue: 'Proceedings of SPIE, Medical Imaging 2023: Image-Guided Procedures, Robotic Interventions, and Modeling'
paperurl: 'https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12466/1246623/Deep-learning-based-rectum-segmentation-on-low-field-prostate-MRI/10.1117/12.2654511.full'
citation: 'Pham, H., Le, D. B. T., Sadinski, M., Narayanan, R., Nacev, A., & Zheng, B. (2023). "Deep Learning-Based Rectum Segmentation on Low-field Prostate MRI to Assist Image-guided Biopsy." In <i>Proceedings of SPIE</i>, Vol. 12466, Medical Imaging 2023: Image-Guided Procedures, Robotic Interventions, and Modeling. https://doi.org/10.1117/12.2654511'
---

This study evaluates whether radiomics features from CT scans can predict 5-year survival in gastric cancer patients.

- **Data**: 406 patient CT scans; 168 survived, 238 did not.
- **Approach**: Tumor segmentation followed by extraction of 103 radiomics features using PyRadiomics.
- **Two Methods**:
  - **2D**: Features from a single CT slice.
  - **Quasi-3D**: Weighted average features from multiple slices.
- **Feature Reduction**: PCA reduced features to 11 (2D) and 7 (3D).
- **Models Tested**: Logistic Regression (LRM), ANN, and SVM.
- **Best Performance**: LRM with quasi-3D features (AUC = 0.72), but not significantly better than 2D (AUC = 0.70, p = 0.21).

### Conclusion