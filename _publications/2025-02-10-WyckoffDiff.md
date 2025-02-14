---
title: "WyckoffDiff -- A Generative Diffusion Model for Crystal Symmetry"
collection: publications
category: preprints
permalink: /publication/2025-02-10-WyckoffDiff
excerpt: 'Discrete diffusion model for generating materials as descriptions of their symmetry properties'
date: 2025-02-10
venue: 'arXiv'
# slidesurl:
paperurl: 'https://arxiv.org/abs/2502.06485'
citation: 'Ekström Kelvinius, F., Andersson, O. B., Parackal, A. S., Qian, D., Armiento, R., & Lindsten, F. (2025). WyckoffDiff-A Generative Diffusion Model for Crystal Symmetry. arXiv preprint arXiv:2502.06485.'
---

Abstract:

Crystalline materials often exhibit a high level of symmetry. However, most generative models do not account for symmetry, but rather model each atom without any constraints on its position or element. We propose a generative model, Wyckoff Diffusion (WyckoffDiff), which generates symmetry-based descriptions of crystals. This is enabled by considering a crystal structure representation that encodes all symmetry, and we design a novel neural network architecture which enables using this representation inside a discrete generative model framework. In addition to respecting symmetry by construction, the discrete nature of our model enables fast generation. We additionally present a new metric, Fréchet Wrenformer Distance, which captures the symmetry aspects of the materials generated, and we benchmark WyckoffDiff against recently proposed generative models for crystal generation.