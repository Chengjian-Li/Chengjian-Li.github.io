---
title:          "FTMoMamba: Motion Generation with Frequency and Text State Space Models"
date:           2024-11-26 00:01:00 +0800
selected:       false
# pub:            "IEEE Transactions on Instrumentation and Measurement"
# pub_pre:        "Submitted to "
pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  Diffusion models achieve impressive performance in human motion generation. However, current approaches typically ignore the significance of frequency-domain information in capturing fine-grained motions within the latent space (e.g., low frequencies correlate with static poses, and high frequencies align with fine-grained motions). Additionally, there is a semantic discrepancy between text and motion, leading to inconsistency between the generated motions and the text descriptions. In this work, we propose a novel diffusion-based FTMoMamba framework equipped with a Frequency State Space Model (FreqSSM) and a Text State Space Model (TextSSM). Specifically, to learn fine-grained representation, FreqSSM decomposes sequences into low-frequency and high-frequency components, guiding the generation of static pose (e.g., sits, lay) and fine-grained motions (e.g., transition, stumble), respectively. To ensure the consistency between text and motion, TextSSM encodes text features at the sentence level, aligning textual semantics with sequential features. Extensive experiments show that FTMoMamba achieves superior performance on the text-to-motion generation task, especially gaining the lowest FID of 0.181 (rather lower than 0.421 of MLD) on the HumanML3D dataset.
cover:          assets\images\covers\FTMomamba.jpg
authors:
  - Chengjian Li 
  - Xiangbo Shu
  - Qiongjie Cui
  - Yazhou Yao
  - Jinhui Tang

links:
    Paper: https://arxiv.org/abs/2411.17532
#   Code: https://github.com/luost26/bubble-visual-hash
#   Demo: https://luost26.github.io/bubble-visual-hash
---
