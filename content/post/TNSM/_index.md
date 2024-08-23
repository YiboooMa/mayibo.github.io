---
title: 🎉 Our paper _Mitigating Energy Consumption in Heterogeneous Mobile Networks through Data-Driven Optimization_ was accepted by IEEE Transactions on Network and Service Management (**TNSM**).
summary: We propose the pRoactivE Data-drivEn Energy Saving Method (REDEEM) to mitigate energy consumption in heterogeneous 4G and 5G mobile networks. [Code](https://github.com/tsinghua-fib-lab/REDEEM) [Paper](https://ieeexplore.ieee.org/abstract/document/10565848)
date: 2024-06-18

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Framework overview of REDEEM.'

authors:
  - admin
  - TNSM

tags:
  - Mobile Network
  - Data-Driven Energy Saving Method
  - 5G
---

{{< toc mobile_only=true is_open=true >}}

## Author

Yibo Ma (Me), Tong Li, Yan Zhou, Li Yu, Depeng Jin

## Abstract

5G networks, with their notable energy consumption, pose a significant challenge. Traditional energy-saving methods, effective for 4G, struggle in heterogeneous 4G and 5G networks. In this paper, we propose the pRoactivE Data-drivEn Energy Saving Method (REDEEM) to mitigate energy consumption in heterogeneous 4G and 5G mobile networks. REDEEM spatially divides the network into meshes based on cell overlaps, predicts cell traffic for proactive control, and selects active cells within each mesh. Our framework includes energy efficiency profiling for each mesh and offloads 5G traffic onto overlapping 4G cells to reduce 5G energy usage. Experiments based on the Nanchang mobile networks validate REDEEM's effectiveness, yielding energy savings of 3442.72 MWh over a week. Notably, our approach achieves a 53.10% energy-saving rate, surpassing threshold-based methods by 38.85%, optimization-based methods by 18.15%, and fluid capacity engine by 14.79%. It minimally impacts service quality, with less than four parts per million traffic missed. Experimental results also demonstrate REDEEM's robustness across various temporal, spatial, and traffic load scenarios.

## Code

We have made our code publicly available on [GitHub](https://github.com/tsinghua-fib-lab/REDEEM).

## Acknowledgements

This research has been supported in part by the National Key Research and Development Program of China under Grant 2022ZD0116402;  in part by the National Natural Science Foundation of China under Grant U22B2057, and in part by the Institute for Guo Qiang, Tsinghua University under Grant 2023GQS0002.
