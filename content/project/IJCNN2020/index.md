---
date: "2020-07-01T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- icon: 
  icon_pack: 
  name: PDF
  url: https://ieeexplore.ieee.org/abstract/document/9207530/
# - icon: github
#   icon_pack: fab
#   name: Code
#   url: https://github.com/H-Liu1997/Pytorch_Pose_Estimation_Framework/
- icon: youtube
  icon_pack: fab
  name: Oral
  url: https://drive.google.com/file/d/16J3O0Ja7IxP1p9NkidgkmwcCUVoBRqSG/view/

slides:
summary: "Haiyang Liu and Cheng Zhang. 2020 International Joint Conference on Neural Networks (IJCNN)"
tags:
- research
- include
title: "Reinforcement Learning based Neural Architecture Search for Audio Tagging"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

## Summary
Audio tagging aims to assign tags for an audio chunk, and it has attracted increasing attention as its potential applications seem to be evident. Deep learning technologies have been successfully applied to domestic audio tagging task. However, the performance of deep models is heavily relied on the hyper-parameters selection such as the filter size in the convolutional layers. Recently, Neural Architecture Search (NAS) has been successfully applied to design deep model architectures for specified learning task. In this paper, we explore the neural architecture search method for domestic audio tagging. We propose to use the Convolutional Recurrent Neural Network (CRNN) with Attention and Location (ATT-LOC) as the audio tagging model. Then, we apply NAS to search for the optimal number of filters and the filter size. Finally, we employ a grid search over the mixup augmentation coefficient, the input size of the spectrogram and the value of batch size to further improve the classification results. As demonstrated in our experiments, the architecture found by automatic searching achieves an equal error rate of 0.095 on DCASE 2016 task 4 dataset, outperforming the CRNN baseline of 0.10. In addition, the architecture found by NAS achieves a faster convergence rate in training than the CRNN baseline.
