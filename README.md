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
    <p>LLM4Network & Malicious Traffic Detection Analysis Resources</p>
    <p>LLM4Network & 恶意流量检测相关研究资源汇总</p>
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

## Malicious Traffic with ML-Based Manners

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
