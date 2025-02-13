---
title: "Accelerating Molecular Graph Neural Networks via Knowledge Distillation"
collection: publications
category: conferences
permalink: /publication/2023-12-12-Accelerating-Molecular-Graph-Neural-Networks-via-Knowledge-Distillation
excerpt: 'Using knowledge distillation for improving performance of molecular graph neural networks'
date: 2023-12-12
venue: 'Neural Information Processing Systems (NeurIPS)'
slidesurl: 'https://neurips.cc/virtual/2023/poster/72565'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/hash/51ec452ca04d8ec7160e5bbaf76153f6-Abstract-Conference.html'
citation: 'Ekström Kelvinius, F., Georgiev, D., Toshev, A., & Gasteiger, J. (2024). Accelerating molecular graph neural networks via knowledge distillation. *Advances in Neural Information Processing Systems, 36.*'
---

Abstract:

Recent advances in graph neural networks (GNNs) have enabled more comprehensive modeling of molecules and molecular systems, thereby enhancing the precision of molecular property prediction and molecular simulations. Nonetheless, as the field has been progressing to bigger and more complex architectures, state-of-the-art GNNs have become largely prohibitive for many large-scale applications. In this paper, we explore the utility of knowledge distillation (KD) for accelerating molecular GNNs. To this end, we devise KD strategies that facilitate the distillation of hidden representations in directional and equivariant GNNs, and evaluate their performance on the regression task of energy and force prediction. We validate our protocols across different teacher-student configurations and datasets, and demonstrate that they can consistently boost the predictive accuracy of student models without any modifications to their architecture. Moreover, we conduct comprehensive optimization of various components of our framework, and investigate the potential of data augmentation to further enhance performance. All in all, we manage to close the gap in predictive accuracy between teacher and student models by as much as 96.7\% and 62.5\% for energy and force prediction respectively, while fully preserving the inference throughput of the more lightweight models.