# Awesome Edge AI Papers

A curated list of Edge AI papers. If you find some interesting work/projects, please contact me through issues or email withhaotian [at] gmail [dot] com.

*The papers or projects for on-device LLMs/SLMs are transferred to [awesome-on-device-LLM-papers](https://github.com/withhaotian/awesome-on-device-LLM-papers.git)*

# Contributing
> 🔥 This list will be keep maintaining. 

Contributions are always welcome! Please refer to [our contributing guidelines](CONTRIBUTING.md) for more information and create a PR to add papers or projects.

# License
This project is licensed under the GPL-3.0 license - see the [LICENSE](LICENSE) file for details.

# Overview
- [Awesome Edge AI Papers](#awesome-edge-ai-papers)
- [Contributing](#contributing)
- [License](#license)
- [Overview](#overview)
  - [Surveys](#surveys)
  - [Edge Training](#edge-training)
  - [Edge Inference](#edge-inference)
  - [Serverless Computing](#serverless-computing)
  - [Large Language Models (LLMs) / Small Language Models (SLMs)](#large-language-models-llms--small-language-models-slms)
  - [Graph Processing/Scheduling](#graph-processingscheduling)
  - [Optimization for Edge systems](#optimization-for-edge-systems)
  - [Edge AI Systems](#edge-ai-systems)
  - [System-Level Analytics \& Evaluation](#system-level-analytics--evaluation)
  - [Edge Security \& Privacy](#edge-security--privacy)
  - [On-Device Intelligence](#on-device-intelligence)
  - [Video Analytics](#video-analytics)
  - [Edge Cahcing](#edge-cahcing)
  - [Edge Data Storage/Analytics](#edge-data-storageanalytics)
  - [Cloud-Edge Systems](#cloud-edge-systems)
  - [Services Provision](#services-provision)
  - [Sensing \& Wireless Communications](#sensing--wireless-communications)
  - [Unmanned Aerial Vehicle (UAV)](#unmanned-aerial-vehicle-uav)
  - [Mobile Crowdsensing](#mobile-crowdsensing)
  - [Resource Allocation/Management](#resource-allocationmanagement)
  - [Over-the-air Computation](#over-the-air-computation)
  - [Coded Distributed Computing](#coded-distributed-computing)

## Surveys
- \[KDD'24\] [Inference Optimization of Foundation Models on AI Accelerators](content/2024/kdd24-inference.md) - \[[PDF](https://doi.org/10.1145/3637528.3671465)\]
- \[TPAMI'24\] [Parallel and distributed graph neural networks: An in-depth concurrency analysis](content/2024/tpami24-parallel.md) - \[[PDF](https://doi.org/10.1109/TPAMI.2023.3303431)\]
- \[COMST'24\] Unleashing the Power of Edge-Cloud Generative AI in Mobile Networks: A Survey of AIGC Services - \[[PDF](https://ieeexplore.ieee.org/document/10398474/)\]
- \[ACM CSUR'24\] Mobile Edge Computing and Machine Learning in the Internet of Unmanned Aerial Vehicles: A Survey - \[[PDF](https://dl.acm.org/doi/10.1145/3604933)\]
- \[ACM CSUR'24\] A Model and Survey of Distributed Data-Intensive Systems - \[[PDF](https://dl.acm.org/doi/10.1145/3604801)\]
- \[arXiv'24\] On-Device Language Models: A Comprehensive Review - \[[PDF](https://arxiv.org/abs/2409.00088)\] \[[Code](https://github.com/NexaAI/Awesome-LLMs-on-device)\]
- \[arXiv'24\] A Survey of Small Language Models - \[[PDF](https://arxiv.org/abs/2410.20011)\]
- \[arXiv'24\] Small Language Models: Survey, Measurements, and Insights - \[[PDF](https://arxiv.org/abs/2409.15790)\] \[[Code](https://github.com/UbiquitousLearning/SLM_Survey)\] \[[Demo](https://ubiquitouslearning.github.io/TinyLLMLeaderBoard/)\]
- \[arXiv'24\] A Survey of Resource-efficient LLM and Multimodal Foundation Models - \[[PDF](https://arxiv.org/abs/2401.08092.pdf)\] \[[Code](https://github.com/UbiquitousLearning/Efficient_Foundation_Model_Survey)\]
- \[arXiv'24\] Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security - \[[PDF](https://arxiv.org/abs/2401.05459)\] \[[Code](https://github.com/MobileLLM/Personal_LLM_Agents_Survey/)\]
- \[arXiv'24\] Edge Graph Intelligence: Reciprocally Empowering Edge Networks with Graph Intelligence - \[[PDF](http://arxiv.org/abs/2407.15320)\]
- \[arXiv'24\] A Survey on Effective Invocation Methods of Massive LLM Services - \[[PDF](http://arxiv.org/abs/2402.03408)\]
- \[arXiv'24\] On-Device Language Models: A Comprehensive Review - \[[PDF](https://arxiv.org/abs/2409.00088)\]
- \[arXiv'24\] A Survey on Model Compression for Large Language Models - \[[PDF](http://arxiv.org/abs/2308.07633)\]
- \[ACM CSUR'23\] [The evolution of distributed systems for graph neural networks and their origin in graph processing and deep learning: A survey](content/2023/csur23-disgnn.md) - \[[PDF](https://doi.org/10.1145/3597428)\]
- \[COMST'23\] [Distributed artificial intelligence empowered by end-edge-cloud computing: A survey](content/2023/comst23-dis-ai-eecc.md) - \[[PDF](https://doi.org/10.1109/COMST.2022.3218527)\]
- \[COMST'23\] Machine Learning for Large-Scale Optimization in 6G Wireless Networks - \[[PDF](https://doi.org/10.1109/COMST.2023.3300664)\]
- \[IEEE JPROC'23\] Efficient Acceleration of Deep Learning Inference on Resource-Constrained Edge Devices: A Review - \[[PDF](https://doi.org/10.1109/JPROC.2022.3226481)\]
- \[IOTJ'23\] The Security and Privacy of Mobile Edge Computing: An Artificial Intelligence Perspective - \[[PDF](https://doi.org/10.1109/JIOT.2023.3304318)\]
- \[COMST'22\] [Pervasive AI for IoT applications: A survey on resource-efficient distributed artificial intelligence](content/2022/comst22-pervasive-ai.md) - \[[PDF](https://doi.org/10.1109/COMST.2022.3200740)\]

## Edge Training
- \[INFOCOM'24\] Agglomerative Federated Learning: Empowering Larger Model Training via End-Edge-Cloud Collaboration - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621254)\]
- \[INFOCOM'24\] Edge-MSL: Split Learning on the Mobile Edge via Multi-Armed Bandits - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621231)\]
- \[INFOCOM'24\] Heroes: Lightweight Federated Learning with Neural Composition and Adaptive Local Update in Heterogeneous Edge Networks - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621351)\]
- \[INFOCOM'24\] SpreadFGL: Edge-Client Collaborative Federated Graph Learning with Adaptive Neighbor Generation - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621368)\]
- \[INFOCOM'24\] Towards Efficient Asynchronous Federated Learning in Heterogeneous Edge Environments - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621333)\]
- \[WWW'24\] [Accelerating the Decentralized Federated Learning via Manipulating Edges](content/2024/www24-sseo.md) - \[[PDF](https://doi.org/10.1145/3589334.3645509)\]
- \[WWW'24\] FedDSE: Distribution-aware Sub-model Extraction for Federated Learning over Resource-constrained Devices - \[[PDF](https://doi.org/10.1145/3589334.3645416)\]
- \[WWW'24\] How Few Davids Improve One Goliath: Federated Learning in Resource-Skewed Edge Computing Environments - \[[PDF](https://doi.org/10.1145/3589334.3645544)\]
- \[TMC'24\] Federated Learning with Dynamic Epoch Adjustment and Collaborative Training in Mobile Edge Computing - \[[PDF](https://ieeexplore.ieee.org/document/10158912/)\]
- \[arXiv'24\] [Automated Federated Pipeline for Parameter-Efficient Fine-Tuning of Large Language Models](content/2024/arxiv24-automated.md) - \[[PDF](https://arxiv.org/abs/2404.06448)\]
- \[TMC'23\] [HierFedML: aggregator placement and UE assignment for hierarchical federated learning in mobile edge computing](content/2023/tmc23-hierfedml.md) - \[[PDF](https://doi.org/10.1109/TPDS.2022.3218807)\]
- \[WWW'23\] PipeEdge: A Trusted Pipelining Collaborative Edge Training based on Blockchain - \[[PDF](https://doi.org/10.1145/3543507.3583413)\]
- \[WWW'23\] FlexiFed: Personalized Federated Learning for Edge Clients with Heterogeneous Model Architectures - \[[PDF](https://doi.org/10.1145/3543507.3583347)\]
- \[WWW'23\] FedEdge: Accelerating Edge-Assisted Federated Learning - \[[PDF](https://doi.org/10.1145/3543507.3583264)\]
- \[WWW'23\] EdgeMove: Pipelining Device-Edge Model Training for Mobile Intelligence - \[[PDF](https://dl.acm.org/doi/10.1145/3543507.3583540)\]
- \[WWW'23\] pFedPrompt: Learning Personalized Prompt for Vision-Language Models in Federated Learning - \[[PDF](https://dl.acm.org/doi/10.1145/3543507.3583518)\]
- \[TWC'23\] Ensemble Distillation Based Adaptive Quantization for Supporting Federated Learning in Wireless Networks - \[[PDF](https://doi.org/10.1109/TWC.2022.3222717)\]
- \[TWC'23\] Hierarchical Federated Learning With Quantization: Convergence Analysis and System Design - \[[PDF](https://doi.org/10.1109/TWC.2022.3190512)\]
- \[TWC'23\] Knowledge-Guided Learning for Transceiver Design in Over-the-Air Federated Learning - \[[PDF](https://doi.org/10.1109/TWC.2022.3192550)\]
- \[TWC'23\] Online Client Selection for Asynchronous Federated Learning With Fairness Consideration - \[[PDF](https://doi.org/10.1109/TWC.2022.3211998)\]
- \[TWC'23\] Olive Branch Learning: A Topology-Aware Federated Learning Framework for Space-Air-Ground Integrated Network - \[[PDF](https://doi.org/10.1109/TWC.2022.3226867)\]
- \[TPDS'23\] From Deterioration to Acceleration: A Calibration Approach to Rehabilitating Step Asynchronism in Federated Optimization - \[[PDF](https://doi.org/10.1109/TPDS.2023.3250513)\]
- \[TPDS'23\] Energy-Aware, Device-to-Device Assisted Federated Learning in Edge Computing - \[[PDF](https://doi.org/10.1109/TPDS.2023.3277423)\]
- \[TPDS'23\] HiFlash: Communication-Efficient Hierarchical Federated Learning With Adaptive Staleness Control and Heterogeneity-Aware Client-Edge Association - \[[PDF](https://doi.org/10.1109/TPDS.2023.3238049)\]
- \[TPDS'23\] HierFedML: Aggregator Placement and UE Assignment for Hierarchical Federated Learning in Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TPDS.2022.3218807)\]
- \[ToN'23\] Scheduling In-Band Network Telemetry With Convergence-Preserving Federated Learning - \[[PDF](https://doi.org/10.1109/TNET.2023.3253302)\]
- \[ToN'23\] Optimizing Parameter Mixing Under Constrained Communications in Parallel Federated Learning - \[[PDF](https://doi.org/10.1109/TNET.2023.3257236)\]
- \[TMC'23\] Distributed Traffic Synthesis and Classification in Edge Networks: A Federated Self-supervised Learning Approach - \[[PDF](https://doi.org/10.1109/TMC.2023.3240821)\]
- \[TMC'23\] A Personalized Privacy Preserving Mechanism for Crowdsourced Federated Learning - \[[PDF](https://doi.org/10.1109/TMC.2023.3237636)\]
- \[TMC'23\] Mobile Collaborative Learning over Opportunistic Internet of Vehicles - \[[PDF](https://doi.org/10.1109/TMC.2023.3273425)\]
- \[TMC'23\] Tree Learning: Towards Promoting Coordination in Scalable Multi-Client Training Acceleration - \[[PDF](https://doi.org/10.1109/TMC.2023.3259007)\]
- \[TMC'23\] PromptFL: Let Federated Participants Cooperatively Learn Prompts Instead of Models - Federated Learning in Age of Foundation Model - \[[PDF](https://doi.org/10.1109/TMC.2023.3302410)\]
- \[TMC'23\] Enabling Long-Term Cooperation in Cross-Silo Federated Learning: A Repeated Game Perspective - \[[PDF](https://doi.org/10.1109/TMC.2022.3148263)\]
- \[TMC'23\] Energy or Accuracy? Near-Optimal User Selection and Aggregator Placement for Federated Learning in MEC - \[[PDF](https://doi.org/10.1109/TMC.2023.3262829)\]
- \[TKDE'23\] Adaptive Clustering based Personalized Federated Learning Framework for Next POI Recommendation with Location Noise - \[[PDF](https://doi.org/10.1109/TKDE.2023.3312511)\]
- \[TGCN'23\] Exploiting UAV for Air–Ground Integrated Federated Learning: A Joint UAV Location and Resource Optimization Approach - \[[PDF](https://doi.org/10.1109/TGCN.2023.3242999)\]
- \[TC'23\] Towards Data-Independent Knowledge Transfer in Model-Heterogeneous Federated Learning - \[[PDF](https://doi.org/10.1109/TC.2023.3272801)\]
- \[JSTSP'23\] Knowledge Selection and Local Updating Optimization for Federated Knowledge Distillation With Heterogeneous Models - \[[PDF](https://doi.org/10.1109/JSTSP.2022.3223526)\]
- \[JSAC'23\] nFEDge: A Blockchain-Based Incentive Mechanism in Hierarchical Federated Learning for End-Edge-Cloud Communications - \[[PDF](https://doi.org/10.1109/JSAC.2022.3213323)\]
- \[IOTJ'23\] Multicore Federated Learning for Mobile-Edge Computing Platforms - \[[PDF](https://doi.org/10.1109/JIOT.2022.3224239)\]
- \[INFOCOM'23\] Joint Edge Aggregation and Association for Cost-Efficient Multi-Cell Federated Learning - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229060)\]
- \[INFOCOM'23\] Communication-Efficient Federated Learning for Heterogeneous Edge Devices Based on Adaptive Gradient Quantization - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228970)\]
- \[INFOCOM'23\] AnycostFL: Efficient On-Demand Federated Learning over Heterogeneous Edge Devices - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229017)\]
- \[INFOCOM WKSHPS'23\] Federated Learning at the Edge: An Interplay of Mini-batch Size and Aggregation Frequency - \[[PDF](https://doi.org/10.1109/INFOCOMWKSHPS57453.2023.10226109)\]
- \[ICC WKSHPS'23\] Decentralized Federated Learning With Asynchronous Parameter Sharing - \[[PDF](https://doi.org/10.1109/ICCCWorkshops57813.2023.10233712)\]
- \[ICASSP'23\] Semi-Federated Learning for Edge Intelligence with Imperfect SIC - \[[PDF](https://doi.org/10.1109/ICASSP49357.2023.10095782)\]
- \[arXiv'23\] FedFA: Federated Learning with Feature Anchors to Align Features and Classifiers for Heterogeneous Data - \[[PDF](http://arxiv.org/abs/2211.09299)\]
- \[arXiv'23\] Understanding Model Averaging in Federated Learning on Heterogeneous Data - \[[PDF](http://arxiv.org/abs/2305.07845)\]
- \[arXiv'23\] MimiC: Combating Client Dropouts in Federated Learning by Mimicking Central Updates - \[[PDF](http://arxiv.org/abs/2306.12212)\]
- \[arXiv'23\] Channel and Gradient-Importance Aware Device Scheduling for Over-the-Air Federated Learning - \[[PDF](http://arxiv.org/abs/2305.16854)\]
- \[arXiv'23\] Selective Knowledge Sharing for Privacy-Preserving Federated Distillation without A Good Teacher - \[[PDF](http://arxiv.org/abs/2304.01731)\]
- \[arXiv'23\] Binary Federated Learning with Client-Level Differential Privacy - \[[PDF](http://arxiv.org/abs/2308.03320)\]
- \[arXiv'23\] Feature Matching Data Synthesis for Non-IID Federated Learning - \[[PDF](http://arxiv.org/abs/2308.04761)\]
- \[arXiv'23\] FedCiR: Client-Invariant Representation Learning for Federated Non-IID Features - \[[PDF](http://arxiv.org/abs/2308.15786)\]
- \[arXiv'23\] Federated Fine-tuning of Billion-Sized Language Models across Mobile Devices - \[[PDF](http://arxiv.org/abs/2308.13894)\]
- \[arXiv'23\] FedAdapter: Efficient Federated Learning for Modern NLP - \[[PDF](http://arxiv.org/abs/2205.10162)\]
- \[arXiv'23\] Device-centric Federated Analytics At Ease - \[[PDF](http://arxiv.org/abs/2206.11491)\]
- \[arXiv'23\] Efficient Federated Learning with Enhanced Privacy via Lottery Ticket Pruning in Edge Computing - \[[PDF](http://arxiv.org/abs/2305.01387)\]
- \[arXiv'23\] When Computing Power Network Meets Distributed Machine Learning: An Efficient Federated Split Learning Framework - \[[PDF](http://arxiv.org/abs/2305.12979)\]
- \[WCNC'22\] Semi-Decentralized Federated Edge Learning for Fast Convergence on Non-IID Data - \[[PDF](https://doi.org/10.1109/WCNC51071.2022.9771904)\]
- \[TPDS'22\] Reputation-Aware Hedonic Coalition Formation for Efficient Serverless Hierarchical Federated Learning - \[[PDF](https://doi.org/10.1109/TPDS.2021.3139039)\]
- \[TPDS'22\] PS+: A Simple yet Effective Framework for Fast Training on Parameter Server - \[[PDF](https://doi.org/10.1109/TPDS.2022.3200518)\]
- \[TPDS'22\] Incentive-Aware Autonomous Client Participation in Federated Learning - \[[PDF](https://doi.org/10.1109/TPDS.2022.3148113)\]
- \[TON'22\] Accelerating Federated Learning via Parallel Servers: A Theoretically Guaranteed Approach - \[[PDF](https://doi.org/10.1109/TNET.2022.3168939)\]
- \[TMC'22\] FLASH: Heterogeneity-Aware Federated Learning at Scale - \[[PDF](https://doi.org/10.1109/TMC.2022.3214234)\]
- \[TMC'22\] Collaboration in Participant-Centric Federated Learning: A Game-Theoretical Perspective - \[[PDF](https://doi.org/10.1109/TMC.2022.3194198)\]
- \[TITS'22\] Federated Learning Enabled Credit Priority Task Processing for Transportation Big Data - \[[PDF](https://doi.org/10.1109/TITS.2022.3210405)\]
- \[TBD'22\] Resource-Aware Federated Neural Architecture Search over Heterogeneous Mobile Devices - \[[PDF](https://doi.org/10.1109/TBDATA.2022.3227403)\]
- \[SenSys'22\] TailorFL: Dual-Personalized Federated Learning under System and Data Heterogeneity - \[[PDF](https://dl.acm.org/doi/10.1145/3560905.3568503)\]
- \[SECON'22\] Energy-efficient Federated Learning via Stabilization-aware On-device Update Scaling - \[[PDF](https://doi.org/10.1109/SECON55815.2022.9918541)\]
- \[MobiSys'22\] Melon: breaking the memory wall for resource-efficient on-device machine learning - \[[PDF](https://doi.org/10.1145/3498361.3538928)\]
- \[MobiSys'22\] FedBalancer: data and pace control for efficient federated learning on heterogeneous clients - \[[PDF](https://doi.org/10.1145/3498361.3538917)\]
- \[INFOCOM'22\] A Profit-Maximizing Model Marketplace with Differentially Private Federated Learning - \[[PDF](https://doi.org/10.1109/INFOCOM48880.2022.9796833)\]
- \[arXiv'22\] Exploiting Personalized Invariance for Better Out-of-distribution Generalization in Federated Learning - \[[PDF](http://arxiv.org/abs/2211.11243)\]
- \[arXiv'22\] FedTune: A Deep Dive into Efficient Federated Fine-Tuning with Pre-trained Transformers - \[[PDF](http://arxiv.org/abs/2211.08025)\]

## Edge Inference
- \[TMC'24\] [DVFO: Learning-Based DVFS for Energy-Efficient Edge-Cloud Collaborative Inference](content/2024/tmc24-dvfo.md) - \[[PDF](https://ieeexplore.ieee.org/abstract/document/10412103)\]
- \[TMC'24\] Distributed DNN Inference with Fine-grained Model Partitioning in Mobile Edge Computing Networks - \[[PDF](https://ieeexplore.ieee.org/document/10413648/)\]
- \[WWW'24\] Unlocking the Non-deterministic Computing Power with Memory-Elastic Multi-Exit Neural Networks - \[[PDF](https://doi.org/10.1145/3589334.3645340)\]
- \[TMC'24\] MoEI: Mobility-Aware Edge Inference Based on Model Partition and Service Migration - \[[PDF](https://ieeexplore.ieee.org/document/10438028/)\]
- \[TSC'24\] Incentive-Aware Partitioning and Offloading Scheme for Inference Services in Edge Computing - \[[PDF](https://ieeexplore.ieee.org/document/10415185/)\]
- \[TMC'23\] [EdgeAdaptor: Online configuration adaption, model selection and resource provisioning for edge DNN inference serving at scale](content/2023/tmc23-edgeadaptor.md) - \[[PDF](https://doi.org/10.1109/TMC.2022.3189186)\]
- \[TMC'23\] PICO: Pipeline Inference Framework for Versatile CNNs on Diverse Mobile Devices - \[[PDF](https://doi.org/10.1109/TMC.2023.3265111)\]
- \[INFOCOM'23\] Cross-Camera Inference on the Constrained Edge - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229045)\]
- \[INFOCOM'23\] Adversarial Group Linear Bandits and Its Application to Collaborative Edge Inference - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228900)\]
- \[ToN'23\] Accelerating DNN Inference With Reliability Guarantee in Vehicular Edge Computing - \[[PDF](https://ieeexplore.ieee.org/document/10141674/)\]
- \[TWC'23\] Task-Oriented Communication for Edge Video Analytics - \[[PDF](https://doi.org/10.1109/TWC.2023.3314888)\]
- \[TWC'23\] Progressive Feature Transmission for Split Classification at the Wireless Edge - \[[PDF](https://doi.org/10.1109/TWC.2022.3221778)\]
- \[OSDI'23\] Optimizing Dynamic Neural Networks with Brainstorm - \[[PDF](https://www.usenix.org/conference/osdi23/presentation/cui)\]
- \[TMC'23\] AdaEvo: Edge-Assisted Continuous and Timely DNN Model Evolution for Mobile Devices - \[[PDF](https://doi.org/10.1109/TMC.2023.3316388)\]
- \[JSAC'23\] Resource Allocation for Multiuser Edge Inference With Batching and Early Exiting - \[[PDF](https://doi.org/10.1109/JSAC.2023.3242724)\]
- \[JSAC'23\] GNN at the Edge: Cost-Efficient Graph Neural Network Processing Over Distributed Edge Servers - \[[PDF](https://doi.org/10.1109/JSAC.2022.3229422)\]
- \[ICSOC'23\] Niagara: Scheduling DNN Inference Services on Heterogeneous Edge Processors - \[[PDF](https://doi.org/10.1007/978-3-031-48421-6_6)\]
- \[arXiv'23\] Task-Oriented Communication with Out-of-Distribution Detection: An Information Bottleneck Framework - \[[PDF](http://arxiv.org/abs/2305.12423)\]
- \[arXiv'23\] Joint Batching and Scheduling for High-Throughput Multiuser Edge AI with Asynchronous Task Arrivals - \[[PDF](http://arxiv.org/abs/2307.14350)\]
- \[arXiv'23\] Adaptive DNN Surgery for Selfish Inference Acceleration with On-demand Edge Resource - \[[PDF](http://arxiv.org/abs/2306.12185)\]
- \[arXiv'23\] Serving MoE Models on Resource-constrained Edge Devices via Dynamic Expert Swapping - \[[PDF](http://arxiv.org/abs/2308.15030)\]
- \[arXiv'23\] Accelerating In-Browser Deep Learning Inference on Diverse Edge Clients through Just-in-Time Kernel Optimizations - \[[PDF](http://arxiv.org/abs/2309.08978)\]
- \[TWC'22\] Task-Oriented Communication for Multi-Device Cooperative Edge Inference - \[[PDF](https://doi.org/10.1109/TWC.2022.3191118)\]
- \[TWC'22\] Data Partition and Rate Control for Learning and Energy Efficient Edge Intelligence - \[[PDF](https://doi.org/10.1109/TWC.2022.3173262)\]
- \[TMC'22\] Hastening Stream Offloading of Inference via Multi-exit DNNs in Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TMC.2022.3218724)\]
- \[TMC'22\] EdgeAdaptor: Online Configuration Adaption, Model Selection and Resource Provisioning for Edge DNN Inference Serving at Scale - \[[PDF](https://doi.org/10.1109/TMC.2022.3189186)\]
- \[MobiSys'22\] CoDL: efficient CPU-GPU co-execution for deep learning inference on mobile devices - \[[PDF](https://dl.acm.org/doi/10.1145/3498361.3538932)\]
- \[MICRO'22\] ANT: Exploiting Adaptive Numerical Data Type for Low-bit Deep Neural Network Quantization - \[[PDF](https://doi.org/10.1109/MICRO56248.2022.00095)\]
- \[JSA'22\] Edge intelligence in motion: Mobility-aware dynamic DNN inference service migration with downtime in mobile edge computing - \[[PDF](https://doi.org/10.1016/j.sysarc.2022.102664)\]
- \[JSA'22\] Inference replication at edges via combinatorial multi-armed bandit - \[[PDF](https://doi.org/10.1016/j.sysarc.2022.102636)\]
- \[MobiCom'21\] [Elf: accelerate high-resolution mobile deep vision with content-aware parallel offloading](content/before2022/mobicom21-elf.md) - \[[PDF](https://doi.org/10.1145/3447993.3448628)\] \[[Code](https://github.com/wuyangzhang/elf)\]

## Serverless Computing
- \[TSC'24\] [faasHouse: Sustainable Serverless Edge Computing through Energy-aware Resource Scheduling](content/2024/tsc24-faashouse.md) - \[[PDF](https://doi.org/10.1109/TSC.2024.3354296)\]
- \[WWW'24\] DirectFaaS: A Clean-Slate Network Architecture for Efficient Serverless Chain Communications - \[[PDF](https://doi.org/10.1145/3589334.3645333)\]
- \[INFOCOM'24\] On Efficient Zygote Container Planning and Task Scheduling for Edge Native Application Acceleration - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621106)\]
- \[TMC'24\] Taming Serverless Cold Start of Cloud Model Inference with Edge Computing - \[[PDF](https://ieeexplore.ieee.org/document/10376304/)\]
- \[INFOCOM'23\] [Enabling age-aware big data analytics in serverless edge clouds](content/2023/infocom23-enabling.md) - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228905)\]
- \[INFOCOM'23\] Online Container Scheduling for Data-intensive Applications in Serverless Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229034)\]
- \[INFOCOM'23\] On Efficient Zygote Container Planning toward Fast Function Startup in Serverless Edge Cloud - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228916)\]
- \[TPDS'21\] [Dependent function embedding for distributed serverless edge computing](content/before2022/tpds21-dpe.md) - \[[PDF](https://doi.org/10.1109/TPDS.2021.3137380)\] \[[Code](https://github.com/hliangzhao/embedding)\]

## Large Language Models (LLMs) / Small Language Models (SLMs)
- \[arXiv'24\] OpenELM: An Efficient Language Model Family with Open Training and Inference Framework - \[[PDF](https://arxiv.org/abs/2404.14619)\] \[[Code](https://github.com/apple/corenet)\] \[[HuggingFace](https://huggingface.co/apple/OpenELM)\]
- \[arXiv'24\] FOX-1 TECHNICAL REPORT - \[[PDF](https://arxiv.org/abs/2411.05281)\] \[[HuggingFace](https://huggingface.co/tensoropera/Fox-1-1.6B)\]
- \[arXiv'24\] Tinyllama: An open-source small language model - \[[PDF](https://arxiv.org/abs/2401.02385)\] \[[Code](https://github.com/jzhang38/TinyLlama)\]
- \[arXiv'24\] MobileVLM V2: Faster and Stronger Baseline for Vision Language Model - \[[PDF](https://arxiv.org/abs/2402.03766)\] \[[Code](https://github.com/Meituan-AutoML/MobileVLM)\]
- \[arXiv'24\] AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration - \[[PDF](https://arxiv.org/abs/2306.00978)\] \[[Code](https://github.com/mit-han-lab/llm-awq)\]
- \[arXiv'24\] MobileAIBench: Benchmarking LLMs and LMMs for On-Device Use Cases - \[[PDF](https://arxiv.org/abs/2406.10290)\]
- \[arXiv'24\] The Era of 1-bit LLMs: All Large Language Models are in 1.58 Bits - \[[PDF](https://arxiv.org/abs/2402.17764)\]
- \[arXiv'24\] Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone - \[[PDF](https://arxiv.org/abs/2404.14219)\]
- \[arXiv'24\] Exploring post-training quantization in llms from comprehensive study to low rank compensation - \[[PDF](https://arxiv.org/abs/2303.08302)\]
- \[OSDI'24\] [ServerlessLLM: Low-Latency Serverless Inference for Large Language Models](content/2024/osdi24-serverlessllm.md) - \[[PDF](https://www.usenix.org/conference/osdi24/presentation/fu)\] \[[Code](https://github.com/ServerlessLLM/ServerlessLLM)\]
- \[EdgeFM'24\] Large Language Models on Mobile Devices: Measurements, Analysis, and Insights - \[[PDF](https://doi.org/10.1145/3662006.3662059)\]
- \[arXiv'24\] vTensor: Flexible Virtual Tensor Management for Efficient LLM Serving - \[[PDF](http://arxiv.org/abs/2407.15309)\]
- \[arXiv'24\] Toward Scalable Generative AI via Mixture of Experts in Mobile Edge Networks - \[[PDF](http://arxiv.org/abs/2402.06942)\]
- \[EuroSys'23\] [Tabi: An Efficient Multi-Level Inference System for Large Language Models](content/2023/eurosys23-tabi.md) - \[[PDF](https://doi.org/10.1145/3552326.3587438)\]

## Graph Processing/Scheduling
- \[WWW'24\] [λGrapher: A Resource-Efficient Serverless System for GNN Serving through Graph Sharing](content/2024/www24-lagrapher.md) - \[[PDF](https://doi.org/10.1145/3589334.3645383)\]
- \[TMC'24\] [Startup-aware Dependent Task Scheduling with Bandwidth Constraints in Edge Computing](content/2024/tmc24-sdts.md) - \[[PDF](https://doi.org/10.1109/TMC.2023.3238868)\]
- \[ToN'24\] Serving Graph Neural Networks With Distributed Fog Servers for Smart IoT Services - \[[PDF](https://ieeexplore.ieee.org/document/10189178/?arnumber=10189178)\]
- \[arXiv'24\] Graph Neural Networks Automated Design and Deployment on Device-Edge Co-Inference Systems - \[[PDF](http://arxiv.org/abs/2404.05605)\]
- \[TOSN'23\] [DAG Scheduling in Mobile Edge Computing](content/2023/tosn23-dag.md) - \[[PDF](https://doi.org/10.1145/3616374)\]
- \[INFOCOM'23\] [Two-level Graph Caching for Expediting Distributed GNN Training](content/2023/infocom23-twolevel.md) - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228911)\]
- \[WWW'22\] [Fograph: Enabling real-time deep graph inference with fog computing](content/2022/www22-fograph.md) - \[[PDF](https://dl.acm.org/doi/10.1145/3485447.3511982)\]

## Optimization for Edge systems
- \[WWW'24\] MatchNAS: Optimizing Edge AI in Sparse-Label Data Contexts via Automating Deep Neural Network Porting for Mobile Deployment - \[[PDF](https://doi.org/10.1145/3589334.3645538)\]
- \[INFOCOM'24\] [Online Resource Allocation for Edge Intelligence with Colocated Model Retraining and Inference](content/2024/infocom24-orric.md) - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621206)\] \[[Code](https://github.com/caihuaiguang/ORRIC.git)\]
- \[INFOCOM'24\] EdgeTimer: Adaptive Multi-Timescale Scheduling in Mobile Edge Computing with Deep Reinforcement Learning - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621305)\]
- \[INFOCOM'24\] In-Orbit Processing or Not? Sunlight-Aware Task Scheduling for Energy-Efficient Space Edge Computing Networks - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621268)\]
- \[INFOCOM'24\] VeriEdge: Verifying and Enforcing Service Level Agreements for Pervasive Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621128)\]
- \[TMC'24\] Joint task offloading and resource allocation in heterogeneous edge environments - \[[PDF](https://doi.org/10.1109/TMC.2023.3335198)\]
- \[TMC'24\] Deep Learning-Assisted Online Task Offloading for Latency Minimization in Heterogeneous Mobile Edge - \[[PDF](https://ieeexplore.ieee.org/document/10158235/)\]
- \[INFOCOM'23\] [FEAT: Towards Fast Environment-Adaptive Task Offloading and Power Allocation in MEC](content/2023/infocom23-feat.md) - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228946)\]
- \[INFOCOM'23\] Latency-Optimal Pyramid-based Joint Communication and Computation Scheduling for Distributed Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228964)\]
- \[INFOCOM'23\] Dynamic Edge-centric Resource Provisioning for Online and Offline Services Co-location - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228949)\]
- \[INFOCOM'23\] Layered Structure Aware Dependent Microservice Placement Toward Cost Efficient Edge Clouds - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229030)\]
- \[INFOCOM'23\] Latency-Optimal Pyramid-based Joint Communication and Computation Scheduling for Distributed Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228964)\]
- \[INFOCOM'23\] AdaptSLAM: Edge-Assisted Adaptive SLAM with Resource Constraints via Uncertainty Minimization - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229009)\] \[[Code](https://github.com/i3tyc/AdaptSLAM)\]
- \[JSAC'23\] [Dependent task scheduling and offloading for minimizing deadline violation ratio in mobile edge computing networks](content/2023/jsac23-dependent.md) - \[[PDF](https://doi.org/10.1109/JSAC.2022.3233532)\]
- \[TSC'23\] Role-Based User Allocation Driven by Criticality in Edge Computing - \[[PDF](https://doi.org/10.1109/TSC.2023.3280498)\]
- \[TSC'23\] Joint Optimization of Coverage and Reliability for Application Placement in Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TSC.2023.3296742)\]
- \[TPDS'23\] CoopEdge+: Enabling Decentralized, Secure and Cooperative Multi-Access Edge Computing Based on Blockchain - \[[PDF](https://doi.org/10.1109/TPDS.2022.3231296)\]
- \[TPDS'23\] EESaver: Saving Energy Dynamically for Green Multi-Access Edge Computing - \[[PDF](https://doi.org/10.1109/TPDS.2023.3277619)\]
- \[TPDS'23\] ProScale: Proactive Autoscaling for Microservice With Time-Varying Workload at the Edge - \[[PDF](https://doi.org/10.1109/TPDS.2023.3238429)\]
- \[TNSE'23\] Re-Scheduling IoT Services in Edge Networks - \[[PDF](https://doi.org/10.1109/TNSM.2023.3242937)\]
- \[TMC'23\] OL-EUA: Online User Allocation for NOMA-Based Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TMC.2021.3112941)\]
- \[TMC'23\] Multi-Agent Deep Reinforcement Learning Based UAV Trajectory Optimization for Differentiated Services - \[[PDF](https://doi.org/10.1109/TMC.2023.3312276)\]
- \[TMC'23\] Lightweight Imitation Learning for Real-Time Cooperative Service Migration - \[[PDF](https://doi.org/10.1109/TMC.2023.3239845)\]
- \[IWQoS'23\] OSCA: Online User-managed Server Selection and Configuration Adaptation for Interactive MAR - \[[PDF](https://doi.org/10.1109/IWQoS57198.2023.10188796)\]
- \[TSC'22\] ST-EUA: Spatio-temporal Edge User Allocation with Task Decomposition - \[[PDF](https://doi.org/10.1109/TSC.2022.3144441)\]
- \[TPDS'22\] Joint Application Placement and Request Routing Optimization for Dynamic Edge Computing Service Management - \[[PDF](https://doi.org/10.1109/TPDS.2022.3195205)\]
- \[TMC'22\] Online User and Power Allocation in Dynamic NOMA-Based Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TMC.2022.3193366)\]
- \[TMC'22\] Price Competition in Multi-Server Edge Computing Networks under SAA and SIQ Models - \[[PDF](https://doi.org/10.1109/TMC.2022.3227675)\]
- \[IWQoS'22\] An Online Approach for DNN Model Caching and Processor Allocation in Edge Computing - \[[PDF](https://doi.org/10.1109/IWQoS54832.2022.9812874)\]
- \[INFOCOM'22\] Two Time-Scale Joint Service Caching and Task Offloading for UAV-assisted Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM48880.2022.9796714)\]
- \[INFOCOM'22\] Online File Caching in Latency-Sensitive Systems with Delayed Hits and Bypassing - \[[PDF](https://doi.org/10.1109/INFOCOM48880.2022.9796969)\]
- \[ICPP'22\] Energy-efficient Edge Server Management for Edge Computing: A Game-theoretical Approach - \[[PDF](https://doi.org/10.1145/3545008.3545079)\]
- \[CN'22\] Adaptive provisioning for mobile cloud gaming at edges - \[[PDF](https://doi.org/10.1016/j.comnet.2021.108704)\]

## Edge AI Systems
- \[INFOCOM'24\] Galaxy: A Resource-Efficient Collaborative Edge AI System for In-situ Transformer Inference - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621342)\]
- \[INFOCOM'24\] T-PRIME: Transformer-based Protocol Identification for Machine-learning at the Edge - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621284)\]
- \[INFOCOM'23\] [Tapfinger: Task placement and fine-grained resource allocation for edge machine learning](content/2023/infocom23-tapfinger.md) - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229031)\] \[[Code](https://github.com/nooblyh/TapFinger.git)\]
- \[TCC'23\] AI-Bazaar: A Cloud-Edge Computing Power Trading Framework for Ubiquitous AI Services - \[[PDF](https://doi.org/10.1109/TCC.2022.3201544)\]
- \[arXiv'23\] Message Passing Meets Graph Neural Networks: A New Paradigm for Massive MIMO Systems - \[[PDF](http://arxiv.org/abs/2302.06896)\]
- \[arXiv'23\] Efficient Parallel Split Learning over Resource-constrained Wireless Edge Networks - \[[PDF](http://arxiv.org/abs/2303.15991)\]
- \[WWW'22\] Pyramid: Enabling Hierarchical Neural Networks with Edge Computing - \[[PDF](https://dl.acm.org/doi/10.1145/3485447.3511990)\]
- \[JCIN'22\] Resource-Constrained Edge AI with Early Exit Prediction - \[[PDF](https://doi.org/10.23919/JCIN.2022.9815196)\]
- \[ICC'22\] Loading Cost-Aware Model Caching and Request Routing for Cooperative Edge Inference - \[[PDF](https://doi.org/10.1109/ICC45855.2022.9838823)\]

## System-Level Analytics & Evaluation
- \[INFOCOM'24\] QM-RGNN: An Efficient Online QoS Measurement Framework with Sparse Matrix Imputation for Distributed Edge Clouds - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621145)\]
- \[WWW'24\] [PASS: Predictive Auto-Scaling System for Large-scale Enterprise Web Applications](content/2024/www24-pass.md) - \[[PDF](https://doi.org/10.1145/3589334.3645330)\]
- \[KDD'23\] [One for All: Unified Workload Prediction for Dynamic Multi-tenant Edge Cloud Platforms](content/2023/kdd23-dyneformer.md) - \[[PDF](https://dl.acm.org/doi/abs/10.1145/3580305.3599453)\] \[[Code](https://github.com/hsy23/KDD23_DynEformer)\]
- \[WWW'23\] ELASTIC: Edge Workload Forecasting based on Collaborative Cloud-Edge Deep Learning - \[[PDF](https://doi.org/10.1145/3543507.3583436)\]
- \[TKDE'23\] A Measurement-Driven Analysis and Prediction of Content Propagation in the Device-to-Device Social Networks - \[[PDF](https://doi.org/10.1109/TKDE.2022.3219399)\]
- \[IWQoS'23\] How Far Have Edge Clouds Gone? A Spatial-Temporal Analysis of Edge Network Latency In the Wild - \[[PDF](https://doi.org/10.1109/IWQoS57198.2023.10188741)\]
- \[IWQoS'23\] A Holistic QoS View of Crowdsourced Edge Cloud Platform - \[[PDF](https://doi.org/10.1109/IWQoS57198.2023.10188726)\]
- \[WWWJ'23\] A large-scale holistic measurement of crowdsourced edge cloud platform - \[[PDF](https://doi.org/10.1007/s11280-023-01201-y)\]
- \[TMC'23\] A Comprehensive Deep Learning Library Benchmark and Optimal Library Selection - \[[PDF](https://doi.org/10.1109/TMC.2023.3301973)\]
- \[WWW'22\] Commutativity-guaranteed Docker Image Reconstruction towards Effective Layer Sharing - \[[PDF](https://dl.acm.org/doi/10.1145/3485447.3512154)\]
- \[TMC'22\] Fine-Grained Spatio-Temporal Distribution Prediction of Mobile Content Delivery in 5G Ultra-Dense Networks - \[[PDF](https://doi.org/10.1109/TMC.2022.3226448)\]
- \[arXiv'22\] Benchmarking of DL Libraries and Models on Mobile Devices - \[[PDF](https://arxiv.org/abs/2202.06512)\]
- \[arXiv'22\] SoC-Cluster as an Edge Server: an Application-driven Measurement Study - \[[PDF](http://arxiv.org/abs/2212.12842)\]

## Edge Security & Privacy
- \[WWW'24\] [Poisoning Attack on Federated Knowledge Graph Embedding](content/2024/www24-poisoning.md) - \[[PDF](https://doi.org/10.1145/3589334.3645422)\] \[[Code](https://doi.org/10.5281/zenodo.10646619)\]
- \[WWW'24\] [GEES: Enabling Location Privacy-Preserving Energy Saving in Multi-Access Edge Computing](content/2024/www24-gees.md) - \[[PDF](https://doi.org/10.1145/3589334.3645329)\] \[[Code & Datasets](https://github.com/ziqiwang20/LEDR)\]
- \[TWC'23\] Securing Large-Scale D2D Networks Using Covert Communication and Friendly Jamming - \[[PDF](https://doi.org/10.1109/TWC.2023.3280464)\]
- \[TMC'23\] On the Robustness of Channel Allocation in Joint Radar and Communication Systems: An Auction Approach - \[[PDF](https://doi.org/10.1109/TMC.2023.3276934)\]
- \[ToN'23\] Privacy Protection Under Incomplete Social and Data Correlation Information - \[[PDF](https://doi.org/10.1109/TNET.2023.3254549)\]
- \[KDD'23\] Investigating Trojan Attacks on Pre-trained Language Model-powered Database Middleware - \[[PDF](https://dl.acm.org/doi/10.1145/3580305.3599395)\]
- \[MobiCom'23\] Enc2: Privacy-Preserving Inference for Tiny IoTs via Encoding and Encryption - \[[PDF](https://dl.acm.org/doi/10.1145/3570361.3592501)\]
- \[INFOCOM'23\] Mind Your Heart: Stealthy Backdoor Attack on Dynamic Deep Neural Network in Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229092)\]

## On-Device Intelligence
- \[WWW'24\] Towards Energy-efficient Federated Learning via INT8-based Training on Mobile DSPs - \[[PDF](https://doi.org/10.1145/3589334.3645341)\]
- \[WWW'24\] Cold Start or Hot Start? Robust Slow Start in Congestion Control with A Priori Knowledge for Mobile Web Services - \[[PDF](https://doi.org/10.1145/3589334.3645393)\]
- \[INFOCOM'24\] edgeSLAM2: Rethinking Edge-Assisted Visual SLAM with On-Chip Intelligence - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621278)\]
- \[INFOCOM'24\] Minimizing Latency for Multi-DNN Inference on Resource-Limited CPU-Only Edge Devices - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621120)\]
- \[MobiSys'23\] [Boosting DNN Cold Inference on Edge Devices](content/2023/mobisys23-nnv12.md) - \[[PDF](https://doi.org/10.1145/3581791.3596842)\] \[[Code](https://github.com/UbiquitousLearning/NNV12)\]
- \[MobiCom'23\] [SWAM: Revisiting Swap and OOMK for Improving Application Responsiveness on Mobile Devices](content/2023/mobicom23-swam.md) - \[[PDF](https://doi.org/10.1145/3570361.3592518)\] \[[Code](https://mobile-swam.github.io/)\]
- \[TMC'23\] AdaEvo: Edge-Assisted Continuous and Timely DNN Model Evolution for Mobile Devices - \[[PDF](https://doi.org/10.1109/TMC.2023.3316388)\]
- \[MWUT'23\] DAPPER: Label-Free Performance Estimation after Personalization for Heterogeneous Mobile Sensing - \[[PDF](https://dl.acm.org/doi/10.1145/3596256)\]
- \[MobiSys'23\] NN-Stretch: Automatic Neural Network Branching for Parallel Inference on Heterogeneous Multi-Processors - \[[PDF](https://dl.acm.org/doi/10.1145/3581791.3596870)\]
- \[MobiCom'23\] AdaptiveNet: Post-deployment Neural Architecture Adaptation for Diverse Edge Environments - \[[PDF](https://dl.acm.org/doi/10.1145/3570361.3592529)\]
- \[MobiCom'23\] LUT-NN: Empower Efficient Neural Network Inference with Centroid Learning and Table Lookup - \[[PDF](https://doi.org/10.1145/3570361.3613285)\]
- \[MobiCom'23\] Re-thinking computation offload for efficient inference on IoT devices with duty-cycled radios - \[[PDF](https://dl.acm.org/doi/10.1145/3570361.3592514)\]
- \[MobiCom'23\] Cost-effective On-device Continual Learning over Memory Hierarchy with Miro - \[[PDF](https://dl.acm.org/doi/10.1145/3570361.3613297)\]
- \[arXiv'23\] Generative Model for Models: Rapid DNN Customization for Diverse Tasks and Resource Constraints - \[[PDF](http://arxiv.org/abs/2308.15003)\]
- \[arXiv'23\] Empowering LLM to use Smartphone for Intelligent Task Automation - \[[PDF](http://arxiv.org/abs/2308.15272)\]
- \[SenSys'22\] Hyperion: A Generic and Distributed Mobile Offloading Framework on OpenCL - \[[PDF](https://dl.acm.org/doi/10.1145/3560905.3568511)\]
- \[MobiCom'22\] MobiDepth: real-time depth estimation using on-device dual cameras - \[[PDF](https://dl.acm.org/doi/10.1145/3495243.3560517)\]

## Video Analytics
- \[INFOCOM'24\] Gecko: Resource-Efficient and Accurate Queries in Real-Time Video Streams at the Edge - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621399)\]
- \[INFOCOM'24\] Rosevin: Employing Resource- and Rate-Adaptive Edge Super-Resolution for Video Streaming - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621104)\]
- \[INFOCOM'24\] Smart Data-Driven Proactive Push to Edge Network for User-Generated Videos - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621410)\]
- \[INFOCOM'24\] BiSwift: Bandwidth Orchestrator for Multi-Stream Video Analytics on Edge - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621392)\]
- \[WWW'24\] NCTM: A Novel Coded Transmission Mechanism for Short Video Deliveries - \[[PDF](https://doi.org/10.1145/3589334.3645387)\]
- \[MobiCom'23\] [AccuMO: Accuracy-centric multitask offloading in edge-assisted mobile augmented reality](content/2023/mobicom23-accumo.md) - \[[PDF](https://doi.org/10.1145/3570361.3592531)\] \[[Code](https://github.com/JonnyKong/AccuMO)\]
- \[MobiCom'23\] NeuriCam: Key-Frame Video Super-Resolution and Colorization for IoT Cameras - \[[PDF](https://dl.acm.org/doi/10.1145/3570361.3592523)\]
- \[INFOCOM'23\] [Who is the Rising Star? Demystifying the Promising Streamers in Crowdsourced Live Streaming](content/2023/infocom23-niffler.md) - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228881)\]
- \[INFOCOM'23\] [ResMap: Exploiting Sparse Residual Feature Map for Accelerating Cross-Edge Video Analytics](content/2023/infocom23-resmap.md) - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228990)\] \[[Code](https://github.com/nju-cn/ResMap)\]
- \[INFOCOM'23\] OmniSense: Towards Edge-Assisted Online Analytics for 360-Degree Videos - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229105)\]
- \[INFOCOM'23\] Energy-Efficient 360-Degree Video Streaming on Multicore-Based Mobile Devices - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228863)\]
- \[INFOCOM'23\] EAVS: Edge-assisted Adaptive Video Streaming with Fine-grained Serverless Pipelines - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229102)\]
- \[TMC'23\] Live Migration of Video Analytics Applications in Edge Computing - \[[PDF](https://doi.org/10.1109/TMC.2023.3246539)\]
- \[TMC'23\] EMS: Erasure-Coded Multi-Source Streaming for UHD Videos Within Cloud Native 5G Networks - \[[PDF](https://doi.org/10.1109/TMC.2023.3238356)\]
- \[INFOCOM'23\] Crowd2: Multi-agent Bandit-based Dispatch for Video Analytics upon Crowdsourcing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228927)\]
- \[arXiv'23\] Low-complexity Deep Video Compression with A Distributed Coding Architecture - \[[PDF](http://arxiv.org/abs/2303.11599)\]
- \[SECON'22\] Focus! Provisioning Attention-aware Detection for Real-time On-device Video Analytics - \[[PDF](https://doi.org/10.1109/SECON55815.2022.9918169)\]
- \[ICC'22\] Multi-server Multi-user Game at Edges for Heterogeneous Video Analytics - \[[PDF](https://doi.org/10.1109/ICC45855.2022.9839250)\]

## Edge Cahcing
- \[INFOCOM'24\] Exploiting Storage for Computing: Computation Reuse in Collaborative Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621100)\]
- \[TMC'24\] FedCache: A Knowledge Cache-Driven Federated Learning Architecture for Personalized Edge Intelligence - \[[PDF](https://ieeexplore.ieee.org/document/10420495/)\]
- \[INFOCOM'23\] Economic Analysis of Joint Mobile Edge Caching and Peer Content Sharing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229068)\]
- \[INFOCOM'23\] Dynamic Regret of Randomized Online Service Caching in Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229044)\]
- \[TPDS'23\] A Proactive On-Demand Content Placement Strategy in Edge Intelligent Gateways - \[[PDF](https://doi.org/10.1109/TPDS.2023.3249797)\]
- \[TMC'23\] Efficient Algorithms for Service Chaining in NFV-Enabled Satellite Edge Networks - \[[PDF](https://doi.org/10.1109/TMC.2023.3312352)\]
- \[JSAC'23\] Federated Deep Reinforcement Learning for Recommendation-Enabled Edge Caching in Mobile Edge-Cloud Computing Networks - \[[PDF](https://doi.org/10.1109/JSAC.2023.3235443)\]
- \[TMC'22\] Near-Optimal and Collaborative Service Caching in Mobile Edge Clouds - \[[PDF](https://doi.org/10.1109/TMC.2022.3144175)\]
- \[TMC'22\] Stable Service Caching in MECs of Hierarchical Service Markets with Uncertain Request Rates - \[[PDF](https://doi.org/10.1109/TMC.2022.3149870)\]
- \[IPCCC'22\] Pricing in the Open Market of Crowdsourced Video Edge Caching: A Newcomer Perspective - \[[PDF](https://doi.org/10.1109/IPCCC55026.2022.9894319)\]

## Edge Data Storage/Analytics
- \[TPDS'23\] Enabling Balanced Data Deduplication in Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TPDS.2023.3247061)\]
- \[SIGIR'23\] EDIndex: Enabling Fast Data Queries in Edge Storage Systems - \[[PDF](https://doi.org/10.1145/3539618.3591676)\]
- \[TSC'22\] Data Caching Optimization With Fairness in Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TSC.2022.3197881)\]
- \[TSC'22\] Cost-Effective Data Placement in Edge Storage Systems with Erasure Code - \[[PDF](https://doi.org/10.1109/TSC.2022.3152849)\]
- \[TPDS'22\] CSEdge: Enabling Collaborative Edge Storage for Multi-Access Edge Computing Based on Blockchain - \[[PDF](https://doi.org/10.1109/TPDS.2021.3131680)\]
- \[KDD'22\] EdgeWatch: Collaborative Investigation of Data Integrity at the Edge based on Blockchain - \[[PDF](https://doi.org/10.1145/3534678.3539104)\]
- \[ICPP'22\] Formulating Interference-aware Data Delivery Strategies in Edge Storage Systems - \[[PDF](https://doi.org/10.1145/3545008.3545078)\]

## Cloud-Edge Systems
- \[INFOCOM'24\] Cur-CoEdge: Curiosity-Driven Collaborative Request Scheduling in Edge-Cloud Systems - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621190)\]
- \[TSC'23\] [CompCube: A Space-Time-Request Resource Trading Framework for Edge-Cloud Service Market](content/2023/tsc23-compcube.md) - \[[PDF](https://doi.org/10.1109/TSC.2023.3261553)\]
- \[ToN'23\] Collaborative Learning-Based Scheduling for Kubernetes-Oriented Edge-Cloud Network - \[[PDF](https://doi.org/10.1109/TNET.2023.3267168)\]
- \[JSAC'23\] EdgeMatrix: A Resource-Redefined Scheduling Framework for SLA-Guaranteed Multi-Tier Edge-Cloud Computing Systems - \[[PDF](https://doi.org/10.1109/JSAC.2022.3229444)\]

## Services Provision
- \[ToN'24\] [Mean Field Graph Based D2D Collaboration and Offloading Pricing in Mobile Edge Computing](content/2024/ton24-meanfield.md) - \[[PDF](https://doi.org/10.1109/TNET.2023.3288558)\]
- \[INFOCOM'24\] A Practical Near Optimal Deployment of Service Function Chains in Edge-to-Cloud Networks - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621162)\]
- \[INFOCOM'24\] Joint Optimization of Model Deployment for Freshness-Sensitive Task Assignment in Edge Intelligence - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621314)\]
- \[TC'23\] Stateful Serverless Application Placement in MEC With Function and State Dependencies - \[[PDF](https://doi.org/10.1109/TC.2023.3262947)\]
- \[INFOCOM'23\] Dynamic Edge-centric Resource Provisioning for Online and Offline Services Co-location - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228949)\]
- \[INFOCOM'23\] Digital Twin-Enabled Service Satisfaction Enhancement in Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228893)\]
- \[TSC'22\] Service Home Identification of Multiple-Source IoT Applications in Edge Computing - \[[PDF](https://doi.org/10.1109/TSC.2022.3176576)\]
- \[ToN'22\] Near Optimal Learning-Driven Mechanisms for Stable NFV Markets in Multitier Cloud Networks - \[[PDF](https://doi.org/10.1109/TNET.2022.3179295)\]
- \[TMC'22\] Digital Twin-Assisted, SFC-Enabled Service Provisioning in Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TMC.2022.3227248)\]
- \[TMC'22\] Budget-Aware User Satisfaction Maximization on Service Provisioning in Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/TMC.2022.3205427)\]
- \[MASS'22\] SFC-Enabled Reliable Service Provisioning in Mobile Edge Computing via Digital Twins - \[[PDF](https://doi.org/10.1109/MASS56207.2022.00052)\]
- \[INFOCOM'22\] Schedule or Wait: Age-Minimization for IoT Big Data Processing in MEC via Online Learning - \[[PDF](https://doi.org/10.1109/INFOCOM48880.2022.9796718)\]

## Sensing & Wireless Communications
- \[TSC'23\] RuleDRL: Reliability-Aware SFC Provisioning with Bounded Approximations in Dynamic Environments - \[[PDF](https://doi.org/10.1109/TSC.2023.3281759)\]
- \[ToN'23\] Reinforcement Learning-Based Particle Swarm Optimization for End-to-End Traffic Scheduling in TSN-5G Networks - \[[PDF](https://doi.org/10.1109/TNET.2023.3276363)\]
- \[TCOMM'23\] Mobility-Aware Proactive Flow Setup in Software-Defined Mobile Edge Networks - \[[PDF](https://doi.org/10.1109/TCOMM.2023.3238396)\]
- \[IWQoS'23\] Optimizing Average AoI with Directional Charging for Wireless-Powered Network Edge - \[[PDF](https://doi.org/10.1109/IWQoS57198.2023.10188771)\]
- \[arXiv'22\] Graph Neural Networks for Wireless Communications: From Theory to Practice - \[[PDF](http://arxiv.org/abs/2203.10800)\]
- \[TMC'23\] Decoupled Association with Rate Splitting Multiple Access in UAV-assisted Cellular Networks Using Multi-agent Deep Reinforcement Learning - \[[PDF](10.1109/TMC.2023.3256404)\]
- \[TMC'23\] Efficient Dynamic Distributed Resource Slicing in 6G Multi-Access Edge Computing Networks with Online ADMM and Message Passing Graph Neural Networks - \[[PDF](https://doi.org/10.1109/TMC.2023.3262514)\]
- \[JSAC'23\] Task-Oriented Delay-Aware Multi-Tier Computing in Cell-Free Massive MIMO Systems - \[[PDF](https://doi.org/10.1109/JSAC.2023.3280965)\]
- \[JSAC'23\] AI-Generated Incentive Mechanism and Full-Duplex Semantic Communications for Information Sharing - \[[PDF](https://doi.org/10.1109/JSAC.2023.3287547)\]
- \[JSAC'23\] Semantic Communications for Wireless Sensing: RIS-aided Encoding and Self-supervised Decoding - \[[PDF](https://doi.org/10.1109/JSAC.2023.3288231)\]
- \[arXiv'23\] Task-Oriented Integrated Sensing, Computation and Communication for Wireless Edge AI - \[[PDF](http://arxiv.org/abs/2306.06603)\]
- \[arXiv'23\] Joint Activity-Delay Detection and Channel Estimation for Asynchronous Massive Random Access - \[[PDF](https://doi.org/[10.1145/3543507.3583347](http://arxiv.org/abs/2305.12372))\]
- \[TMC'22\] [Wireless powered mobile edge computing: Dynamic resource allocation and throughput maximization](content/2022/tmc22-dtm.md) - \[[PDF](https://doi.org/10.1109/TMC.2020.3034479)\]
- \[TWC'22\] Joint Sensing and Communication-Rate Control for Energy Efficient Mobile Crowd Sensing - \[[PDF](https://doi.org/10.1109/TWC.2022.3204269)\]
- \[MobiCom'22\] Wirelessly powered integrated sensing and communication - \[[PDF](https://dl.acm.org/doi/10.1145/3556562.3558564)\]

## Unmanned Aerial Vehicle (UAV)
- \[INFOCOM'24\] An Online Joint Optimization Approach for QoE Maximization in UAV-Enabled Mobile Edge Computing - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621306)\]
- \[WWW'24\] Air-CAD: Edge-Assisted Multi-Drone Network for Real-time Crowd Anomaly Detection - \[[PDF](https://doi.org/10.1145/3589334.3645362)\]
- \[TMC'24\] [Multi-agent deep reinforcement learning based uav trajectory optimization for differentiated services](content/2024/tmc24-multiagent.md) - \[[PDF](https://doi.org/10.1109/TMC.2023.3312276)\]
- \[ToN'24\] [Incentive Mechanisms for Online Task Offloading With Privacy-Preserving in UAV-Assisted Mobile Edge Computing](content/2024/ton24-incentive.md) - \[[PDF](https://doi.org/10.1109/TNET.2024.3364141)\]
- \[INFOCOM'23\] WiSwarm: Age-of-Information-based Wireless Networking for Collaborative Teams of UAVs - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10228860)\]
- \[INFOCOM'23\] A2-UAV: Application-Aware Content and Network Optimization of Edge-Assisted UAV Systems - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229096)\]

## Mobile Crowdsensing
- \[INFOCOM'24\] Seer: Proactive Revenue-Aware Scheduling for Live Streaming Services in Crowdsourced Cloud-Edge Platforms - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621424)\]
- \[TMC'23\] AoI-guaranteed Incentive Mechanism for Mobile Crowdsensing with Freshness Concerns - \[[PDF](https://doi.org/10.1109/TMC.2023.3285779)\]
- \[TMC'23\] Incentive Mechanism for Spatial Crowdsourcing With Unknown Social-Aware Workers: A Three-Stage Stackelberg Game Approach - \[[PDF](https://doi.org/10.1109/TMC.2022.3157687)\]
- \[TMC'23\] Crowdsourcing Upon Learning: Energy-Aware Dispatch With Guarantee for Video Analytics - \[[PDF](https://doi.org/10.1109/TMC.2023.3269807)\]
- \[INFOCOM'23\] AoI-aware Incentive Mechanism for Mobile Crowdsensing using Stackelberg Game - \[[PDF](https://doi.org/10.1109/INFOCOM53939.2023.10229079)\]
- \[TMC'22\] Combination of Auction Theory and Multi-Armed Bandits: Model, Algorithm, and Application - \[[PDF](https://doi.org/10.1109/TMC.2022.3197459)\]

## Resource Allocation/Management
- \[INFOCOM'24\] [INVAR: Inversion Aware Resource Provisioning and Workload Scheduling for Edge Computing](content/2024/infocom24-invar.md) - \[[PDF](https://doi.org/10.1109/INFOCOM52122.2024.10621417)\]
- \[TWC'23\] Elastic Resource Allocation for Coded Distributed Computing Over Heterogeneous Wireless Edge Networks - \[[PDF](https://doi.org/10.1109/TWC.2022.3213256)\]
- \[TMC'23\] MetaSlicing: A Novel Resource Allocation Framework for Metaverse - \[[PDF](https://doi.org/10.1109/TMC.2023.3288085)\]
- \[TCOMM'23\] QoE Analysis and Resource Allocation for Wireless Metaverse Services - \[[PDF](https://doi.org/10.1109/TCOMM.2023.3282594)\]
- \[JSAC'23\] Attention-Aware Resource Allocation and QoE Analysis for Metaverse xURLLC Services - \[[PDF](https://doi.org/10.1109/JSAC.2023.3280978)\]

## Over-the-air Computation
- \[WCNC'23\] Task-Oriented Over-the-Air Computation for Multi-Device Edge Split Inference - \[[PDF](https://doi.org/10.1109/WCNC55385.2023.10118681)\]
- \[TWC'23\] Task-Oriented Over-the-Air Computation for Multi-Device Edge AI - \[[PDF](https://doi.org/10.1109/TWC.2023.3294703)\]
- \[arXiv'23\] Spectrum Breathing: Protecting Over-the-Air Federated Learning Against Interference - \[[PDF](http://arxiv.org/abs/2305.05933)\]
- \[JSAC'22\] Distributed Over-the-air Computing for Fast Distributed Optimization: Beamforming Design and Convergence Analysis - \[[PDF](https://doi.org/10.1109/JSAC.2022.3223661)\]

## Coded Distributed Computing
- \[TWC'23\] Elastic Resource Allocation for Coded Distributed Computing Over Heterogeneous Wireless Edge Networks - \[[PDF](https://doi.org/10.1109/TWC.2022.3213256)\]
- \[TMC'23\] Resource Optimization for UAV-assisted Wireless Power Charging Enabled Hybrid Coded Edge Computing Network - \[[PDF](https://doi.org/10.1109/TMC.2023.3246994)\]
- \[TMC'22\] Secure and Efficient Coded Multi-Access Edge Computing with Generalized Graph Neural Networks - \[[PDF](https://doi.org/10.1109/TMC.2022.3172117)\]
