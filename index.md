---
layout: default
title: 論文メモ
---

# Image Classification
1. [x] ResNet [Deep Residual Learning for Image Recognition] [&#x1f4c4;](https://arxiv.org/abs/1512.03385)
2. [x] SENet [Squeeze-and-Excitation Networks] [&#x1f4c4;](https://arxiv.org/abs/1709.01507)
3. [x] ResNext  [Aggregated Residual Transformations for Deep Neural Networks] [&#x1f4c4;](https://arxiv.org/abs/1611.05431)
4. [x] MobileNetv1 [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications] [&#x1f4c4;](https://arxiv.org/abs/1704.04861)
5. [x] MobileNetv2 [MobileNetV2: Inverted Residuals and Linear Bottlenecks] [&#x1f4c4;](https://arxiv.org/abs/1801.04381)
6. [x] MnasNet [MnasNet: Platform-Aware Neural Architecture Search for Mobile] [&#x1f4c4;](https://arxiv.org/abs/1807.11626)
7. [x] EfficientNet [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks] [&#x1f4c4;](https://arxiv.org/abs/1905.11946)

# Semantic Segmentation
1. [x] U-Net [U-Net: Convolutional Networks for Biomedical Image Segmentation] [&#x1f4c4;](https://arxiv.org/abs/1505.04597)
2. [x] SPP-Net [Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition] [&#x1f4c4;](https://arxiv.org/abs/1406.4729)
3. [x] PSPNet [Pyramid Scene Parsing Network] [&#x1f4c4;](https://arxiv.org/abs/1612.01105)
4. [x] Segmentation Using DL : Survey [Image Segmentation Using Deep Learning: A Survey] [&#x1f4c4;](https://arxiv.org/abs/2001.05566)
5. [x] CRF as RNN [Conditional Random Fields as Recurrent Neural Networks] [&#x1f4c4;](https://arxiv.org/abs/1502.03240)
6. [x] [DeepLabv3+](./papers/semseg/deeplabv3plus.md) [Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation] [&#x1f4c4;](https://arxiv.org/abs/1802.02611)
    * CRFなどのポストプロセスなしでPASCAL VOC2012で89.0%、CItyscapesで82.1%を達成
    * DeepLabv3+はシンプルながら効率的なデコーダーをDeepLabv3に追加し、オブジェクトの輪郭部の結果を改善した
    * Xceptionを改良し、depth-wiseかつseparableな畳み込みをAtrous Spatial Pyramid Poolingとデコーダーに適用し、より高速でロバストなencoder-decoderネットワークを開発した

# Classifier with SemSeg Network
1. [x] [Y-Net](./papers/semseg_with_classification/ynet.md) [Y-Net: Joint Segmentation and Classification for Diagnosis of Breast Biopsy Images] [link](https://homes.cs.washington.edu/~shapiro/sachin-miccai18.pdf) [&#x1f4c4;](https://arxiv.org/abs/1806.01313)
2. [x] Combining Bottom-Up, Top-Down, and Smoothness Cues for Weakly Supervised Image Segmentation [&#x1f4c4;](http://web.engr.oregonstate.edu/~sinisa/research/publications/cvpr17_segmentation.pdf)
3. [x] From Image-level to Pixel-level Labeling with Convolutional Networks* [&#x1f4c4;](https://arxiv.org/pdf/1411.6228.pdf)

# Object Detection
1. [x] Mask R-CNN [Mask R-CNN] [&#x1f4c4;](https://arxiv.org/abs/1703.06870)
2. [x] R-CNN [Rich feature hierarchies for accurate object detection and semantic segmentation] [&#x1f4c4;](https://arxiv.org/abs/1311.2524)
3. [x] Fast R-CNN [Fast R-CNN] [&#x1f4c4;](https://arxiv.org/abs/1504.08083)
4. [x] FPN for Object Detection [Feature Pyramid Networks for Object Detection] [&#x1f4c4;](https://arxiv.org/abs/1612.03144)
5. [x] Faster R-CNN [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks] [&#x1f4c4;](https://arxiv.org/abs/1506.01497)
7. [x] Focal Loss / Retina Net [Focal Loss for Dense Object Detection] [&#x1f4c4;](https://arxiv.org/abs/1708.02002)
8. [x] Trident Net [Scale-Aware Trident Networks for Object Detection] [&#x1f4c4;](https://arxiv.org/abs/1901.01892v2)

# GANs
1. [x] Conditional GAN [Conditional Generative Adversarial Nets] [&#x1f4c4;](https://arxiv.org/abs/1411.1784)
2. [x] Pix2Pix [Image-to-Image Translation with Conditional Adversarial Networks] [&#x1f4c4;](https://arxiv.org/abs/1611.07004)
3. [x] UNIT [1703.00848 Unsupervised Image-to-Image Translation Networks] [&#x1f4c4;](https://arxiv.org/abs/1703.00848)
4. [x] CycleGAN [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks] [&#x1f4c4;](https://arxiv.org/abs/1703.10593)

# Image Captioning

# Pointcloud

# Localization

# Dataset
1. [x] CMP [CMP Facade Database](http://cmp.felk.cvut.cz/~tylecr1/facade/)
2. [ ] Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling https://arxiv.org/abs/1908.00222