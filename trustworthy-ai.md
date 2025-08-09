# Paper Lists for Trustworhy AI

## Table of Contents
 - [Survey](#survey)
 - [AI Safety](#ai-safety)
    - [Alignment](#alignment)
 - [AI Security](#ai-security)
    - [Jailbreak Attacks](#jailbreak-attacks)
    - [Misinformation Attacks](#misinformation-attacks)
    - [Prompt Injection Attacks](#prompt-injection-attacks)


## Survey

- [x] [2025 arXiv] **AI Safety vs. AI Security: Demystifying the Distinction and Boundaries.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2506.18932) [![](https://img.shields.io/badge/slides-E29135)](https://zhiqlin.github.io/file/talks/AI_Safety_Security_July_17_2025.pdf) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/7k6RR4BMl7gcROFfzWhJjg)


- [ ] [2025 arXiv] **A Comprehensive Survey in LLM(-Agent) Full Stack Safety: Data, Training and Deployment.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2504.15585) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/ym-Bv1tPs57Y3zI-Pu6lzA)


- [ ] [2025 arXiv] **A Survey on AgentOps: Catagorization, Challenges, and Future Directions.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://www.arxiv.org/abs/2508.02121) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/UWR5BFKhJj0zrvjhjSymgQ)


- [ ] [2025 arXiv] **Safety at Scale: A Comprehensive Survey of Large Model and Agent Safety.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2502.05206) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/CKVe-45__NFey16gex55zQ) [![](https://img.shields.io/badge/homepage-808080)](https://github.com/xingjunm/Awesome-Large-Model-Safety?tab=readme-ov-file) 


## AI Safety
### Alignment

- [ ] [2025 arXiv] **STAIR: Improving Safety Alignment with Introspective Reasoning.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2502.02384) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/1v4A6JBDSTrcw1nGnRR4ow) [![](https://img.shields.io/badge/code-B5739D)](https://github.com/thu-ml/STAIR)



- [ ] [2025 arXiv] **RealSafe-R1: Safety-Aligned DeepSeek-R1 without Compromising Reasoning Capability.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2504.10081) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/1v4A6JBDSTrcw1nGnRR4ow) [![](https://img.shields.io/badge/code-B5739D)](https://huggingface.co/RealSafe)



## AI Security


### Jailbreak Attacks

- [ ] [2024 NeurIPS] **Bag of Tricks: Benchmarking of Jailbreak Attacks on LLMs.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://proceedings.neurips.cc/paper_files/paper/2024/file/38c1dfb4f7625907b15e9515365e7803-Paper-Datasets_and_Benchmarks_Track.pdf) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/KulCxJm1wgz2fqorfuJ3Iw) [![](https://img.shields.io/badge/code-B5739D)](https://github.com/usail-hkust/JailTrickBench.git)


- [ ] [2025 ACL] **Jailbreak Large Vision-Language Models Through Multi-Modal Linkage.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://aclanthology.org/2025.acl-long.74.pdf)


- [ ] [2024 arXiv] **Heuristic-Induced Multimodal Risk Distribution Jailbreak Attack for Multimodal Large Language Models.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2412.05934) [![](https://img.shields.io/badge/article-719AAC)](https://mp.weixin.qq.com/s/XqsQE_tdA4gmlsDjp4pHtA)


- [ ] [2025 arXiv] **Implicit Jailbreak Attacks via Cross-Modal Information Concealment on Vision-Language Models.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2505.16446v1)

### Misinformation Attacks

- [ ] [2024 NPJ Digital Medicine] **Medical large language models are susceptible to targeted misinformation attacks.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://www.nature.com/articles/s41746-024-01282-7)



### Prompt Injection Attacks

<!-- > Malicious users inject specially crafted prompts or instructions into model inputs, manipulating the system to produce unintended, harmful, or unauthorized outputs by bypassing safety mechanisms. -->

- [ ] [2024 arXiv] **Prompt Injection attack against LLM-integrated Applications.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2306.05499) [![](https://img.shields.io/badge/code-B5739D)](https://github.com/LLMSecurity/HouYi)

### Extraction Attacks

- [ ] [2021 Security] **Extracting Training Data from Large Language Models.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://www.usenix.org/system/files/sec21-carlini-extracting.pdf)


### Model Stealing Attacks

<!-- > Attackers extract sensitive information from black-box models through API access, without requiring direct access to the model's internals. -->

### Membership Inference Attacks



### Backdoor Attacks

<!-- > Attackers covertly embed malicious triggers during the model training process, enabling them to manipulate model behavior when specific predefined conditions are activated during inference. -->



### Defense

#### Data Cleaning

<!-- > Decontamination, deduplication, filtering. -->

#### Watermark

<!-- > Digital watermarking techniques that embed imperceptible identifiers into AI models or their outputs, enabling copyright protection and model provenance verification. -->


---

### Privacy-preserving Computation
<!-- 真正实现“数据可用不可见”的安全愿景。-->
<!-- 在保证数据提供方不泄露原始数据的前提下，对数据进行分析计算的一系列信息技术，保障数据在流通与融合过程中的“可用不可见”。 -->
<!-- 将隐私计算相关技术概括为三个大类，分别为以安全多方计算为代表的密码学路径、以可信任执行环境为代表的硬件路径和以联邦学习为代表的人工智能路径 -->

#### Survey

- [ ] [2025 IEEE Access] **Privacy-Preserving Deep Learning: A Survey on Theoretical Foundations, Software Frameworks, and Hardware Accelerators.**

- [ ] [2025 arXiv] **Towards Efficient Privacy-Preserving Machine Learning: A Systematic Review from Protocol, Model, and System Perspectives.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/pdf/2507.14519) [![](https://img.shields.io/badge/article-719AAC)](https://www.showapi.com/news/article/6892f9824ddd79d1350039fd)

#### Secure Multi-Party Computation (SMPC)

<!-- 多方安全计算指参与者在不泄露各自隐私数据情况下，利用隐私数据参与保密计算，共同完成某项计算任务。 -->

#### Homomorphic Encryption

- [ ] [2025 DAC] **ABC-FHE: A Resource-Efficient Accelerator Enabling Bootstrappable Parameters for Client-Side Fully Homomorphic Encryption.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2506.08461)

#### Differential Privacy (DP)
<!-- > Add calibrated noise to data or model outputs, preventing attackers from inferring whether specific individuals were included in the training dataset. -->

#### Federated Learning (FL)
<!-- > A distributed machine learning approach where raw data remains on local devices, and only model updates are aggregated centrally, preserving data privacy without compromising model performance. -->
<!-- 联邦学习是一种分布式机器学习技术，通过在多个拥有本地数据的数据源之间进行分布式模型训练；在不需要交换本地个体或样本数据的前提下，仅通过交换模型参数或中间结果的方式构建基于虚拟融合数据下的全局模型，从而实现数据隐私保护和数据共享计算的平衡，即“数据可用不可见”、“数据不动模型动”的应用新范式。 -->

#### Trusted Execution Environments (TEE) 
<!-- 可信执行环境是一种能确保代码和数据在执行过程中安全、完整且不被篡改的环境。 -->

#### Zero-Knowledge Proofs (ZKP)
<!-- > Cryptographic protocols that allow one party to prove knowledge of a secret without revealing the secret itself, enabling privacy-preserving verification and authentication. -->

- [ ] [2025 DAC] **zkVC: Fast Zero-Knowledge Proof for Private and Verifiable Computing.** [![](https://img.shields.io/badge/paper-7EA6E0)](https://arxiv.org/abs/2504.12217) [![](https://img.shields.io/badge/code-B5739D)](https://github.com/UCF-Lou-Lab-PET/zkformer)

<!--
- [ ] [xxx] **xxx.** 
[![](https://img.shields.io/badge/paper-7EA6E0)]()
[![](https://img.shields.io/badge/slides-E29135)]()
[![](https://img.shields.io/badge/article-719AAC)]()
[![](https://img.shields.io/badge/code-B5739D)]()
-->

