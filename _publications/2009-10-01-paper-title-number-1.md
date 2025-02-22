---
title: "Benchmarking Encoder-Decoder Architectures for Biplanar X-ray to 3D Shape Reconstruction"
collection: publications
permalink: /publication/Benchmarking-Encoder-Decoder
excerpt: 'We provide benchmarking toolkit, including architecture implementations, clinical metric evaluation, benchmarking tasks, data preprocessing utils for Biplanar X-ray to 3D Shape Reconstruction.'
date: 2023/9/24
venue: 'NeurIPS 2023 Datasets and Benchmark Track'
paperurl: 'https://arxiv.org/pdf/2309.13587'
citation: 'Shakya, Mahesh, and Bishesh Khanal. "Benchmarking Encoder-Decoder Architectures for Biplanar X-ray to 3D Bone Shape Reconstruction." (2023)'
---
Various deep learning models have been proposed for 3D bone shape reconstruction from two orthogonal (biplanar) X-ray images. However, it is unclear how these models compare against each other since they are evaluated on different anatomy, cohort and (often privately held) datasets. Moreover, the impact of the commonly optimized image-based segmentation metrics such as dice score on the estimation of clinical parameters relevant in 2D-3D bone shape reconstruction is not well known. To move closer toward clinical translation, we propose a benchmarking framework that evaluates tasks relevant to real-world clinical scenarios, including reconstruction of fractured bones, bones with implants, robustness to population shift, and error in estimating clinical parameters. Our open-source platform provides reference implementations of 8 models (many of whose implementations were not publicly available), APIs to easily collect and preprocess 6 public datasets, and the implementation of automatic clinical parameter and landmark extraction methods. We present an extensive evaluation of 8 2D-3D models on equal footing using 6 public datasets comprising images for four different anatomies. Our results show that attention-based methods that capture global spatial relationships tend to perform better across all anatomies and datasets; performance on clinically relevant subgroups may be overestimated without disaggregated reporting; ribs are substantially more difficult to reconstruct compared to femur, hip and spine; and the dice score improvement does not always bring a corresponding improvement in the automatic estimation of clinically …

[Download paper here](https://arxiv.org/pdf/2309.13587)

Recommended citation: Shakya, Mahesh, and Bishesh Khanal. "Benchmarking Encoder-Decoder Architectures for Biplanar X-ray to 3D Bone Shape Reconstruction." (2023).