---
title:          "TFFormer: A time–frequency information fusion-based CNN-transformer model 
                 for OSA detection with single-lead ECG"
date:           2023-09-6 00:01:00 +0800
selected:       true
pub:            "IEEE Transactions on Instrumentation and Measurement"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"

abstract: >-
  Accurate detection of obstructive sleep apnea (OSA) with a single-lead electrocardiogram (ECG) signal is highly desirable for the timely treating of OSA patients. However, due to the variance of apneas in appearance and size in ECG signals, it is still a very challenging task to obtain an accurate OSA apnea detection. To address this problem, this article presents a time–frequency information fusion-based CNN-Transformer model (TFFormer) for OSA detection with single-lead ECG, in which a module consisting of a deep residual shrinkage module, a multiscale convolutional attention (MSCA) module, and a multilayer convolution module is developed for time–frequency feature extraction. The purpose of this operation is to extract rich features from a short length of ECG signal sequences with a low computation cost. For time–frequency information fusion, to reduce its computation cost, a gated self-attention-based adaptive pruning time–frequency information fusion attention module is developed to prune the redundant tokens. With the attention-based adaptive pruning time–frequency information fusion module, the TFFormer is constructed for data-parallel processing and long-distance modeling. Compared with the best model in the comparative method, the accuracy of the proposed method was improved by 0.18% in the segmented case, and the mean absolute error was reduced by 0.25 per-recorded case, which demonstrates that the TFFormer model has better OSA detection performance and could provide a convenient and accurate solution for clinical OSA detection.
cover:          assets\images\covers\TFFormer.jpg
authors:
  - Chengjian Li 
  - Zhenghao Shi
  - Liang Zhou
  - Zhijun Zhang
  - Chenwei Wu
  - Xiaoyong Ren
  - Xinhong Hei
  - Minghua Zhao
  - Yitong Zhang
  - Haiqin Liu
  - ZhenZhen You
  - Lifeng He

links:
    Paper: https://ieeexplore.ieee.org/abstract/document/10242151
#   Code: https://github.com/luost26/bubble-visual-hash
#   Demo: https://luost26.github.io/bubble-visual-hash
---
