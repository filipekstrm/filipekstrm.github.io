---
title: "Graph-based machine learning beyond stable materials and relaxed crystal structures"
collection: publications
category: manuscripts
permalink: /publication/2022-03-11-Graph-based-machine-learning-beyond-stable-materials-and-relaxed-crystal-structures
excerpt: 'Evaluating the performance of a GNN for crystals in a high-throughput search setting, and proposing an ML-assisted workflow'
date: 2022-03-11
venue: 'Physical Review Materials'
# slidesurl:
paperurl: 'https://doi.org/10.1103/PhysRevMaterials.6.033801'
citation: 'Ekström Kelvinius, F., Armiento, R., & Lindsten, F. (2022). Graph-based machine learning beyond stable materials and relaxed crystal structures. Physical Review Materials, 6(3), 033801.'
---

Abstract:

There has been a recent surge of interest in using machine learning to approximate density functional theory in materials science. However, many of the most performant models are evaluated on large databases of computed properties of, primarily, materials with precise atomic coordinates available, and which have been experimentally synthesized, i.e., which are thermodynamically stable or metastable. These aspects provide challenges when applying such models on theoretical candidate materials, for example for materials discovery, where the coordinates are not known. To extend the scope of this methodology, we investigate the performance of the crystal graph convolutional neural network on a data set of theoretical structures in three related ternary phase diagrams (Ti,Zr,Hf)-Zn-N, which thus include many highly unstable structures. We then investigate the impact on the performance of using atomic positions that are only partially relaxed into local energy minima. We also explore options for improving the performance in these scenarios by transfer learning, either from models trained on a large database of mostly stable systems, or a different but related phase diagram. Models pretrained on stable materials do not significantly improve performance, but models trained on similar data transfer very well. We demonstrate how our findings can be utilized to generate phase diagrams with a major reduction in computational effort.