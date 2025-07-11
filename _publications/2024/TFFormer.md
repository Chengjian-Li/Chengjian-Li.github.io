---
title:          "DRLFormer: A Data Rebalancing Loss Constrained Light Transformer For OSA 
                Detection"
date:           2024-08-8 00:01:00 +0800
selected:       true
pub:            "IEEE Transactions on Instrumentation and Measurement"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

# abstract: >-
#   Although Transformer-based methods have achieved significant success in obstructive sleep apnea (OSA) detection, they suffer from higher computational costs, lower feature-capturing ability in the frequency domain, and class imbalance at the data level. To address these problems, this article proposes a data rebalancing loss (DRLoss)-constrained light transformer for OSA detection, called DRLFormer. The core of the proposed method lies in the following two aspects: the development of the additive temporal–frequency fusion attention (ATFA) module, and the propose of data rebalancing loss (DRLoss) function. The purpose of the ATFA module is to fuse the frequency-domain features extracted by the frequency-domain enhancement module (FEM) with the important time-domain features extracted by the learnable time-domain attention (LTA) in a very low computational cost by novel using the summation strategy. The purpose of DRLoss is to solve the problem of imbalanced samples within batches which usually ignored by existing common used cross-entropy loss (CELoss). The novelty of the design of DRLoss lies in by designing weight memory units (WMUs) and allocating different weights for correctly and incorrectly predicted samples to achieve prediction level balance through classification penalty item (CPI). Extensive experiments are conducted on the Apnea-ECG dataset and compared with the state-of-the-art (SOTA) method. Our method achieves an improvement of 0.44% in accuracy (from 91.68% improved to 92.12%), with a reduction of size by 74% and FLOPs by 53%. Furthermore, excellent performance was achieved on the University College Dublin Sleep Apnea Database (UCD), PhysioNet, and clinical XJ300 datasets, thoroughly verifying the effectiveness and clinical application potential of DRLFormer.
cover:          assets\images\covers\DRLFormer.jpg
authors:
  - Chengjian Li 
  - Zhenghao Shi
  - ZhenZhen You
  - Na Li
  - Liang Zhou
  - Zhijun Zhang
  - Lulu Ye
  - Yitong Zhang
  - Xiaoyong Ren
  - Xinhong Hei
  - Haiqin Liu

links:
    Paper: https://ieeexplore.ieee.org/document/10630857
#   Code: https://github.com/luost26/bubble-visual-hash
#   Demo: https://luost26.github.io/bubble-visual-hash
---
