---
title: "Discriminator Guidance for Autoregressive Diffusion Models"
collection: publications
category: conferences
permalink: /publication/2024-05-03-Discriminator-Guidance-for-Autoregressive-Diffusion-Models
excerpt: 'Three versions of discriminator guidance for autoregressive (diffusion) models'
date: 2024-05-04
venue: 'The 28th International Conference on Artificial Intelligence and Statistics (AISTATS)'
# slidesurl: 'https://neurips.cc/virtual/2023/poster/72565'
paperurl: 'https://proceedings.mlr.press/v238/ekstrom-kelvinius24a.html'
citation: 'Ekström Kelvinius, F. &amp; Lindsten, F.. (2024). Discriminator Guidance for Autoregressive Diffusion Models. <i>Proceedings of The 27th International Conference on Artificial Intelligence and Statistics</i>, in <i>Proceedings of Machine Learning Research</i> 238:3403-3411 Available from https://proceedings.mlr.press/v238/ekstrom-kelvinius24a.html.'
---

Abstract:

We introduce discriminator guidance in the setting of Autoregressive Diffusion Models. The use of a discriminator to guide a diffusion process has previously been used for continuous diffusion models, and in this work we derive ways of using a discriminator together with a pretrained generative model in the discrete case. First, we show that using an optimal discriminator will correct the pretrained model and enable exact sampling from the underlying data distribution. Second, to account for the realistic scenario of using a sub-optimal discriminator, we derive a sequential Monte Carlo algorithm which iteratively takes the predictions from the discriminator into account during the generation process. We test these approaches on the task of generating molecular graphs and show how the discriminator improves the generative performance over using only the pretrained model.