# DCASE-2023-Papers
Workshop on Detection and Classification of Acoustic Scenes and Events

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Conference](http://img.shields.io/badge/DCASE-2023-395C5.svg)](https://dcase.community/)
![Version](https://img.shields.io/badge/version-v1.0.0-rc0)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://mit-license.org/)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/abikaki/DCASE-2023-Papers/blob/main/README.md)

[Proceedings](https://trepo.tuni.fi/bitstream/handle/10024/152310/978-952-03-3171-9.pdf?sequence=2&isAllowed=y) of the 8<sup>th</sup> Workshop on Detection and Classification of Acoustic Scenes and Events (DCASE 2023), September 2023


<script>
  document.getElementById('toggle').addEventListener('click', function() {
    var content = document.getElementById('content');
    content.style.display = (content.style.display === 'none' || content.style.display === '') ? 'block' : 'none';
  });
</script>



## Contribute
Contributions are welcome!

## Papers

| **ID** | **Title** | **Repo** | **PDF** | **Abstract**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ------ | ----------| -------- |---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| 1 | Sound Event Classification with Object-Based Labels | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Afolaranmi_71.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;"> Availability of audio-visual datasets and increase of computational resources have made possible the use of deep learning techniques that exploit the relationship between audio and video. In this paper, we present an approach that makes use of pretrained models for object detection to label audio clips based on objects that are expected to make sound. The study consists of performing object detection for four target classes belonging to vehicle category and training sound classifiers in supervised way using the resulting labels. We conclude that object detection is a useful alternative for labeling audio-visual material for audio classification, with substantial improvements in different datasets. Results show that even for data provided with reference audio labels, labeling through video object detection can identify additional, non-annotated acoustic events, thus improving the quality of the labels in existing datasets. This promotes exploitation of video content not only as an alternative, but also to complement the available label information.</div></details> |
| 2 | Learning in the Wild: Bioacoustics Few Shot Learning Without Using a Training Set | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Aguado_58.pdf) | 
| 3 | Multi-Resolution Conformer for Sound Event Detection: Analysis and Optimization | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Barahona_69.pdf) |
| 4 | Foley Sound Synthesis at the DCASE 2023 Challenge | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Choi_4.pdf) |
| 5 | STELIN-US: A Spatio-Temporally Linked Neighborhood Urban Sound Database | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Chunarkar_49.pdf) |
| 6 | Foley Sound Synthesis Based on Generative Adversarial Networks Using Oneself-Conditioned Contrastive Learning | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Chung_65.pdf) |
| 7 | Description and Discussion on DCASE 2023 Challenge Task 2: First-Shot Unsupervised Anomalous Sound Detection for Machine Condition Monitoring | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Dohi_70.pdf) |
| 8 | Post-Processing Independent Evaluation of Sound Event Detection Systems | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Ebbers_62.pdf) |
| 9 | ToyADMOS2+: New Toyadmos Data and Benchmark Results of the First-Shot Anomalous Sound Event Detection Baseline | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Harada_74.pdf) |
| 10 | Evaluating Classification Systems Against Soft Labels with Fuzzy Precision and Recall | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Harju_51.pdf) |
| 11 | META-SELD: Meta-Learning for Fast Adaptation to the New Environment in Sound Event Localization and Detection | |
| 12 | Leveraging Geometrical Acoustic Simulations of Spatial Room Impulse Responses for Improved Sound Event Detection and Localization | |
| 13 | Speech Obfuscation in Mel Spectra That Allows for Centralised Annotation and Classification of Sound Events | |
| 14 | FALL-E: A Foley Sound Synthesis Model and Strategies | |
| 15 | Label Filtering-Based Self-Learning for Sound Event Detection Using Frequency Dynamic Convolution with Large Kernel Attention | |
| 16 | Improving Automated Audio Captioning Fluency Through Data Augmentation and Ensemble Selection | |
| 17 | Weakly-Supervised Automated Audio Captioning via Text Only Training | |
| 18 | Killing Two Birds with One Stone: Can an Audio Captioning System Also Be Used for Audio-Text Retrieval? | |
| 19 | Few Shot Bioacoustic Detection Boosting with Finetuning Strategy Using Negative-Based Prototypical Learning | |
| 20 | Masked Modeling Duo Vision Transformer with Multi-Layer Feature Fusion on Respiratory Sound Classification | |
| 21 | Efficient Evaluation Algorithms for Sound Event Detection | |
| 22 | Aggregate or Separate: Learning From Multi-Annotator Noisy Labels for Best Classification Performance | |
| 23 | Active Learning in Sound-Based Bearing Fault Detection | |
| 24 | Auditory Neural Response Inspired Sound Event Detection Based on Spectro-Temporal Receptive Field | |
| 25 | Creating a Good Teacher for Knowledge Distillation in Acoustic Scene Classification | |
| 26 | Pretraining Representations for Bioacoustic Few-Shot Detection Using Supervised Contrastive Learning | |
| 27 | Incremental Learning of Acoustic Scenes and Sound Events | |
| 28 | Frequency & Channel Attention for Computationally Efficient Sound Event Detection | |
| 29 | Unsupervised Domain Adaptation for the Cross-Dataset Detection of Humpback Whale Calls | |
| 30 | Few-Shot Bioacoustic Event Detection at the DCASE 2023 Challenge | |
| 31 | Advancing Natural-Language Based Audio Retrieval with Passt and Large Audio-Caption Data Sets | |
| 32 | Foley Sound Synthesis with a Class-Conditioned Latent Diffusion Model | |
| 33 | Distilling the Knowledge of Transformers and CNNs with CP-Mobile | |
| 34 | Device Generalization with Inverse Contrastive Loss and Impulse Response Augmentation | |
| 35 | Multi-Label Open-Set Audio Classification | |
| 36 | Spectral Transcoder : Using Pretrained Urban Sound Classifiers on Undersampled Spectral Representations | |
| 37 | Audio Difference Captioning Utilizing Similarity-Discrepancy Disentanglement | |
| 39 | Cross-Dimensional Interaction with Inverted Residual Triplet Attention for Low-Complexity Sound Event Detection | |
| 40 | Exploring Multi-Task Learning with Weighted Soft Label Loss for Sound Event Detection with Soft Labels | |
| 41 | Event Classification with Class-Level Gated Unit Using Large-Scale Pretrained Model for Optical Fiber Sensing | |
| 42 | Audio-Change Captioning to Explain Machine-Sound Anomalies | |
| 43 | Automatic Detection of Cow Vocalizations Using Convolutional Neural Networks | |
| 44 | Low-Complexity Acoustic Scene Classification Using Deep Mutual Learning and Knowledge Distillation Fine-Tuning | |
| 45 | Two vs. Four-Channel Sound Event Localization and Detection | | 
| 46 | PLDISET: Probabilistic Localization and Detection of Independent Sound Events with Transformers | |
| 47 | Crowdsourcing and Evaluating Text-Based Audio Retrieval Relevances | |
| 48 | Text-Driven Foley Sound Generation with Latent Diffusion Model | |