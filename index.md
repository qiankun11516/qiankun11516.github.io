---
layout: default
---

I am a research scientist in Network Research at Alibaba Cloud, and lead the design and implementation of innovations in predicatble network (可预期网络). 
My research focuses on building high-performance network solutions for computing and storaging systems.

I received my Ph.D. degree from Tsinghua University in 2020, under the guidance of Professor [Fengyuan Ren](https://nns.cs.tsinghua.edu.cn/personal/renfy/renfy.html).

# Selected Projects

## High performance AI training network

I am working for designing high performance and high stability network solutions for cloud AI training clusters (灵骏), including network architecture, traffic scheduler, collective communication library, RDMA, monitoring & diagnosis.
Our brand-new AI training network architecture (HPN) is large-scale deployed in production and introduces great improvement on both the stability and performance of LLM training.
The global network resource scheduler (Crux) maximizes GPU computation utilization by mitigating the communication contention among different training jobs, which is in the deployment procedure in production.

## High performance storage netowrk

I am working for designing high performance network solutions for cloud storage services.
With the deep cooperation of Elastic Block Storage (EBS), we complete the great transport evolution from commodity kernel-space TCP to user-space TCP (Luna), and finally to the brand-new storage-network fusion protocol (Solar).
From 2018 to 2022, with the large-scale deployment of Luna and Solar, the average I/O latency decreases 72% and the overall IOPS increase 3X.
<br>
These contributions are published in **SIGCOMM '22**.
<br>
[Introductory Video](https://www.bilibili.com/video/BV15R4y187g4/).

## Global video conferencing system

I am cooperating with Dingtalk (钉钉) to design cross-region multicast system.
This system implements an overlay network based on hybird network resources and a multicast system with various long-distance video multicast enhancements.
This cross-region multicast system is deployed on all main service region of Dingtalk and reduces video stall ratio and bad audio fluency by 77% and 65.2%.
<br>
These contributions are published in **SIGCOMM '23**.

# Selected Publications

SimAI: Unifying Architecture Design and Performance Tunning for Large-Scale Large Language Model Training with Scalability and Precision
\[Upcomming Soon]
<br>
Xizheng Wang, Qingxu Li, Yichi Xu, Gang Lu, Dan Li, Li Chen, Heyang Zhou, Linkang Zheng, Sen Zhang, Yikai Zhu, Yang Liu, Pengcheng Zhang, **Kun Qian**, Kunling He, Jiaqi Gao, Ennan Zhai, Dennis Cai, Binzhang Fu.
<br>
USENIX Symposium on Networked Systems Design and Implementation (**NSDI '25**).

SimAI: Unifying Architecture Design and Performance Tunning for Large-Scale Large Language Model Training with Scalability and Precision
\[Upcomming Soon]
<br>
Xizheng Wang, Qingxu Li, Yichi Xu, Gang Lu, Dan Li, Li Chen, Heyang Zhou, Linkang Zheng, Sen Zhang, Yikai Zhu, Yang Liu, Pengcheng Zhang, **Kun Qian**, Kunling He, Jiaqi Gao, Ennan Zhai, Dennis Cai, Binzhang Fu.
<br>
USENIX Symposium on Networked Systems Design and Implementation (**NSDI '25**).

SimAI: Unifying Architecture Design and Performance Tunning for Large-Scale Large Language Model Training with Scalability and Precision
\[Upcomming Soon]
<br>
Xizheng Wang, Qingxu Li, Yichi Xu, Gang Lu, Dan Li, Li Chen, Heyang Zhou, Linkang Zheng, Sen Zhang, Yikai Zhu, Yang Liu, Pengcheng Zhang, **Kun Qian**, Kunling He, Jiaqi Gao, Ennan Zhai, Dennis Cai, Binzhang Fu.
<br>
USENIX Symposium on Networked Systems Design and Implementation (**NSDI '25**).

Near-Lossless Gradient Compression for Data-Parallel Distributed DNN Training.
\[[pdf](./pdf/SmartNIC-icnp24.pdf)\]
<br>
Xue Li, Cheng Guo, **Kun Qian**, Menghao Zhang, Mengyu Yang, Mingwei Xu.
<br>
ACM Symposium on Cloud Computing (**SoCC '24**).

Demystifying Datapath Accelerator Enhanced Off-path SmartNIC.
\[[pdf](./pdf/SmartNIC-icnp24.pdf)\]
<br>
Xuzheng Chen, Jie Zhang, Ting Fu, Yifan Shen, Shu Ma, **Kun Qian**, Lingjun Zhu, Chao Shi, Yin Zhang, Ming Liu, Zeke Wang.
<br>
IEEE International Conference on Network Protocols (**ICNP '24**).

Alibaba HPN: A Data Center Network for Large Language Model Training.
\[[pdf](./pdf/sigcomm24-HPN.pdf)\]
<br>
**Kun Qian**, Yongqing Xi, Jiamin Cao, Jiaqi Gao, Yichi Xu, Yu Guan, Binzhang Fu, Xuemei Shi Fangbo Zhu, Rui Miao, Chao Wang, Peng Wang, Pengcheng Zhang, Xianlong Zeng Eddie Ruan, Zhiping Yao, Ennan Zhai, Dennis Cai.
<br>
In Proceedings of the ACM SIGCOMM 2024 Conference (**SIGCOMM '24**).

Crux: GPU-Efficient Communication Scheduling for Deep Learning Training.
\[[pdf](./pdf/sigcomm24-Crux.pdf)\]
<br>
Jiamin Cao, Yu Guan, **Kun Qian**, Jiaqi Gao, Wencong Xiao, Jianbo Dong, Binzhang Fu, Dennis Cai, Ennan Zhai.
<br>
In Proceedings of the ACM SIGCOMM 2024 Conference (**SIGCOMM '24**).

Burstable Cloud Block Storage with Data Processing Units.
\[[pdf](./pdf/osdi24-CBS.pdf)\]
<br>
Junyi Shu, **Kun Qian**, Ennan Zhai, Xuanzhe Liu, Xin Jin.
<br>
18th USENIX Symposium on Operating Systems Design and Implementation (**OSDI '24**).

XRON: A Hybrid Elastic Cloud Overlay Network for Video Conferencing at Planetary Scale.
[paper](https://dl.acm.org/doi/10.1145/3603269.3604845)
<br>
Bingyang Wu, **Kun Qian**, Bo Li, Yunfei Ma, Qi Zhang, Zhigang Jiang, Jiayu Zhao, Dennis Cai, and Ennan Zhai, Xuanzhe Liu and Xin Jin.
<br>
In Proceedings of the ACM SIGCOMM 2023 Conference (**SIGCOMM '23**).

Predictable vFabric on informative data plane.
[paper](https://dl.acm.org/doi/10.1145/3544216.3544241)
<br>
Shuai Wang, Kaihui Gao, **Kun Qian**, Dan Li, Rui Miao, Bo Li, Yu Zhou, Ennan Zhai, Chen Sun, Jiaqi Gao, Dai Zhang, Binzhang Fu, Frank Kelly, Dennis Cai, Hongqiang Harry Liu, and Ming Zhang.
<br>
In Proceedings of the ACM SIGCOMM 2022 Conference (**SIGCOMM '22**).

From luna to solar: the evolutions of the compute-to-storage networks in Alibaba cloud.
[paper](https://dl.acm.org/doi/abs/10.1145/3544216.3544238)
<br>
Rui Miao, Lingjun Zhu, Shu Ma, **Kun Qian**, Shujun Zhuang, Bo Li, Shuguang Cheng, Jiaqi Gao, Yan Zhuang, Pengcheng Zhang, Rong Liu, Chao Shi, Binzhang Fu, Jiaji Zhu, Jiesheng Wu, Dennis Cai, and Hongqiang Harry Liu.
<br>
In Proceedings of the ACM SIGCOMM 2022 Conference (**SIGCOMM '22**).

Re-architecting Congestion Management in Lossless Ethernet.
[paper](https://www.usenix.org/conference/nsdi20/presentation/cheng)
<br>
Wenxue Cheng, **Kun Qian**, Wanchun Jiang, Tong Zhang and Fengyuan Ren.
<br> 
17th USENIX Symposium on Networked Systems Design and Implementation (**NSDI '20**).

Gentle flow control: avoiding deadlock in lossless networks.
[paper](https://dl.acm.org/doi/abs/10.1145/3341302.3342065)
<br>
**Kun Qian**, Wenxue Cheng, Tong Zhang, and Fengyuan Ren.
<br>
In Proceedings of the ACM Special Interest Group on Data Communication (**SIGCOMM '19**).

FlexGate: High-performance Heterogeneous Gateway in Data Centers.
[paper](https://dl.acm.org/doi/abs/10.1145/3343180.3343182)
<br>
**Kun Qian**, Sai Ma, Mao Miao, Jianyuan Lu, Tong Zhang, Peilong Wang, Chenghao Sun, and Fengyuan Ren.
<br>
In Proceedings of the 3rd Asia-Pacific Workshop on Networking 2019 (**APNet '19**).

Awakening Power of Physical Layer: High Precision Time Synchronization for Industrial Ethernet.
[paper](https://ieeexplore.ieee.org/abstract/document/8277288/)
<br>
**Kun Qian**, Tong Zhang and Fengyuan Ren.
<br>
In 2017 IEEE Real-Time Systems Symposium (**RTSS '17**).

XpressEth: Concise and efficient converged real-time Ethernet.
[paper](https://ieeexplore.ieee.org/document/7969129)
<br>
**Kun Qian**, Fengyuan Ren, Danfeng Shan, Wenxue Cheng and Bo Wang.
<br>
2017 IEEE/ACM 25th International Symposium on Quality of Service (**IWQoS '17**).
