---
layout: default
title: 論文メモ
---

# Image Classification
1. ResNet [Deep Residual Learning for Image Recognition] [&#x1f4c4;](https://arxiv.org/abs/1512.03385)
2. SENet [Squeeze-and-Excitation Networks] [&#x1f4c4;](https://arxiv.org/abs/1709.01507)
3. ResNext  [Aggregated Residual Transformations for Deep Neural Networks] [&#x1f4c4;](https://arxiv.org/abs/1611.05431)
4. MobileNetv1 [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications] [&#x1f4c4;](https://arxiv.org/abs/1704.04861)
5. MobileNetv2 [MobileNetV2: Inverted Residuals and Linear Bottlenecks] [&#x1f4c4;](https://arxiv.org/abs/1801.04381)
6. MnasNet [MnasNet: Platform-Aware Neural Architecture Search for Mobile] [&#x1f4c4;](https://arxiv.org/abs/1807.11626)
7. EfficientNet [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks] [&#x1f4c4;](https://arxiv.org/abs/1905.11946)

# Semantic Segmentation
1. U-Net [U-Net: Convolutional Networks for Biomedical Image Segmentation] [&#x1f4c4;](https://arxiv.org/abs/1505.04597)
2. SPP-Net [Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition] [&#x1f4c4;](https://arxiv.org/abs/1406.4729)
3. PSPNet [Pyramid Scene Parsing Network] [&#x1f4c4;](https://arxiv.org/abs/1612.01105)
4. Segmentation Using DL : Survey [Image Segmentation Using Deep Learning: A Survey] [&#x1f4c4;](https://arxiv.org/abs/2001.05566)
5. CRF as RNN [Conditional Random Fields as Recurrent Neural Networks] [&#x1f4c4;](https://arxiv.org/abs/1502.03240)
6. [DeepLabv3+](./papers/semseg/deeplabv3plus.md) [Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation] [&#x1f4c4;](https://arxiv.org/abs/1802.02611)
    * CRFなどのポストプロセスなしでPASCAL VOC2012で89.0%、CItyscapesで82.1%を達成
    * DeepLabv3+はシンプルながら効率的なデコーダーをDeepLabv3に追加し、オブジェクトの輪郭部の結果を改善した
    * Xceptionを改良し、depth-wiseかつseparableな畳み込みをAtrous Spatial Pyramid Poolingとデコーダーに適用し、より高速でロバストなencoder-decoderネットワークを開発した

# Classifier with SemSeg Network
1. [Y-Net](./papers/semseg_with_classification/ynet.md) [Y-Net: Joint Segmentation and Classification for Diagnosis of Breast Biopsy Images] [link](https://homes.cs.washington.edu/~shapiro/sachin-miccai18.pdf) [&#x1f4c4;](https://arxiv.org/abs/1806.01313)
2. Combining Bottom-Up, Top-Down, and Smoothness Cues for Weakly Supervised Image Segmentation [&#x1f4c4;](http://web.engr.oregonstate.edu/~sinisa/research/publications/cvpr17_segmentation.pdf)
3. From Image-level to Pixel-level Labeling with Convolutional Networks* [&#x1f4c4;](https://arxiv.org/pdf/1411.6228.pdf)

# Object Detection
1. Mask R-CNN [Mask R-CNN] [&#x1f4c4;](https://arxiv.org/abs/1703.06870)
2. R-CNN [Rich feature hierarchies for accurate object detection and semantic segmentation] [&#x1f4c4;](https://arxiv.org/abs/1311.2524)
3. Fast R-CNN [Fast R-CNN] [&#x1f4c4;](https://arxiv.org/abs/1504.08083)
4. FPN for Object Detection [Feature Pyramid Networks for Object Detection] [&#x1f4c4;](https://arxiv.org/abs/1612.03144)
5. Faster R-CNN [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks] [&#x1f4c4;](https://arxiv.org/abs/1506.01497)
7. Focal Loss / Retina Net [Focal Loss for Dense Object Detection] [&#x1f4c4;](https://arxiv.org/abs/1708.02002)
8. Trident Net [Scale-Aware Trident Networks for Object Detection] [&#x1f4c4;](https://arxiv.org/abs/1901.01892v2)

# GANs
1. Conditional GAN [Conditional Generative Adversarial Nets] [&#x1f4c4;](https://arxiv.org/abs/1411.1784)
2. Pix2Pix[Image-to-Image Translation with Conditional Adversarial Networks] [&#x1f4c4;](https://arxiv.org/abs/1611.07004)
3. UNIT [1703.00848 Unsupervised Image-to-Image Translation Networks] [&#x1f4c4;](https://arxiv.org/abs/1703.00848)
4. CycleGAN [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks] [&#x1f4c4;](https://arxiv.org/abs/1703.10593)

# Image Captioning

# Pointcloud

# Localization

# Dataset
1. CMP [CMP Facade Database](http://cmp.felk.cvut.cz/~tylecr1/facade/)
- [ ] Thin structure reconstruction [Vid2Curve: Simultaneous Camera Motion Estimation and Thin Structure Reconstruction from an RGB Video](https://arxiv.org/abs/2005.03372)
- [ ] Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling https://arxiv.org/abs/1908.00222