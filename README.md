# MMFNet: Multi-Modal Foundation Model for Generalizable Flood Mapping

This repository contains the official implementation of **MMFNet**, a novel Multi-Modal Foundation Model designed for generalizable flood mapping using Sentinel-1 (Synthetic Aperture Radar - SAR) and Sentinel-2 (Multi-Spectral Imagery - MSI) remote sensing data.

**Note:** This work is currently under review and the code is not publicly available at this time. We appreciate your understanding.

![](/assets/full-processing-v5.png)

## Overview

MMFNet addresses the critical need for robust and adaptable flood mapping solutions by leveraging the complementary information from both SAR and MSI data. Our model is built upon a multi-phase framework:

* **Phase I: Pre-training** on a large, unlabeled multi-modal dataset (SSL4EO-S12) using a self-supervised learning approach to learn rich, generalized representations from both SAR and MSI data.
* **Phase II: Fine-tuning** on a labeled flood dataset (Sen1Floods11) to adapt the pre-trained model for the specific task of flood mapping. MMFNet is capable of handling mono-modal (SAR or MSI) and multi-modal (SAR + MSI) inputs during this phase.
* **Phase III: Application** to real-world scenarios, demonstrating MMFNet's strong generalization capabilities across diverse flood events.

## Key Features

* **Multi-Modal Handling:** MMFNet is designed to seamlessly process and fuse information from both Sentinel-1 SAR and Sentinel-2 MSI data, allowing for more comprehensive flood detection.
* **Global-Scale Pre-training:** The foundation model is pre-trained on a vast, unlabeled dataset, enhancing its generalization ability and label efficiency for downstream tasks.
* **Generalizable Flood Mapping:** Our experiments demonstrate robust performance in various and practical flood scenarios, highlighting MMFNet's ability to generalize to unseen flood events and geographical regions.
* **Foundation Model Approach:** By learning generalizable representations through pre-training, MMFNet reduces the need for extensive labeled data for specific flood mapping tasks.

## Citing MMFNet

If you find this work relevant to your research, please consider citing our paper (once published). The current draft is under review.

## Contact

For any inquiries regarding this work, please contact:

* zhouhuan@whu.edu.cn

We will update this repository with the code and pre-trained models upon acceptance and publication of our paper. Thank you for your patience and interest!
