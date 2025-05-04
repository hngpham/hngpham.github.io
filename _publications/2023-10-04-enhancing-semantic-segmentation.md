---
title: "Enhancing Semantic Segmentation through Reinforced Active Learning: Combating Dataset Imbalances and Bolstering Annotation Efficiency"
collection: publications
category: manuscripts
permalink: /publication/2023-10-04-enhancing-semantic-segmentation
excerpt: "This study introduces a reinforced active learning framework for semantic segmentation, integrating techniques such as Dueling Deep Q-Networks, Prioritized Experience Replay, and Noisy Networks. The approach addresses dataset imbalances and annotation efficiency, demonstrating improved segmentation performance with reduced labeling efforts."
date: 2023-10-04
venue: 'Journal of Electronic & Information Systems'
paperurl: '/files/2023-10-04-enhancing-semantic-segmentation.pdf'
citation: 'Han, D., Pham, H., & Cheng, S. (2023). "Enhancing Semantic Segmentation through Reinforced Active Learning: Combating Dataset Imbalances and Bolstering Annotation Efficiency." <i>Journal of Electronic & Information Systems</i>, 5(2), 45–60. https://doi.org/10.30564/jeis.v5i2.6063'
---

This paper presents a novel framework called **Reinforced Active Learning (RAL)** to enhance semantic segmentation performance under limited annotation resources and class imbalance.

### Key Contributions

- **Reinforcement Learning-Based Sample Selection**  
  RAL employs a reinforcement learning agent to identify the most informative and diverse samples for annotation. The reward function is designed to improve segmentation performance while addressing class imbalance.

- **Class Imbalance-Aware Sampling Strategy**  
  Introduces a metric that accounts for class distribution, encouraging the selection of samples that include rare or underrepresented classes. This leads to better performance across all categories.

- **Annotation Efficiency**  
  RAL achieves high segmentation accuracy with fewer labeled samples, reducing the cost and time associated with manual annotation.

- **Experimental Validation**  
  The framework was tested on datasets like **Cityscapes** and **ACDC**, where it outperformed conventional active learning methods in both efficiency and accuracy.

### Conclusion

RAL effectively balances the need for performance and annotation efficiency, particularly in imbalanced datasets, making it a strong candidate for practical semantic segmentation applications.
