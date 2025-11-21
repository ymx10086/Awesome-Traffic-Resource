<!--
Copyright (c) 2024 Mingxin Yang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
-->

<!-- <h3 align="center">
    <img src="https://github.com/ymx10086/MTD-Resource/blob/main/ETA.png">
</h3> -->

<h1 align="center">
    <p>LLM4Network & Malicious Traffic Detection & Encrypted Traffic Classification & Website Fingerprinting Resources</p>
    <p>LLM4Network & 恶意流量检测 & 加密流量分类 & 网站指纹识别相关研究资源汇总</p>
</h1>

<p align="center">
    <a href="https://github.com/ymx10086/MTD-Resource/blob/main/LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/ymx10086/MTD-Resource.svg">
    </a>
    <img src="https://img.shields.io/github/stars/ymx10086/MTD-Resource">
    <img src="https://img.shields.io/github/forks/ymx10086/MTD-Resource">
    <a href="https://github.com/ymx10086/MTD-Resource/graphs/traffic">
    <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Flinwhitehat%2FMTD-Resource&label=visitor%20%20%20&labelColor=%23697689&countColor=%232ccce4&style=flat">
    </a>
    <a href="https://github.com/ymx10086/MTD-Resource#contributors-"><img src="https://img.shields.io/badge/Contributors-1-orange.svg"></a>
</p>

