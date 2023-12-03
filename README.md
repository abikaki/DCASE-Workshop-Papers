# DCASE-2023-Papers

![img.png](DCASE-logo.png)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Conference](http://img.shields.io/badge/DCASE-2023-395C5.svg)](https://dcase.community/)
![Version](https://img.shields.io/badge/version-v1.0.0-rc0)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://mit-license.org/)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/abikaki/DCASE-2023-Papers/blob/main/README.md)

[Proceedings](https://trepo.tuni.fi/bitstream/handle/10024/152310/978-952-03-3171-9.pdf?sequence=2&isAllowed=y) of the 8<sup>th</sup> Workshop on Detection and Classification of Acoustic Scenes and Events (DCASE 2023), September 2023

<!--
<script>
  document.getElementById('toggle').addEventListener('click', function() {
    var content = document.getElementById('content');
    content.style.display = (content.style.display === 'none' || content.style.display === '') ? 'block' : 'none';
  });
</script>
-->


## Contribute
Contributions are welcome!

## Papers

| **ID** | **Title** | **Repo** | **PDF** | **Abstract**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ------ | ----------| -------- |---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| 1 | Sound Event Classification with Object-Based Labels | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Afolaranmi_71.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;"> Availability of audio-visual datasets and increase of computational resources have made possible the use of deep learning techniques that exploit the relationship between audio and video. In this paper, we present an approach that makes use of pretrained models for object detection to label audio clips based on objects that are expected to make sound. The study consists of performing object detection for four target classes belonging to vehicle category and training sound classifiers in supervised way using the resulting labels. We conclude that object detection is a useful alternative for labeling audio-visual material for audio classification, with substantial improvements in different datasets. Results show that even for data provided with reference audio labels, labeling through video object detection can identify additional, non-annotated acoustic events, thus improving the quality of the labels in existing datasets. This promotes exploitation of video content not only as an alternative, but also to complement the available label information.</div></details> |
| 2 | Learning in the Wild: Bioacoustics Few Shot Learning Without Using a Training Set | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Aguado_58.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;"> Few-shot learning is a machine learning approach in which a pre-trained model is re-trained for new categories with just a few examples. This strategy results very convenient for problems with a dynamic number of categories as typically happens in acoustic data. The purpose of this paper is to explore the possibility of skipping this pre-training process and using as training data only the five first shots of an audio file together with the silence between them. For the experimental evaluation, data belonging to the Validation set of Task 5 DCASE Challenge 2023 is used, purposely neglecting the Training set. This challenge consists of detecting animal species using only five positive examples. In this exploratory work, three learning methods have been compared: a ResNet architecture with a prototypical loss, a ProtoNet and an XGBoost classifier. In all cases, spectrograms with different transformations are used as inputs. Obtained results are evaluated per audio file, enabling the obtention of particular conclusions about different animal species. While the detection for some species presents encouraging results using only these first 5-shots as training data, all the tested algorithms are unable to successfully learn how to properly detect the blackbird sounds of the validation dataset.</div></details> |
| 3 | Multi-Resolution Conformer for Sound Event Detection: Analysis and Optimization | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Barahona_69.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;"> The Conformer architecture has achieved state-of-the-art results in several tasks, including automatic speech recognition and automatic speaker verification. However, its utilization in sound event detection and in particular in the DCASE Challenge Task 4 has been limited despite winning the 2020 edition. Although the Conformer architecture may not excel in accurately localizing sound events, it shows promising potential in minimizing confusion between different classes. Therefore, in this paper we propose a Conformer optimization to enhance the second Polyphonic Sound Detection Score (PSDS) scenario defined for the DCASE 2023 Task 4A. With the aim of maximizing its classification properties, we have employed recently proposed methods such as Frequency Dynamic Convolutions in addition to our multi-resolution approach, which allow us to analyse its behaviour over different time-frequency resolution points. Furthermore, our Conformer systems are compared with multi-resolution models based on Convolutional Recurrent Neural Networks (CRNNs) to evaluate the respective benefits of each architecture in relation to the two proposed scenarios for the PSDS and the different time-frequency resolution points defined. These systems were submitted as our participation in the DCASE 2023 Task 4A, in which our Conformer system obtained a PSDS2 value of 0.728, achieving one of the highest scores for this scenario among systems trained without external resources.</div></details> |
| 4 | Foley Sound Synthesis at the DCASE 2023 Challenge | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Choi_4.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;">The addition of Foley sound effects during post-production is a common technique used to enhance the perceived acoustic properties of multimedia content. Traditionally, Foley sound has been produced by human Foley artists, which involves manual recording and mixing of sound. However, recent advances in sound synthesis and generative models have generated interest in machine-assisted or automatic Foley synthesis techniques. To promote further research in this area, we have organized a challenge in DCASE 2023: Task 7 - Foley Sound Synthesis. Our challenge aims to provide a standardized evaluation framework that is both rigorous and efficient, allowing for the evaluation of different Foley synthesis systems. We received 17 submissions, and performed both objective and subjective evaluation to rank them according to three criteria: audio quality, fit-to-category, and diversity. Through this challenge, we hope to encourage active participation from the research community and advance the state-of-the-art in automatic Foley synthesis. In this paper, we provide a detailed overview of the Foley sound synthesis challenge, including task definition, dataset, baseline, evaluation scheme and criteria, challenge result, and discussion.</div></details> |
| 5 | STELIN-US: A Spatio-Temporally Linked Neighborhood Urban Sound Database | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Chunarkar_49.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;">Automated acoustic understanding, e.g., sound event detection and acoustic scene recognition, is an important research direction enabling numerous modern technologies. Although there is a wealth of corpora, most, if not all, include acoustic samples of scenes/events in isolation without considering their inter-connectivity with locations nearby in a neighborhood. Within a connected neighborhood, the temporal continuity and regional limitation (sound-location dependency) at distinct locations creates non-iid acoustics samples at each site across spatial-temporal dimensions. To our best knowledge, none of the previous data sources takes on this particular angle. In this work, we present a novel dataset, Spatio-temporally Linked Neighborhood Urban Sound (STeLiN-US) database. The dataset is semi-synthesized, that is, each sample is generated by leveraging diverse sets of real urban sounds with crawled information of real-world user behaviors over time. This method helps create realistic large-scale dataset, and we further evaluate through perceptual listening test. This neighborhood-based data generation opens up novel opportunities to advance user-centered applications with automated acoustic understanding. For example, to develop real-world technology to model a user's speech data over a day, one can imagine utilizing this dataset as user's speech samples would modulate by diverse sources of acoustics surrounding linked across sites and temporally by natural behavior dynamics at each location over time.</div></details> |
| 6 | Foley Sound Synthesis Based on Generative Adversarial Networks Using Oneself-Conditioned Contrastive Learning | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Chung_65.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;">The creation of sound effects, such as foley sounds, for radio or film has traditionally relied on the expertise of skilled professionals. However, synthesizing these sounds automatically without expert intervention presents significant challenge. Particularly, when the available data is limited, this challenge becomes even more compounded. This often leads to a lack of diversity in the generated data. In this paper, we propose effective GAN frameworks, O2C-GAN and OC-SupConGAN for foley sound synthesis in this situation. The proposed frameworks use a new learning method, oneself-conditioned contrastive learning (OCC learning), to solve problems encountered in small dataset. The OCC learning is a method that aims to expand the diversity of data while preserving the inherent attributes of each class within the data. Experiments show that the proposed framework outperforms baseline schemes, ranking 2nd in DCASE2023-T7 Track B with a FAD score of 5.023 on the evaluation set.</div></details> |
| 7 | Description and Discussion on DCASE 2023 Challenge Task 2: First-Shot Unsupervised Anomalous Sound Detection for Machine Condition Monitoring | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Dohi_70.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;">We present the task description of the Detection and Classification of Acoustic Scenes and Events (DCASE) 2023 Challenge Task 2: “First-shot unsupervised anomalous sound detection (ASD) for machine condition monitoring”. The main goal is to enable rapid deployment of ASD systems for new kinds of machines without the need for hyperparameter tuning. In the past ASD tasks, developed methods tuned hyperparameters for each machine type, as the development and evaluation datasets had the same machine types. However, collecting normal and anomalous data as the development dataset can be infeasible in practice. In 2023 Task 2, we focus on solving first-shot problem, which is the challenge of training a model on a completely novel machine type. Specifically, (i) each machine type has only one section (a subset of machine type) and (ii) machine types in the development and evaluation datasets are completely different. Analysis of 86 submissions from 23 teams revealed that keys to outperform baselines were: 1) sampling techniques for dealing with class imbalances across different domains and attributes, 2) generation of synthetic samples for robust detection, and 3) use of multiple large pre-trained models to extract meaningful embeddings for the anomaly detector.</div></details> |
| 8 | Post-Processing Independent Evaluation of Sound Event Detection Systems | [![GitHub](https://img.shields.io/github/stars/fgnt/sed_scores_eval)](https://github.com/fgnt/sed_scores_eval) | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Ebbers_62.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;"> Due to the high variation in the application requirements of sound event detection (SED) systems, it is not sufficient to evaluate systems only in a single operating mode. Therefore, the community recently adopted the polyphonic sound detection score (PSDS) as an evaluation metric, which is the normalized area under the PSD receiver operating characteristic (PSD-ROC). It summarizes the system performance over a range of operating modes resulting from varying the decision threshold that is used to translate the system output scores into a binary detection output. Hence, it provides a more complete picture of the overall system behavior and is less biased by specific threshold tuning. However, besides the decision threshold there is also the post-processing that can be changed to enter another operating mode. In this paper we propose the post-processing independent PSDS (piPSDS) as a generalization of the PSDS. Here, the post-processing independent PSD-ROC includes operating points from varying post-processings with varying decision thresholds. Thus, it summarizes even more operating modes of an SED system and allows for system comparison without the need of implementing a post-processing and without a bias due to different post-processings. While piPSDS can in principle combine different types of post-processing, we here, as a first step, present median filter independent PSDS (miPSDS) results for this year’s DCASE Challenge Task4a systems. Source code is publicly available in our sed_scores_eval package.</div></details> |
| 9 | ToyADMOS2+: New Toyadmos Data and Benchmark Results of the First-Shot Anomalous Sound Event Detection Baseline | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Harada_74.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;">This paper introduces the newly recorded ToyADMOS dataset for the DCASE 2023 Challenge Task 2, First-shot anomalous sound detection for machine condition monitoring (DCASE2023T2). New machine types, such as ToyDrone, ToyNscale, Vacuum, and ToyTank, were newly recorded as a part of the Additional training and Evaluation datasets. This paper also shows benchmark results of the First-shot baseline implementation (with simple autoencoder and selective Mahalanobis modes) on the DCASE2023T2 Evaluation dataset and the previous DCASE Challenge Task 2 datasets in 2020, 2021, and 2022, compared with the baselines of those years.</div></details> |
| 10 | Evaluating Classification Systems Against Soft Labels with Fuzzy Precision and Recall | :heavy_minus_sign: | [![DCASE](https://img.shields.io/badge/pdf-DCASE-395C5.svg)](https://dcase.community/documents/workshop2023/proceedings/DCASE2023Workshop_Harju_51.pdf) | <details><summary id="toggle">Show</summary> <div id="content" style="display: none;">Classification systems are normally trained by minimizing the cross-entropy between system outputs and reference labels, which makes the Kullback-Leibler divergence a natural choice for measuring how closely the system can follow the data. Precision and recall provide another perspective for measuring the performance of a classification system. Non-binary references can arise from various sources, and it is often beneficial to use the soft labels for training instead of the binarized data. However, the existing definitions for precision and recall require binary reference labels, and binarizing the data can cause erroneous interpretations. We present a novel method to calculate precision, recall and F-score without quantizing the data. The proposed metrics extend the well established metrics as the definitions coincide when used with binary labels. To understand the behavior of the metrics we show simple example cases and an evaluation of different sound event detection models trained on real data with soft labels.</div></details> |
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