---
title: "SMAFormer: Synergistic Multi-Attention Transformer for Medical Image Segmentation"
collection: publications
category: conferences
permalink: /publication/SMAFormer
excerpt: 'This paper is about small tumors and organs Segmentation Problem.'
date: 2024-08-16
venue: 'IEEE International Conference on Bioinformatics and Biomedicine (BIBM)'
paperurl: 'http://lzeeorno.github.io/files/SMAFormer_IEEE_BIBM2024.pdf'
citation: 'comming soon'
---

In medical image segmentation, specialized computer vision techniques, notably transformers grounded in attention mechanisms and residual networks employing skip connections, have been instrumental in advancing performance. Nonetheless, previous models often falter when segmenting small, irregularly shaped tumors. To this end, we introduce SMAFormer, an efficient, Transformer-based architecture that fuses multiple attention mechanisms for enhanced segmentation of small tumors and organs.
SMAFormer can capture both local and global features for medical image segmentation. The architecture comprises two pivotal components. First, a Synergistic Multi-Attention (SMA) Transformer block is proposed, which has the benefits of Pixel Attention, Channel Attention, and Spatial Attention for feature enrichment. Second, addressing the challenge of information loss incurred during attention mechanism transitions and feature fusion, we design a Feature Fusion Modulator. This module bolsters the integration between the channel and spatial attention by mitigating reshaping-induced information attrition.
To evaluate our method, we conduct extensive experiments on various medical image segmentation tasks, including multi-organ, liver tumor, and bladder tumor segmentation, achieving state-of-the-art results. Code and models are available at:[address](https://github.com/lzeeorno/SMAFormer).