**Note:**
- ⭐ **Please leave a <font color='orange'>STAR</font> if you like this project!** ⭐
- If you find any <font color='red'>incorrect</font> / <font color='red'>inappropriate</font> / <font color='red'>outdated</font> content, please kindly consider opening an issue or a PR. 
- We would greatly appreciate your contribution to this list, and you will appear in the [contributors✨](#contributors-)!

# Content
- [About](#about)
- [Dataset](#datasets)
- [Survey](#survey)
- [LLM for Network](#LLM-for-Network)
- [Malicious Traffic Detection](#Malicious-Traffic-Detection)
- [Blogs](#blogs)
- [Libraries and Frameworks](#tool-libraries-and-frameworks)
<!--
- [Ethereum](#ethereum)
-->

# About
This is a current list of resources related to the research and development of Malicious Traffic Detection. We comb the field for relevant representative work and related resources, and pay more attention to typical studies and research teams.

# Datasets
- [Kisune](https://paperswithcode.com/dataset/kitsune-network-attack-dataset) Introduced by Mirsky et al. In Kitsune: An Ensemble of Autoencoders for Online Network Intrusion Detection.
- [Yatesbury](https://github.com/microsoft/Yatesbury) Introduced by microsoft et al. This dataset serves as a benchmark for evaluting the performance and efficiency of anomaly detectors in east-west data center network traffic.

# Survey

# LLM for Network

## General Tasks
- [NetLLM: Adapting Large Language Models for Networking](https://dl.acm.org/doi/10.1145/3651890.3672268). Duo Wu. SIGCOMM 2024. [[code]](https://github.com/duowuyms/NetLLM) [[video]](https://www.bilibili.com/video/BV11sDUYmEDH/?vd_source=80d0ce9c94b3b5bd62a09a87188a643d) [[slides]](https://duowuyms.github.io/pdf/sigcomm_2024_NetLLM.pptx)

# Malicious Traffic Detection

## DDoS with Pre-training/LLMs (Generalization, Side-channel Analysis)

- [TrafficFormer: An Efficient Pre-trained Model for Traffic Data](http://www.thucsnet.com/wp-content/papers/guangmeng_sp2025.pdf). Guangmeng Zhou. S&P 2025. [[code]](https://github.com/IDP-code/TrafficFormer)
- [DoLLM: How Large Language Models Understanding Network Flow Data to Detect Carpet Bombing DDoS](https://arxiv.org/pdf/2405.07638). Qingyang Li.
- [DrLLM: Prompt-Enhanced Distributed Denial-of-Service Resistance Method with Large Language Models](https://arxiv.org/pdf/2409.10561). Zhenyu Yin. [[code]](https://github.com/liuup/DrLLM)
- [ShieldGPT: An LLM-based Framework for DDoS Mitigation](https://dl.acm.org/doi/epdf/10.1145/3663408.3663424). Tongze Wang. APNet 2024. [[code]](https://github.com/wangtz19/ShieldGPT)

## Malicious Traffic Detection with Pre-training/LLMS

- [Training with Only 1.0 ‰ Samples: Malicious Traffic Detection via Cross-Modality Feature Fusion](). Chuanpu Fu. CCS 2025. [[code]](https://github.com/fuchuanpu/TFusion)
- [Flow-MAE: Leveraging Masked AutoEncoder for Accurate, Efficient and Robust Malicious Traffic Classification](https://dl.acm.org/doi/pdf/10.1145/3607199.3607206). Zijun Hang. RAID 2023. [[code]](https://github.com/NLear/Flow-MAE)
- [A Method for Network Intrusion Detection Using  Flow Sequence and BERT Framework](https://ieeexplore.ieee.org/document/10279335/). Loc Gia Nguyen. ICC 2023. 

## Malicious Traffic with ML-Based Manners

- [Feature Selection for Network Intrusion Detection](https://dl.acm.org/doi/10.1145/3690624.3709339). Charles Westphal. KDD 2025. [[code]](https://github.com/c-s-westphal/FSNID)
- [Realtime Robust Malicious Traffic Detection via Frequency Domain Analysis](https://arxiv.org/pdf/2106.14707). Chuanpu Fu. CCS 2021. [[code]](https://github.com/fuchuanpu/Whisper) [[video]](https://dl.acm.org/doi/10.1145/3460120.3484585)
- [Detecting Unknown Encrypted Malicious Traffic in Real Time via Flow Interaction Graph Analysis](https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s80_paper.pdf). Chuanpu Fu. NDSS 2023. [[code]](https://github.com/fuchuanpu/HyperVision) [[video]](https://www.youtube.com/watch?v=FuKrs4dt6aw) [[slide]](https://www.ndss-symposium.org/wp-content/uploads/2024/10/2023-80-slides.pdf)
- [Trident: A Universal Framework for Fine-Grained and Class-Incremental Unknown Traffic Detection](https://dl.acm.org/doi/pdf/10.1145/3589334.3645407). Ziming Zhao. WWW 2024. [[code]](https://github.com/Secbrain/Trident) [[video]](https://dl.acm.org/doi/abs/10.1145/3589334.3645407?download=true)
- [Kitsune: An Ensemble of Autoencoders for Online  Network Intrusion Detection](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_03A-3_Mirsky_paper.pdf). 
Yisroel Mirsky. NDSS 2018. [[code]](https://github.com/ymirsky/Kitsune-py)
- [Detecting Tunneled Flooding Traffic via Deep Semantic Analysis of Packet Length Patterns](https://dl.acm.org/doi/pdf/10.1145/3658644.3670353). Chuanpu Fu. CCS 2024. [[code]](https://github.com/fuchuanpu/Exosphere)
- [Wedjat: Detecting Sophisticated Evasion Attacks via Real-time Causal Analysis](https://doi.org/10.1145/3690624.3709218). Gao Li. KDD 2025. [[code]](https://github.com/cimeguy/Wedjat) [[video]](https://www.youtube.com/watch?v=Y3aEviafeaU)
- [Relative Frequency-Rank Encoding for Unsupervised Network Anomaly Detection](https://dl.acm.org/doi/pdf/10.1109/TNET.2024.3391396). Minsong Kim. ToN 2024. [[code]](https://github.com/kmuinfosec/RFRE)
- [NetVigil: Robust and Low-Cost Anomaly Detection for East-West Data Center Security](https://www.usenix.org/system/files/nsdi24-hsieh.pdf).  Kevin Hsieh. NDSI 2024. [[code]](https://github.com/microsoft/Yatesbury) [[video]](https://www.youtube.com/watch?v=gj_jpAWd-xY)

## Traffic Concept Drift

- [Continual Learning with Strategic Selection and Forgetting for Network Intrusion Detection](http://arxiv.org/abs/2412.16264). Xinchen Zhang. INFOCOM 2025. [[code]](https://github.com/xinchen930/SSF-StrategicSelection-and-Forgetting)

## OOD Malicious Traffic Detection

- [Detection of Unknown Attacks Through Encrypted Traffic A Gaussian Prototype-Aided Variational Autoencoder Framework](https://ieeexplore.ieee.org/document/11173696). Qianwei Meng. TIFS 2025. [[code]](https://github.com/niebikong/Open-Detect)

## Real-time Malicious Traffic Detection

- [Proteus: A Difficulty-aware Deep Learning  Framework for Real-time Malicious Traffic  Detection](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10858520). Chupeng Cui. ICNP 2024.
- [Realtime Robust Malicious Traffic Detection via Frequency Domain Analysis](https://arxiv.org/pdf/2106.14707). Chuanpu Fu. CCS 2021. [[code]](https://github.com/fuchuanpu/Whisper) [[video]](https://dl.acm.org/doi/10.1145/3460120.3484585)

# Encrypted Traffic Classification

## Overview

- [SoK: Decoding the Enigma of Encrypted Network Traffic Classifiers](https://ieeexplore.ieee.org/document/11023502/). Nimesha Wickramasinghe. S&P 2025. 

## Pre-training/LLMs

- [The Sweet Danger of Sugar: Debunking Representation Learning for Encrypted Traffic Classification](http://arxiv.org/abs/2507.16438). Yuqi Zhao. SIGCOMM 2025. [[code]](https://github.com/SmartData- Polito/Debunk_Traffic_Representation)
- [MM4flow: A Pre-trained Multi-modal Model for Versatile Network Traffic Analysis](). Luming Yang. CCS 2025. [[code]](https://github.com/Shangshu-LAB/MM4flow)
- [PACKETCLIP: Multi-Modal Embedding of Network Traffic  and Language for Cybersecurity Reasoning](http://arxiv.org/abs/2503.03747). Ryozo Masukawa. Arxiv 2025.5.
- [TrafficLLM: Enhancing Large Language Models for Network Traffic  Analysis with Generic Traffic Representation](https://arxiv.org/pdf/2504.04222). Tianyu Cui. Arxiv 2025.3.
- [netFound: Foundation Model for Network Security](https://arxiv.org/pdf/2310.17025). Satyandra Guthula. Arxiv 2025.1. [[code]](https://github.com/SNL-UCSB/netFound)
- [MERLOT: A Distilled LLM-based Mixture-of-Experts Framework for Scalable Encrypted Traffic Classification](http://arxiv.org/abs/2411.13004). Yuxuan Chen. Arxiv 2025.9.
- [Language of Network: A Generative Pre-trained Model for Encrypted Traffic Comprehension](http://arxiv.org/abs/2505.19482). Di Zhao. Arxiv 2025.9. [[code]]()
- [TrafficFormer: An Efficient Pre-trained Model for Traffic Data](https://ieeexplore.ieee.org/document/11023272/). Guangmeng Zhou. S&P 2025. [[code]](https://github.com/IDP-code/TrafficFormer)
- [Bottom Aggregating, Top Separating: An  Aggregator and Separator Network for  Encrypted Traffic Understanding](https://ieeexplore.ieee.org/document/10839404/). Wei Peng. TIFS 2025. [[code]](https://github.com/pengwei-iie/ASNET)
- [MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification](https://arxiv.org/pdf/2412.15306). Xu-Yang Chen. AAAI 2024. [[code]](https://github.com/SeciliaCxy/MIETT)
- [NetMamba: Efficient Network Traffic Classification via Pre-training Unidirectional Mamba](http://arxiv.org/abs/2405.11449). Tongze Wang. ICNP 2024. [[code]](https://github.com/wangtz19/NetMamba)
- [Ptu: Pre-Trained Model for Network Traffic Understanding](https://ieeexplore.ieee.org/document/10858503/). Lingfeng Peng. ICNP 2024. 
- [Yet Another Traffic Classifier: A Masked Autoencoder Based Traffic Transformer with Multi-Level Flow Representation](https://ojs.aaai.org/index.php/AAAI/article/view/25674). Ruijie Zhao. AAAI 2023. [[code]](https://github.com/NSSL-SJTU/YaTC)
- [ET-BERT: A Contextualized Datagram Representation with Pre-training Transformers for Encrypted Traffic Classification](https://dl.acm.org/doi/10.1145/3485447.3512217). Xinjie Lin. WWW 2022. [[code]](https://github.com/linwhitehat/ET-BERT)
- [PERT: Payload Encoding Representation from Transformer for Encrypted Traffic Classification](https://ieeexplore.ieee.org/document/9303204/). Hongye He. ITU 2020. 

## GNN-based Classification

- [Revolutionizing Encrypted Traffic Classification with MH-Net: A Multi-View Heterogeneous Graph Model](http://arxiv.org/abs/2501.03279). Haozhen Zhang. AAAI 2025.
- [FlowMiner: A Powerful Model Based on Flow  Correlation Mining for Encrypted Traffic  Classification](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11044724). Hongbo Xu. INFOCOM 2025. 
- [TFE-GNN: A Temporal Fusion Encoder Using Graph Neural Networks for Fine-grained Encrypted Trafic Classification](https://dl.acm.org/doi/10.1145/3543507.3583227). Haozhen Zhang. WWW 2023. [[code]](https://github.com/ViktorAxelsen/TFE-GNN)

## ML-based Classification(packet-based)

- [Packet Representation Learning for Tra ic Classification](https://dl.acm.org/doi/10.1145/3534678.3539085). Xuying Meng. KDD 2022. [[code]](https://github.com/ict-net/PacRep)

## ML-based Classification(flow-based)

- [MT-FlowFormer: A Semi-Supervised Flow Transformer for Encrypted Traffic Classification](https://dl.acm.org/doi/10.1145/3534678.3539314). Ruijie Zhao. KDD 2022. 
- [FlowLens: Enabling Efficient Flow Classification for  ML-based Network Security Applications](https://dx.doi.org/10.14722/ndss.2021.24067). Diogo Barradas. NDSS 2021. [[code]](https://github.com/dmbb/FlowLens)
- [FS-Net: A Flow Sequence Network For Encrypted  Traffic Classification](https://ieeexplore.ieee.org/document/8737507/). Chang liu. INFOCOM 2019. [[code]](https://github.com/WSPTTH/FS-Net)

## Class Imbalance & Open-set

- [Trident: A Universal Framework for Fine-Grained and Class-Incremental Unknown Traffic Detection](https://dl.acm.org/doi/10.1145/3589334.3645407). Ziming Zhao. KDD 2024. [[code]](https://github.com/Secbrain/Trident/)
- [TrafficGPT: An LLM Approach for Open-Set Encrypted Traffic Classification](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5074974). Yasod Ginige. SSRN 2024. [[code]](https://github.com/YasodGinige/TrafficGPT)
- [Incremental encrypted traffic classification via contrastive prototype networks](https://linkinghub.elsevier.com/retrieve/pii/S1389128624004237). Wei Cai. Computer Networks 2024. 
- [Listen to minority: Encrypted traffic classification for class imbalance with contrastive pre-training](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10287449). Xiang Li. SECON 2023.

## Diverse Network Environment

- [Training Robust Classifiers for Classifying Encrypted Traffic under Dynamic Network Conditions]() Yuqi Qing. CCS 2025. [[code]](https://github.com/XXnormal/MAML-Training-ETC)
- [Rosetta: Enabling Robust TLS Encrypted Traffic Classification in Diverse Network Environments with TCP-Aware Traffic Augmentation](https://dl.acm.org/doi/10.1145/3603165.3607437). Renjie Xie. USENIX Security 2023. [[code]](https://github.com/sunskyXX/Rosetta.git)

# In-Network Traffic Analysis

- [SentinelX: A Lightweight Malicious Traffic  Detection System Based on Programmable Switches](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11044759). Zutao Zhang. INFOCOM 2025. 

# Network Traffic Generation

- [NetGPT: Generative Pretrained Transformer for  Network Traffic](http://arxiv.org/abs/2304.09513). Xuying Meng. Arxiv 2025.8. [[code]](https://github.com/ict-net/NetGPT)
- [NetFlowGen: Leveraging Generative Pre-training for Network Traffic Dynamics](http://arxiv.org/abs/2412.20635). Jiawei Zhou. Arxiv 2024.12.

# Website Fingerprinting 

- [Swallow: A Transfer-Robust Website Fingerprinting Attack via Consistent Feature Learning](). Meng Shen. CCS 2025. [[code]](https://github.com/wujinhe0814/Swallow)



<!--

# Ethereum
* [A Flexible Sharding Blockchain Protocol Based on Cross-Shard Byzantine Fault Tolerance](https://ieeexplore.ieee.org/abstract/document/10100734). Yizhong Liu. TIFS 2023.
* [Secure and Scalable Cross-Domain Data Sharing in Zero-Trust Cloud-Edge-End Environment Based on Sharding Blockchain](https://ieeexplore.ieee.org/abstract/document/10246351). Yizhong Liu. TDSC 2023.
* [TGC: Transaction Graph Contrast Network for Ethereum Phishing Scam Detection](https://dl.acm.org/doi/abs/10.1145/3627106.3627109). Sijia Li. ACSAC 2023.
* [TTAGN: Temporal transaction aggregation graph network for ethereum phishing scams detection](https://dl.acm.org/doi/abs/10.1145/3485447.3512226). Sijia Li. WWW 2022.
-->

# Blogs

<!--
https://dilidonglong.com/2019/04/26/tshark%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95/
-->

# Tool Libraries and Frameworks

# What's New
**Version 1.0**

# Contributors 🌟

Thanks goes to these wonderful people!

<table>
  <!-- <tr>
    <td align="center"><a href="https://linwhitehat.github.io/"><img src="https://avatars3.githubusercontent.com/u/20349381?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Xinjie Lin</b></sub></a><br /><a href="#ideas-XinjieLin" title="Ideas, Planning, & Feedback">🎯</a> <a href="https://github.com/ymx10086/MTD-Resource/commits?author=linwhitehat" title="Documentation">📝</a> <a href="#maintenance-XinjieLin" title="Maintenance">📔</a></td>
    <td align="center"><a href="https://github.com/CuiTianyu961030"><img src="https://avatars.githubusercontent.com/u/43595189?v=4" width="100px;" alt=""/><br /><sub><b>Tianyu Cui</b></sub></a><br /><a href="#ideas-TianyuCui" title="Ideas, Planning, & Feedback">🎯</a> </td>
    <td align="center"><a href="https://github.com/jmhIcoding"><img src="https://avatars.githubusercontent.com/u/19209689?v=4" width="100px;" alt=""/><br /><sub><b>Minghao Jiang</b></sub></a><br /><a href="#ideas-MinghaoJiang" title="Ideas, Planning, & Feedback">🎯</a> </td>
    <td align="center"><a href="https://github.com/GuanZH95"><img src="https://avatars.githubusercontent.com/u/30852909?v=4" width="100px;" alt=""/><br /><sub><b>Zhong Guan</b></sub></a><br /><a href="#ideas-ZhongGuan" title="Ideas, Planning, & Feedback">🎯</a> <a href="https://github.com/ymx10086/MTD-Resource/commits?author=GuanZH95" title="Documentation">📝</a></td>
    <td align="center"><a href="https://github.com/wayneowen7"><img src="https://avatars.githubusercontent.com/u/29433723?v=4" width="100px;" alt=""/><br /><sub><b>Wei Cai</b></sub></a><br /><a href="#ideas-WeiCai" title="Ideas, Planning, & Feedback">🎯</a> </td>
    <td align="center"><a href="https://github.com/XiyuanZhang971118"><img src="https://avatars.githubusercontent.com/u/155507014?v=4" width="100px;" alt=""/><br /><sub><b>Xiyuan Zhang</b></sub></a><br /><a href="#ideas-XiyuanZhang" title="Ideas, Planning, & Feedback">🎯</a> <a href="https://github.com/ymx10086/MTD-Resource/commits?author=XiyuanZhang971118" title="Documentation">📝</a></td>
  </tr> -->
</table>
