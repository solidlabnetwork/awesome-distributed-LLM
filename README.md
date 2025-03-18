# awesome-distributed-LLM
An Evolving List of Distributed LLM and Multimodal LLM Papers and Repositories
---
**📝Note:** While we tried to include and review as many relevant articles as possible, we would like to ask the research community to share any recent/prior works that fit in the scope of this study for inclusion on the GitHub page as well as future versions of this survey paper. We will review each suggestion and include it if we realize it fits the scope of this survey. Please email your suggestions to solidlabnetwork@gmail.com and cc hadi.amini@ieee.org

---
This work is licensed under a Creative Commons Attribution 4.0 International License.

You are free to:
- Share — copy and redistribute the material in any medium or format.
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Full license text: https://creativecommons.org/licenses/by/4.0/
---
The following figure shows the connection of some of the 100 papers and how they contribute to various aspects of decentralizing the LLM pipeline. This figure shows four primary areas of research focus: Algorithmic Framework, Hardware Infrastructure, Data Layer, and Security and Privacy. 

![Algorithmic Framework](https://github.com/solidlabnetwork/awesome-distributed-LLM/blob/main/Figures/figint_001.jpg)

---
The following figure shows an overview of selected prior, current, and future research directions.

![Research Directions](https://github.com/solidlabnetwork/awesome-distributed-LLM/blob/main/Figures/figfuture_001.jpg)

---
**Link to access source file of figures:** [drive](https://drive.google.com/drive/folders/1ioSrvUvg2t2ulwOKisY_g-h_Ns9BDCfF?usp=drive_link)

# **Table of Contents**  
**I.** [Surveyed Papers on Distributed LLMs](#i-llms-surveys)  
**II.** [Surveyed Papers on VLMs](#ii-vlms-surveys)  
**III.** [Small Language Models (SLMs)](#iii-slms-surveys)  

---

# **I. Distributed LLMs** <a name="i-llms-surveys"></a>

| No. | Paper Title | Url | Code |
|----|-------------|------------|-------------|
| 1 | ✅[Survey Article]Distributed Training of Large Language Models | [Link](https://ieeexplore.ieee.org/abstract/document/10476280?casa_token=qIdCYZCjRqEAAAAA:2mcx2MhpY2y79qbg95ycYL2WhTd6oxrYxIrdR4fHjx4-8J_7GxWwOpIe1A6LQIPDKRj7kuvSJA) | N/A |
| 2 | Fast Distributed Inference Serving for Large Language Models | [Link](https://arxiv.org/pdf/2305.05920.pdf) | [GitHub](https://github.com/fast-inference-serving) |
| 3 | DistFlashAttn: Distributed Memory-Efficient Attention for Long-Context LLMs Training | [Link](https://arxiv.org/pdf/2406.02613.pdf) | [GitHub](https://github.com/fast-inference-serving) |
| 4| Acco: Accumulate While You Communicate, Hiding Communications in Distributed LLM Training | [Link](https://arxiv.org/pdf/2406.02613.pdf) | [GitHub](https://github.com/AdelNabli/ACCO) |
| 5 | Model Parallelism on Distributed Infrastructure: A Literature Review from Theory to LLM Case-Studies | [Link](https://arxiv.org/pdf/2403.03699.pdf) | N/A |
| 6 | Distributed Inference Performance Optimization for LLMs on CPUs | [Link](https://arxiv.org/pdf/2407.00029.pdf) | N/A |
| 7 | Distributed Inference and Fine-Tuning of Large Language Models Over the Internet | [Link](https://arxiv.org/pdf/2305.05920.pdf) | [GitHub](https://github.com/LLM-distributed-inference) |
| 8 | Federated Full-Parameter Tuning of Billion-Sized Language Models with Communication Cost Under 18 Kilobytes | [Link](https://arxiv.org/pdf/2312.06353.pdf) | [GitHub](https://github.com/federated-parameter-tuning) |
| 9 | ✅[Survey Article]Mobile Edge Intelligence for Large Language Models: A Contemporary Survey | [Link](https://arxiv.org/pdf/2407.18921.pdf) | N/A |
| 10 | Decentralized LLM Inference Over Edge Networks with Energy Harvesting | [Link](https://arxiv.org/pdf/2408.15907.pdf) | [GitHub](https://github.com/edge-LLM-inference) |
| 11 | Task Scheduling for Decentralized LLM Serving in Heterogeneous Networks | [Link](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2024/EECS-2024-111.pdf) | [GitHub](https://github.com/edge-LLM-inference) |
| 12 | ScaleLLM: A Resource-Frugal LLM Serving Framework by Optimizing End-to-End Efficiency | [Link](https://arxiv.org/pdf/2408.00008.pdf) | [GitHub](https://github.com/ScaleLLM-framework) |
| 13 | ✅[Survey Article]Efficient Training of Large Language Models on Distributed Infrastructures: A Survey | [Link](https://arxiv.org/pdf/2407.20018.pdf) | N/A |
| 14 | ✅[Survey Article]Large Language Model Inference Acceleration: A Comprehensive Hardware Perspective | [Link](https://arxiv.org/pdf/2410.04466.pdf) | N/A |
| 15 | FederatedScope-LLM: A Comprehensive Package for Fine-Tuning Large Language Models in Federated Learning | [Link](https://arxiv.org/pdf/2406.04845.pdf) | [GitHub](https://github.com/alibaba/FederatedScope/tree/llm) |
| 16 | FwdLLM: Efficient FedLLM Using Forward Gradient | [Link](https://arxiv.org/pdf/2308.13894.pdf) | [GitHub](https://github.com/UbiquitousLearning/FwdLLM.git) |
| 17 | On the Convergence of Zeroth-Order Federated Tuning for Large Language Models | [Link](https://arxiv.org/pdf/2409.15723.pdf) | N/A |
| 18 | ✅[Survey Article]Federated Large Language Models: Current Progress and Future Directions | [Link](https://arxiv.org/pdf/2409.15723.pdf) | N/A |
| 19 | FedRDMA: Communication-Efficient Cross-Silo Federated LLM via Chunked RDMA Transmission | [Link](https://arxiv.org/pdf/2406.09831.pdf) | N/A |
| 20 | FERRET: Federated Full-Parameter Tuning at Scale for Large Language Models | [Link](https://arxiv.org/pdf/2409.06277.pdf) | [GitHub](https://github.com/Ferret-tuning) |
| 21 | OpenFedLLM: Training Large Language Models on Decentralized Private Data via Federated Learning | [Link](https://arxiv.org/pdf/2406.10630.pdf) | [GitHub](https://github.com/rui-ye/OpenFedLLM) |
| 22 | ✅[Survey Article]A Survey of Resource-Efficient LLM and Multimodal Foundation Models | [Link](https://arxiv.org/pdf/2401.08092.pdf) | N/A |
| 23 | Emerging Safety Attack and Defense in Federated Instruction Tuning of Large Language Models | [Link](https://arxiv.org/pdf/2406.10630.pdf) | N/A |
| 24 | FedLLM-Bench: Realistic Benchmarks for Federated Learning of Large Language Models | [Link](https://arxiv.org/pdf/2406.04845.pdf) | N/A |
| 25 | Federated Instruction Tuning of LLMs with Domain Coverage Augmentation | [Link](https://arxiv.org/pdf/2409.20135.pdf) | N/A |
| 26 | FedBIoT: LLM Local Fine-Tuning in Federated Learning Without Full Model | [Link](https://arxiv.org/pdf/2403.06131.pdf) | N/A |
| 27 | FedPIT: Towards Privacy-Preserving and Few-Shot Federated Instruction Tuning | [Link](https://arxiv.org/pdf/2403.06131.pdf) | [GitHub](https://github.com/UbiquitousLearning/FedPIT) |
| 28 | A Fast, Performant, Secure Distributed Training Framework For LLM | [Link](https://ieeexplore.ieee.org/abstract/document/10446717?casa_token=RTd0WrOE65oAAAAA:znqjnhDR3BvQeg759qUTyRlURzoFIsZFoc_dBQcHbYDVT1ACsEiZEVKBYrnD0QBcO6Av7ao-jw) | N/A |
| 29 | ✅[Survey Article]Cloud-Edge Collaborative Large Model Services: Challenges and Solutions | [Link](https://arxiv.org/pdf/2310.17491.pdf) | [GitHub](https://github.com/secure-distributed-LLM) |
| 30 | FedPEAT: Convergence of Federated Learning, Parameter-Efficient Fine Tuning, and Emulator Assisted Tuning for Artificial Intelligence Foundation Models with Mobile Edge Computing| [Link](https://arxiv.org/pdf/2310.17491) | N/A |
| 31 | The Future of Large Language Model Pre-Training is Federated | [Link](https://arxiv.org/pdf/2405.10853.pdf) | [GitHub](https://github.com/CloudEdge-LLM) |
| 32 | FedPFT: Federated Proxy Fine-Tuning of Foundation Models | [Link](https://arxiv.org/pdf/2404.11536.pdf) | [GitHub](https://github.com/pzp-dzd/FedPFT) |
| 33 | Time-FFM: Towards LM-Empowered Federated Foundation Model for Time Series Forecasting | [Link](https://arxiv.org/pdf/2405.14252.pdf) | N/A |
| 34 | ✅[Survey Article]Synergizing Foundation Models and Federated Learning: A Survey | [Link](https://arxiv.org/pdf/2406.12844.pdf) | N/A |
| 35 | Save It All: Enabling Full Parameter Tuning for Federated Large Language Models via Cycle Black Gradient Descent | [Link](https://arxiv.org/pdf/2406.11187.pdf) | [GitHub](https://github.com/L3030/FedCyBGD) |
| 36 | ✅[Survey Article]Federated Learning Driven Large Language Models for Swarm Intelligence: A Survey | [Link](https://arxiv.org/pdf/2406.09831.pdf) | N/A |
| 37 | Grounding Foundation Models Through Federated Transfer Learning: A General Framework | [Link](https://arxiv.org/pdf/2311.17431.pdf) | N/A |
| 38 | ✅[Survey Article]Federated Large Language Model: A Position Paper | [Link](https://arxiv.org/pdf/2307.08925.pdf) | N/A |
| 39 | ✅[Survey Article]A Survey on Efficient Federated Learning Methods for Foundation Model Training | [Link](https://arxiv.org/pdf/2401.04472.pdf) | N/A |
| 40 | ✅[Survey Article]Federated Foundation Models: Privacy-Preserving and Collaborative Learning for Large Models | [Link](https://arxiv.org/pdf/2305.11414.pdf) | N/A |
| 41 | ✅[Survey Article]When Foundation Model Meets Federated Learning: Motivations, Challenges, and Future Directions | [Link](https://arxiv.org/pdf/2306.15546.pdf) | N/A |
| 42 | Safely Learning with Private Data: A Federated Learning Framework for Large Language Model | [Link](https://arxiv.org/pdf/2406.14898.pdf) | [GitHub](https://github.com/TAP-LLM/SplitFedLLM) |
| 43 | Empirical Guidelines for Deploying LLMs onto Resource-Constrained Edge Devices | [Link](https://arxiv.org/pdf/2406.03777.pdf) | N/A |
| 44 | Resource Allocation for Stable LLM Training in Mobile Edge Computing | [Link](https://dl.acm.org/doi/pdf/10.1145/3641512.3686358) | N/A |
| 45 | CoLLM: A Collaborative LLM Inference Framework for Resource-Constrained Devices | [Link](https://ieeexplore.ieee.org/abstract/document/10681712?casa_token=Gc7IZiP1Q74AAAAA:QhtBKCRNN8Ua_nkSY6pmFqFRPIP_jsClSqd8r7c-J28V8k9j19ElPHKR_1E5Vqq2sA_6Cp9psg) |  [GitHub](https://github.com/zyang1580/CoLLM) |
| 46 | PAFT: A Parallel Training Paradigm for Effective LLM Fine-Tuning | [Link](https://arxiv.org/pdf/2406.17923.pdf) | N/A |
| 47 | Unity is Power: Semi-Asynchronous Collaborative Training of Large-Scale Models with Structured Pruning in Resource-Limited Clients | [Link](https://arxiv.org/pdf/2410.08457.pdf) | N/A |
| 48 | Quantized Distributed Training of Large Models with Convergence Guarantees | [Link](https://proceedings.mlr.press/v202/markov23a.html) | N/A |
| 49 | Towards Robust and Efficient Federated Low-Rank Adaptation with Heterogeneous Clients | [Link](https://arxiv.org/pdf/2410.22815.pdf) | N/A |
| 50 |✅[Survey Article]On-Device Language Models: A Comprehensive Review | [Link](https://arxiv.org/pdf/2409.00088.pdf) | N/A |
| 51 | Asynchronous Local-SGD Training for Language Modeling | [Link](https://arxiv.org/pdf/2401.09135.pdf) | [GitHub](https://github.com/google-deepmind/asyncdiloco) |
| 52 | PerLLM: Personalized Inference Scheduling with Edge-Cloud Collaboration for Diverse LLM Services | [Link](https://arxiv.org/pdf/2405.14636.pdf) | N/A |
| 53 | Efficient Parallelization Layouts for Large-Scale Distributed Model Training | [Link](https://arxiv.org/pdf/2311.05610.pdf) | [GitHub](https://github.com/JohannesHa/COLM-submission-efficient-parallelization-layouts) |
| 54 | DISTMM: Accelerating Distributed Multimodal Model Training | [Link](https://www.usenix.org/conference/nsdi24/presentation/huang) | N/A |
| 55 | Efficient Multi-Task Large Model Training via Data Heterogeneity-Aware Model Management | [Link](https://arxiv.org/pdf/2409.03365.pdf) | N/A |
| 56 | TPI-LLM: Serving 70B-Scale LLMs Efficiently on Low-Resource Edge Devices | [Link](https://arxiv.org/pdf/2410.00531.pdf) | [GitHub](https://github.com/Lizonghang/TPI-LLM) |
| 57 | Meta-Learning for Speeding Up Large Model Inference in Decentralized Environments | [Link](https://arxiv.org/pdf/2410.21340.pdf) | N/A |
| 58 | Efficiently Scale LLM Training Across a Large GPU Cluster with Alpa and Ray | [Link](https://developer.nvidia.com/blog/efficiently-scale-llm-training-across-a-large-gpu-cluster-with-alpa-and-ray/) | N/A |
| 59 | LLM-Adapters: An Adapter Family for Parameter-Efficient Fine-Tuning of Large Language Models | [Link](https://arxiv.org/pdf/2304.01933.pdf) | [GitHub](https://github.com/AGI-Edgerunners/LLM-Adapters) |
| 60 | DLoRA: Distributed Parameter-Efficient Fine-Tuning Solution for Large Language Model | [Link](https://arxiv.org/pdf/2404.05182.pdf) | N/A |
| 61 | FedPT: Federated Proxy-Tuning of Large Language Models on Resource-Constrained Edge Devices | [Link](https://arxiv.org/pdf/2410.00362.pdf) | N/A |
| 62 | Communication-Efficient and Tensorized Federated Fine-Tuning of Large Language Models | [Link](https://arxiv.org/pdf/2410.13097.pdf) | N/A |
| 63 | Federated Data-Efficient Instruction Tuning for Large Language Models | [Link](https://arxiv.org/pdf/2410.10926.pdf) | N/A |
| 64 | FRAG: Toward Federated Vector Database Management for Collaborative and Secure Retrieval-Augmented Generation | [Link](https://arxiv.org/pdf/2410.13272.pdf) | N/A |
| 65 | MIRA: A Method of Federated Multi-Task Learning for Large Language Models | [Link](https://arxiv.org/pdf/2410.15524.pdf) | N/A |
| 66 | FDLoRA: Personalized Federated Learning of Large Language Model via Dual LoRA Tuning | [Link](https://arxiv.org/pdf/2406.07925.pdf) | N/A |
| 67 | Why Gradient Subspace? Identifying and Mitigating LoRA's Bottlenecks in Federated Fine-Tuning of Large Language Models | [Link](https://arxiv.org/pdf/2410.23111.pdf) | N/A |
| 68 | Research on Key Technologies for Cross-Cloud Federated Training of Large Language Models | [Link](https://arxiv.org/pdf/2410.19130.pdf) | N/A |
| 69 | Pluto and Charon: A Time and Memory Efficient Collaborative Edge AI Framework for Personal LLMs Fine-tuning | [Link](https://dl.acm.org/doi/abs/10.1145/3673038.3673043) | N/A |
| 70 | FusionLLM: A Decentralized LLM Training System on Geo-Distributed GPUs with Adaptive Compression | [Link](https://arxiv.org/pdf/2410.12707.pdf) | N/A |
| 71 | HybridFlow: A Flexible and Efficient RLHF Framework | [Link](https://arxiv.org/pdf/2409.19256.pdf) | [GitHub](https://github.com/volcengine/verl) |
| 72 | EdgeQAT: Entropy and Distribution Guided Quantization-Aware Training for the Acceleration of Lightweight LLMs on the Edge | [Link](https://arxiv.org/pdf/2402.10787.pdf) | [GitHub](https://github.com/shawnricecake/edge-qatl) |
| 73 | PrivateLoRA for Efficient Privacy-Preserving LLM | [Link](https://arxiv.org/pdf/2311.14030.pdf) | N/A |
| 74 | Distributed Foundation Models for Multi-Modal Learning in 6G Wireless Networks | [Link]([https://arxiv.org/pdf/2311.14030.pdf](https://ieeexplore.ieee.org/abstract/document/10558825?casa_token=0FbVv45FLesAAAAA:UitH2UT6mYCEkAjsoxboqSKVPtyxM-PvjYjxWuMgXba8deySpEVTD61yLNnVYxOvItVb_8S6OA)) | N/A |
| 75 | Confidant: Customizing Transformer-Based LLMs via Collaborative Edge Training | [Link](https://arxiv.org/pdf/2311.13381.pdf) | N/A |
| 76 | EdgeLLM: A Highly Efficient CPU-FPGA Heterogeneous Edge Accelerator for Large Language Models | [Link](https://arxiv.org/pdf/2407.21325.pdf) | N/A |
| 77 | HetHub: A Heterogeneous Distributed Hybrid Training System for Large-Scale Models | [Link](https://arxiv.org/pdf/2405.16256.pdf) | N/A |
| 78 | Mitigating Heterogeneity in Federated Multimodal Learning with Biomedical Vision-Language Pre-Training | [Link](https://arxiv.org/pdf/2404.03854.pdf) | N/A |
| 79 | ✅[Survey Article]A Survey: Collaborative Hardware and Software Design in the Era of Large Language Models | [Link](https://arxiv.org/pdf/2410.07265.pdf) | N/A |
| 80 | Automated Federated Pipeline for Parameter-Efficient Fine-Tuning of Large Language Models | [Link](https://arxiv.org/pdf/2404.06448.pdf) | N/A |
| 81 | FATE-LLM: An Industrial Grade Federated Learning Framework for Large Language Models | [Link](https://arxiv.org/pdf/2310.10049.pdf) | [GitHub](https://github.com/FederatedAI/FATE-LLM) |
| 82 | Federated Fine-Tuning of LLMs on the Very Edge: The Good, the Bad, the Ugly | [Link](https://dl.acm.org/doi/pdf/10.1145/3650203.3663331) | N/A |
| 83 | ✅[Survey Article]LLM-Based Edge Intelligence: A Comprehensive Survey on Architectures, Applications, Security and Trustworthiness | [Link](https://ieeexplore.ieee.org/abstract/document/10669603) | N/A |
| 84 | ServerlessLLM: Low-Latency Serverless Inference for Large Language Models | [Link](https://www.usenix.org/system/files/osdi24-fu.pdf) | [GitHub](https://github.com/ServerlessLLM/ServerlessLLM) |
| 85 | Immediate Communication for Distributed AI Tasks | [Link](https://mcanini.github.io/papers/distfuse.hotinfra24.pdf) | N/A |
| 86 | Harnessing Federated Learning for LLM Fine-Tuning: A Distributed Approach | [Link](https://www.diva-portal.org/smash/get/diva2:1898039/FULLTEXT01.pdf) | N/A |
| 87 | Lightweight Unsupervised Federated Learning with Pretrained Vision Language Model | [Link](https://arxiv.org/pdf/2404.11046.pdf) | N/A |
| 88 | Fair Federated Learning with Biased Vision-Language Models | [Link](https://aclanthology.org/2024.findings-acl.595.pdf) | [GitHub](https://github.com/huiminzeng/FF-DVP) |
| 89 | Communication-Efficient LLM Training for Federated Learning | [Link](http://reports-archive.adm.cs.cmu.edu/anon/anon/usr/ftp/usr0/ftp/2024/CMU-CS-24-123.pdf) | N/A |
| 90 | DisLLM: Distributed LLMs for Privacy Assurance in Resource-Constrained Environments | [Link](https://ieeexplore.ieee.org/abstract/document/10735498?casa_token=n472Sa5EJkkAAAAA:wpeHN1IIegHtFLYdBCxyNSHEIaCGNZqDJMUFG4BfkZRch2F8YuPFxMGM2F8TLevmNs6o5qyAqg) | N/A |
| 91 | Distributed Fine-tuning of Language Models on Private Data | [Link](https://openreview.net/pdf?id=HkgNdt26Z) | N/A |
| 92 | SplitLoRA: A Split Parameter-Efficient Fine-Tuning Framework for Large Language Models | [Link](https://arxiv.org/pdf/2407.00952.pdf) | [GitHub](https://github.com/FDU-INC/Split_LoRA) |
| 93 | CG-FedLLM: How to Compress Gradients in Federated Fine-Tuning for Large Language Models | [Link](https://arxiv.org/pdf/2405.13746.pdf) | N/A |
| 94 | Improving LoRA in Privacy-Preserving Federated Learning | [Link](https://arxiv.org/pdf/2403.12313.pdf) | N/A |
| 95 | Federated Fine-tuning of Large Language Models under Heterogeneous Tasks and Client Resources | [Link](https://arxiv.org/pdf/2402.11505) | N/A |
| 96 | Efficient Adapting for Vision-language Foundation Model in Edge Computing Based on Personalized and Multi-Granularity Federated Learning | [Link](https://ieeexplore.ieee.org/abstract/document/10620835?casa_token=iRRMWnAap1kAAAAA:aRFjkiJRq2WLSugL06aFSa2hY5cuWxYwiQt8plsxdQF9nwylUqJp2V1HryJhRADE4xKMEq1lpg) | N/A |
| 97 | FLoRA: Federated Fine-Tuning Large Language Models with Heterogeneous Low-Rank Adaptations | [Link](https://arxiv.org/pdf/2409.05976.pdf) | [GitHub](https://github.com/ATP-1010/FederatedLLM) |
| 98 | MLLM-FL: Multimodal Large Language Model Assisted Federated Learning on Heterogeneous and Long-Tailed Data | [Link](https://arxiv.org/pdf/2409.06067.pdf) | N/A |
| 99 | Distributed Foundation Models for Multi-Modal Learning in 6G Wireless Networks | [Link](https://ieeexplore.ieee.org/abstract/document/10558825?casa_token=6BBCsC_TMjoAAAAA:3IfhSIY-At9IP0L67UvkcfXKx6wSLjCJnaGQZNLAPpGw8KVZG6G3On0IK3ulnSKXQVrEGhpXIQ) | N/A |
| 100 | FLoRA: Enhancing Vision-Language Models with Parameter-Efficient Federated Learning | [Link](https://arxiv.org/pdf/2404.15182.pdf) | [GitHub](https://github.com/dphuongn/FLoRA) |
---

# **II. VLMs** <a name="ii-vlms-surveys"></a>

| Paper Title | Url | Code |
|-------------|------------|-------------|
| Learning Transferable Visual Models From Natural Language Supervision | [Link](https://proceedings.mlr.press/v139/radford21a/radford21a.pdf) | [GitHub](https://github.com/OpenAI/CLIP) |
| BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation | [Link](https://proceedings.mlr.press/v162/li22n/li22n.pdf) | [GitHub](https://github.com/salesforce/BLIP) |
| Flamingo: a Visual Language Model for Few-Shot Learning | [Link](https://proceedings.neurips.cc/paper_files/paper/2022/file/960a172bc7fbf0177ccccbb411a7d800-Paper-Conference.pdf) | N/A |
| Visual Instruction Tuning | [Link](https://arxiv.org/pdf/2304.08485) | [GitHub](https://llava-vl.github.io/) |
| MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models | [Link](https://arxiv.org/pdf/2304.10592) | [GitHub](https://minigpt-4.github.io/) |
| FLoRA: Enhancing Vision-Language Models with Parameter-Efficient Federated Learning | [Link](https://arxiv.org/pdf/2404.15182.pdf) | [GitHub](https://github.com/dphuongn/FLoRA) |
| CLIP-Guided Federated Learning on Heterogeneity and Long-Tailed Data | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29416) | [GitHub](https://github.com/shijiangming1/CLIP2FL) |
| TriplePlay: Enhancing Federated Learning with CLIP for Non-IID Data and Resource Efficiency | [Link](https://arxiv.org/pdf/2409.05347) | N/A |
| FedCLIP: Fast Generalization and Personalization for CLIP in Federated Learning | [Link](https://arxiv.org/pdf/2302.13485) | [GitHub](https://github.com/microsoft/PersonalizedFL) |
| pFedPrompt: Learning Personalized Prompt for Vision-Language Models in Federated Learning | [Link](https://dl.acm.org/doi/pdf/10.1145/3543507.3583518) | N/A |
| FedDAT: An Approach for Foundation Model Finetuning in Multi-Modal Heterogeneous Federated Learning | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/29007) | N/A |
| Federated Instruction Tuning of LLMs with Domain Coverage Augmentation | [Link](https://arxiv.org/pdf/2409.20135.pdf) | N/A |
---

# **III. SLMs** <a name="iii-slms-surveys"></a>

| Model Name | Parameters | URL |
|------------|------------|------------|
| **GPT-2 Small** | 124M | [link](https://huggingface.co/openai-community/gpt2) |
| **DistilGPT-2** | 82M | [link](https://huggingface.co/distilbert/distilgpt2) |
| **GPT-Neo 125M** | 125M | [link](https://huggingface.co/EleutherAI/gpt-neo-125m) |
| **LLaMA-2 7B** | 7B | [link](https://huggingface.co/meta-llama/Llama-2-7b-hf) |
| **ALBERT-Base** | 11M | [link](https://huggingface.co/albert/albert-base-v2) |
| **inyBERT** | 14.5M | [link](https://huggingface.co/huawei-noah/TinyBERT_General_4L_312D) |
| **DistilBERT** | 66M | [link](https://huggingface.co/distilbert/distilbert-base-uncased) |
| **MobileBert** | 25.3M | [link](https://huggingface.co/docs/transformers/en/model_doc/mobilebert) |
| **T5 Small** | 60M | [link](https://huggingface.co/google-t5/t5-small) |
| **Phi-2** | 2.7B | [link](https://www.microsoft.com/en-us/research/blog/phi-2-the-surprising-power-of-small-language-models/) |
| **Gemini Nano** | 1.8B | [link](https://deepmind.google/technologies/gemini/nano/?utm_source=chatgpt.com) |
| **Claude Instant** | <=1B | [link](https://aibusiness.com/nlp/anthropic-s-claude-instant-a-smaller-faster-and-cheaper-language-model) |
| **ByT5 Small** | 300M | [link](https://huggingface.co/google/byt5-small) |
| **Flan-T5 Small** | 80M | [link](https://huggingface.co/google/flan-t5-small) |
| **BLOOMZ 560M** | 560M | [link](https://huggingface.co/bigscience/bloomz-560m) |
| **OPT 350M** | 350M | [link](https://huggingface.co/facebook/opt-350m) |
| **Galactica 125M** |125M | [link](https://huggingface.co/meta/galactica-125m) |
| **Pythia 160M** | 160M | [link](https://huggingface.co/EleutherAI/pythia-160m) |
| **Cerebras-GPT 256M** | 256M | [link](https://huggingface.co/cerebras/Cerebras-GPT-256M) |
| **TinyLlama 1.1B** | 1.1B | [link](https://huggingface.co/meta/tiny-llama-1.1b) |
| **MiniCPM-1.2B** | 1.2B | [link](https://huggingface.co/openbmb/MiniCPM-V-2_6) |
| **Gemma (2B)** | 2B | [link](https://huggingface.co/google/gemma-2b) |
| **Reformer** | 110M | [link](https://huggingface.co/docs/transformers/en/model_doc/reformer) |
---

## Citation

```bibtex
@article{minaee2024largeLLM,
  title={Large language models: A survey},
  author={Minaee, Shervin and Mikolov, Tomas and Nikzad, Narjes and Chenaghlu, Meysam and Socher, Richard and Amatriain, Xavier and Gao, Jianfeng},
  journal={arXiv preprint arXiv:2402.06196},
  year={2024}
}
```
@article{yin2023surveyMMLM,
  title={A survey on multimodal large language models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Li, Ke and Sun, Xing and Xu, Tong and Chen, Enhong},
  journal={arXiv preprint arXiv:2306.13549},
  year={2023}
}

@article{shannon1951prediction,
  title={Prediction and entropy of printed English},
  author={Shannon, Claude E},
  journal={Bell system technical journal},
  volume={30},
  number={1},
  pages={50--64},
  year={1951},
  publisher={Wiley Online Library}
}


@article{saadati2025pmixfed,
  title={pMixFed: Efficient Personalized Federated Learning through Adaptive Layer-Wise Mixup},
  author={Saadati, Yasaman and Rostami, Mohammad and Amini, M Hadi},
  journal={arXiv preprint arXiv:2501.11002},
  year={2025}
}


@book{HLLM2jelinek1998statistical,
  title={Statistical methods for speech recognition},
  author={Jelinek, Frederick},
  year={1998},
  publisher={MIT press}
}
@article{HLLM3chu2024history,
  title={History, Development, and Principles of Large Language Models-An Introductory Survey},
  author={Chu, Zhibo and Ni, Shiwen and Wang, Zichong and Feng, Xi and Li, Chengming and Hu, Xiping and Xu, Ruifeng and Yang, Min and Zhang, Wenbin},
  journal={arXiv preprint arXiv:2402.06853},
  year={2024}
}
@book{HLLM4manning1999foundations,
  title={Foundations of statistical natural language processing},
  author={Manning, Christopher and Schutze, Hinrich},
  year={1999},
  publisher={MIT press}
}
@inproceedings{HLLM5kombrink2011recurrent,
  title={Recurrent Neural Network Based Language Modeling in Meeting Recognition.},
  author={Kombrink, Stefan and Mikolov, Tomas and Karafi{\'a}t, Martin and Burget, Luk{\'a}s},
  booktitle={Interspeech},
  volume={11},
  pages={2877--2880},
  year={2011}
}

@article{HLLM6mikolov2013distributed,
  title={Distributed representations of words and phrases and their compositionality},
  author={Mikolov, Tomas and Sutskever, Ilya and Chen, Kai and Corrado, Greg S and Dean, Jeff},
  journal={Advances in neural information processing systems},
  volume={26},
  year={2013}
}

@article{HLLM7vaswani2017attention,
  title={Attention is all you need},
  author={Vaswani, Ashish and Shazeer, Noam and Parmar, Niki and Uszkoreit, Jakob and Jones, Llion and Gomez, Aidan N and Kaiser, Lukasz and Polosukhin, Illia},
  journal={Advances in Neural Information Processing Systems},
  year={2017}
}

@article{LLMH8radford2019language,
  title={Language models are unsupervised multitask learners},
  author={Radford, Alec and Wu, Jeffrey and Child, Rewon and Luan, David and Amodei, Dario and Sutskever, Ilya and others},
  journal={OpenAI blog},
  volume={1},
  number={8},
  pages={9},
  year={2019}
}



@article{LLM10mann2020language,
  title={Language models are few-shot learners},
  author={Mann, Ben and Ryder, N and Subbiah, M and Kaplan, J and Dhariwal, P and Neelakantan, A and Shyam, P and Sastry, G and Askell, A and Agarwal, S and others},
  journal={arXiv preprint arXiv:2005.14165},
  volume={1},
  year={2020}
}
@article{LLMH11achiam2023gpt,
  title={Gpt-4 technical report},
  author={Achiam, Josh and Adler, Steven and Agarwal, Sandhini and Ahmad, Lama and Akkaya, Ilge and Aleman, Florencia Leoni and Almeida, Diogo and Altenschmidt, Janko and Altman, Sam and Anadkat, Shyamal and others},
  journal={arXiv preprint arXiv:2303.08774},
  year={2023}
}

@article{LLMH12touvron2023llama,
  title={Llama: Open and efficient foundation language models},
  author={Touvron, Hugo and Lavril, Thibaut and Izacard, Gautier and Martinet, Xavier and Lachaux, Marie-Anne and Lacroix, Timoth{\'e}e and Rozi{\`e}re, Baptiste and Goyal, Naman and Hambro, Eric and Azhar, Faisal and others},
  journal={arXiv preprint arXiv:2302.13971},
  year={2023}
}
@article{LLMH13dai2024nvlm,
  title={NVLM: Open Frontier-Class Multimodal LLMs},
  author={Dai, Wenliang and Lee, Nayeon and Wang, Boxin and Yang, Zhuoling and Liu, Zihan and Barker, Jon and Rintamaki, Tuomas and Shoeybi, Mohammad and Catanzaro, Bryan and Ping, Wei},
  journal={arXiv preprint arXiv:2409.11402},
  year={2024}
}

@article{LLMSurvey1zhao2023survey,
  title={A survey of large language models},
  author={Zhao, Wayne Xin and Zhou, Kun and Li, Junyi and Tang, Tianyi and Wang, Xiaolei and Hou, Yupeng and Min, Yingqian and Zhang, Beichen and Zhang, Junjie and Dong, Zican and others},
  journal={arXiv preprint arXiv:2303.18223},
  year={2023}
}
@article{LLMSurvey2yin2023survey,
  title={A survey on multimodal large language models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Li, Ke and Sun, Xing and Xu, Tong and Chen, Enhong},
  journal={arXiv preprint arXiv:2306.13549},
  year={2023}
}
@article{LLMSurvey3hadi2023survey,
  title={A survey on large language models: Applications, challenges, limitations, and practical usage},
  author={Hadi, Muhammad Usman and Qureshi, Rizwan and Shah, Abbas and Irfan, Muhammad and Zafar, Anas and Shaikh, Muhammad Bilal and Akhtar, Naveed and Wu, Jia and Mirjalili, Seyedali and others},
  journal={Authorea Preprints},
  year={2023},
  publisher={Authorea}
}
@article{LLMSurvey4chang2024survey,
  title={A survey on evaluation of large language models},
  author={Chang, Yupeng and Wang, Xu and Wang, Jindong and Wu, Yuan and Yang, Linyi and Zhu, Kaijie and Chen, Hao and Yi, Xiaoyuan and Wang, Cunxiang and Wang, Yidong and others},
  journal={ACM Transactions on Intelligent Systems and Technology},
  volume={15},
  number={3},
  pages={1--45},
  year={2024},
  publisher={ACM New York, NY}
}


@article{LLMSurvey6zhao2024explainability,
  title={Explainability for large language models: A survey},
  author={Zhao, Haiyan and Chen, Hanjie and Yang, Fan and Liu, Ninghao and Deng, Huiqi and Cai, Hengyi and Wang, Shuaiqiang and Yin, Dawei and Du, Mengnan},
  journal={ACM Transactions on Intelligent Systems and Technology},
  volume={15},
  number={2},
  pages={1--38},
  year={2024},
  publisher={ACM New York, NY}
}
@inproceedings{LLMSurvey12cui2024survey,
  title={A survey on multimodal large language models for autonomous driving},
  author={Cui, Can and Ma, Yunsheng and Cao, Xu and Ye, Wenqian and Zhou, Yang and Liang, Kaizhao and Chen, Jintai and Lu, Juanwu and Yang, Zichong and Liao, Kuei-Da and others},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={958--979},
  year={2024}
}
@article{LLMSurvey7zhu2023large,
  title={Large language models for information retrieval: A survey},
  author={Zhu, Yutao and Yuan, Huaying and Wang, Shuting and Liu, Jiongnan and Liu, Wenhan and Deng, Chenlong and Chen, Haonan and Dou, Zhicheng and Wen, Ji-Rong},
  journal={arXiv preprint arXiv:2308.07107},
  year={2023}
}
@article{LLMSurvey8wu2024survey,
  title={A survey on large language models for recommendation},
  author={Wu, Likang and Zheng, Zhi and Qiu, Zhaopeng and Wang, Hao and Gu, Hongchao and Shen, Tingjia and Qin, Chuan and Zhu, Chen and Zhu, Hengshu and Liu, Qi and others},
  journal={World Wide Web},
  volume={27},
  number={5},
  pages={60},
  year={2024},
  publisher={Springer}
}

@inproceedings{LLMSurvey9ren2024survey,
  title={A survey of large language models for graphs},
  author={Ren, Xubin and Tang, Jiabin and Yin, Dawei and Chawla, Nitesh and Huang, Chao},
  booktitle={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={6616--6626},
  year={2024}
}
@article{LLMSurvey10wang2024large,
  title={Large language models for education: A survey and outlook},
  author={Wang, Shen and Xu, Tianlong and Li, Hang and Zhang, Chaoli and Liang, Joleen and Tang, Jiliang and Yu, Philip S and Wen, Qingsong},
  journal={arXiv preprint arXiv:2403.18105},
  year={2024}
}
@article{LLMSurvey11he2023survey,
  title={A survey of large language models for healthcare: from data, technology, and applications to accountability and ethics},
  author={He, Kai and Mao, Rui and Lin, Qika and Ruan, Yucheng and Lan, Xiang and Feng, Mengling and Cambria, Erik},
  journal={arXiv preprint arXiv:2310.05694},
  year={2023}
}

@article{SurveyLLM15das2024security,
  title={Security and privacy challenges of large language models: A survey},
  author={Das, Badhan Chandra and Amini, M Hadi and Wu, Yanzhao},
  journal={ACM Computing Surveys},
  year={2025}
}
@article{SurveyLLM14yao2024survey,
  title={A survey on large language model (LLM) security and privacy: The good, the bad, and the ugly},
  author={Yao, Yifan and Duan, Jinhao and Xu, Kaidi and Cai, Yuanfang and Sun, Zhibo and Zhang, Yue},
  journal={High-Confidence Computing},
  pages={100211},
  year={2024},
  publisher={Elsevier}
}


@misc{MLLM1lmsys_vicuna_2023,
  author = {{The Vicuna Team}},
  title = {Vicuna: An Open-Source Chatbot Impressing {GPT}-4 with 90 percent {C}hat{GPT} Quality},
  year = {2023},
  month = {March 30},
  url = {https://lmsys.org/blog/2023-03-30-vicuna/},
  note = {Accessed: 2024-10-15}
}

@inproceedings{1zeng2023distributedLLM,
  title={Distributed training of large language models},
  author={Zeng, Fanlong and Gan, Wensheng and Wang, Yongheng and Philip, S Yu},
  booktitle={2023 IEEE 29th International Conference on Parallel and Distributed Systems (ICPADS)},
  pages={840--847},
  year={2023},
  organization={IEEE}
}

@article{2wu2023fastLLM,
  title={Fast distributed inference serving for large language models},
  author={Wu, Bingyang and Zhong, Yinmin and Zhang, Zili and Huang, Gang and Liu, Xuanzhe and Jin, Xin},
  journal={arXiv preprint arXiv:2305.05920},
  year={2023}
}

@inproceedings{3li2024distflashattnLLM,
  title={DISTFLASHATTN: Distributed Memory-efficient Attention for Long-context LLMs Training},
  author={Li, Dacheng and Shao, Rulin and Xie, Anze and Xing, Eric P and Ma, Xuezhe and Stoica, Ion and Gonzalez, Joseph E and Zhang, Hao},
  booktitle={First Conference on Language Modeling},
  year={2024}
}

@article{4nabli2024accoLLM,
  title={ACCO: Accumulate while you Communicate, Hiding Communications in Distributed LLM Training},
  author={Nabli, Adel and Fournier, Louis and Erbacher, Pierre and Serrano, Louis and Belilovsky, Eugene and Oyallon, Edouard},
  journal={arXiv preprint arXiv:2406.02613},
  year={2024}
}

@article{5brakel2024modelLLM,
  title={Model Parallelism on Distributed Infrastructure: A Literature Review from Theory to LLM Case-Studies},
  author={Brakel, Felix and Odyurt, Uraz and Varbanescu, Ana-Lucia},
  journal={arXiv preprint arXiv:2403.03699},
  year={2024}
}

@article{6he2024distributedLLM,
  title={Distributed Inference Performance Optimization for LLMs on CPUs},
  author={He, Pujiang and Zhou, Shan and Li, Changqing and Huang, Wenhuan and Yu, Weifei and Wang, Duyi and Meng, Chen and Gui, Sheng},
  journal={arXiv preprint arXiv:2407.00029},
  year={2024}
}

@article{7borzunov2024distributedLLM,
  title={Distributed inference and fine-tuning of large language models over the internet},
  author={Borzunov, Alexander and Ryabinin, Max and Chumachenko, Artem and Baranchuk, Dmitry and Dettmers, Tim and Belkada, Younes and Samygin, Pavel and Raffel, Colin A},
  journal={Advances in Neural Information Processing Systems},
  volume={36},
  year={2024}
}


@article{8qin2023federatedLLM,
  title={Federated full-parameter tuning of billion-sized language models with communication cost under 18 kilobytes},
  author={Qin, Zhen and Chen, Daoyuan and Qian, Bingchen and Ding, Bolin and Li, Yaliang and Deng, Shuiguang},
  journal={arXiv preprint arXiv:2312.06353},
  year={2023}
}

@article{9qu2024mobileLLM, 
  title={Mobile edge intelligence for large language models: A contemporary survey},
  author={Qu, Guanqiao and Chen, Qiyuan and Wei, Wei and Lin, Zheng and Chen, Xianhao and Huang, Kaibin},
  journal={arXiv preprint arXiv:2407.18921},
  year={2024}
}

@article{10khoshsirat2024decentralizedLLM,
  title={Decentralized LLM Inference over Edge Networks with Energy Harvesting},
  author={Khoshsirat, Aria and Perin, Giovanni and Rossi, Michele},
  journal={arXiv preprint arXiv:2408.15907},
  year={2024}
}

@article{11ren2024taskLLM,
  title={Task Scheduling for Decentralized LLM Serving in Heterogeneous Networks},
  author={Ren, Elden},
  year={2024}
}

@article{12yao2024scalellmLLM,
  title={ScaleLLM: A Resource-Frugal LLM Serving Framework by Optimizing End-to-End Efficiency},
  author={Yao, Yuhang and Jin, Han and Shah, Alay Dilipbhai and Han, Shanshan and Hu, Zijian and Ran, Yide and Stripelis, Dimitris and Xu, Zhaozhuo and Avestimehr, Salman and He, Chaoyang},
  journal={arXiv preprint arXiv:2408.00008},
  year={2024}
}

@article{13duan2024efficientLLM,
  title={Efficient Training of Large Language Models on Distributed Infrastructures: A Survey},
  author={Duan, Jiangfei and Zhang, Shuo and Wang, Zerui and Jiang, Lijuan and Qu, Wenwen and Hu, Qinghao and Wang, Guoteng and Weng, Qizhen and Yan, Hang and Zhang, Xingcheng and others},
  journal={arXiv preprint arXiv:2407.20018},
  year={2024}
}

@article{14li2024largeHardware,
  title={Large Language Model Inference Acceleration: A Comprehensive Hardware Perspective},
  author={Li, Jinhao and Xu, Jiaming and Huang, Shan and Chen, Yonghua and Li, Wen and Liu, Jun and Lian, Yaoxiu and Pan, Jiayi and Ding, Li and Zhou, Hao and others},
  journal={arXiv preprint arXiv:2410.04466},
  year={2024}
}

@inproceedings{15kuang2024federatedscopeLLM,
  title={Federatedscope-llm: A comprehensive package for fine-tuning large language models in federated learning},
  author={Kuang, Weirui and Qian, Bingchen and Li, Zitao and Chen, Daoyuan and Gao, Dawei and Pan, Xuchen and Xie, Yuexiang and Li, Yaliang and Ding, Bolin and Zhou, Jingren},
  booktitle={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={5260--5271},
  year={2024}
}

@article{16xu2023fwdllmLLM,
  title={FwdLLM: Efficient FedLLM using Forward Gradient},
  author={Xu, Mengwei and Cai, Dongqi and Wu, Yaozong and Li, Xiang and Wang, Shangguang},
  journal={arXiv preprint arXiv:2308.13894},
  year={2023}
}

@inproceedings{17ling2024convergenceLLM,
  title={On the convergence of zeroth-order federated tuning for large language models},
  author={Ling, Zhenqing and Chen, Daoyuan and Yao, Liuyi and Li, Yaliang and Shen, Ying},
  booktitle={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={1827--1838},
  year={2024}
}



@article{18yao2024federatedLLM,
  title={Federated Large Language Models: Current Progress and Future Directions},
  author={Yao, Yuhang and Zhang, Jianyi and Wu, Junda and Huang, Chengkai and Xia, Yu and Yu, Tong and Zhang, Ruiyi and Kim, Sungchul and Rossi, Ryan and Li, Ang and  Yao, Lina Yao and McAuley, Julian and Chen, Yiran and  Joe-Wong, Carlee},
  journal={arXiv preprint arXiv:2409.15723},
  year={2024}
}




@inproceedings{19zhang2024fedrdmaLLM,
  title={FedRDMA: Communication-Efficient Cross-Silo Federated LLM via Chunked RDMA Transmission},
  author={Zhang, Zeling and Cai, Dongqi and Zhang, Yiran and Xu, Mengwei and Wang, Shangguang and Zhou, Ao},
  booktitle={Proceedings of the 4th Workshop on Machine Learning and Systems},
  pages={126--133},
  year={2024}
}

@article{20shu2024ferretLLM,
  title={Ferret: Federated Full-Parameter Tuning at Scale for Large Language Models},
  author={Shu, Yao and Hu, Wenyang and Ng, See-Kiong and Low, Bryan Kian Hsiang and Yu, Fei Richard},
  journal={arXiv preprint arXiv:2409.06277},
  year={2024}
}

@inproceedings{21ye2024openfedllmLLM,
  title={OpenFedLLM: Training large language models on decentralized private data via federated learning},
  author={Ye, Rui and Wang, Wenhao and Chai, Jingyi and Li, Dihan and Li, Zexi and Xu, Yinda and Du, Yaxin and Wang, Yanfeng and Chen, Siheng},
  booktitle={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={6137--6147},
  year={2024}
}




@article{22xu2024surveyLLM,
  title={A survey of resource-efficient LLM and multimodal foundation models},
  author={Xu Mengwei and Li Xiang and Wang Shangguang},
  journal={arXiv preprint arXiv:2401.08092},
  year={2024}
}

@article{23ye2024safetyLLM,
  title={Emerging Safety Attack and Defense in Federated Instruction Tuning of Large Language Models},
  author={Ye Rui and Wang Wenhao and Chai Jingyi and Wang Yanfeng and Chen Siheng},
  journal={arXiv preprint arXiv:2406.10630},
  year={2024}
}

@article{24ye2024fedllmLLM,
  title={FedLLM-Bench: Realistic Benchmarks for Federated Learning of Large Language Models},
  author={Ye Rui and Chai Jingyi and Li Dihan and Wang Wenhao and Du Yaxin and Wang Yanfeng and Chen Siheng},
  journal={arXiv preprint arXiv:2406.04845},
  year={2024}
}

@article{25wang2024federatedLLM,
  title={Federated Instruction Tuning of LLMs with Domain Coverage Augmentation},
  author={Wang Zezhou and Ye Rui and Li Dihan and Wang Wenhao and Chen Siheng},
  journal={arXiv preprint arXiv:2409.20135},
  year={2024}
}

@inproceedings{26wu2024fedbiotLLM,
  title={Fedbiot: LLM local fine-tuning in federated learning without full model},
  author={Wu Feijie and Gao Xiang and Yu Youjia and Ren Xuefeng and Wu Qianqian},
  booktitle={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  year={2024}
}

@article{27zhang2024fedpitLLM,
  title={Fedpit: Towards privacy-preserving and few-shot federated instruction tuning},
  author={Zhang Zhuo and Zhang Xin and Wang Zezhou and Liu Zelin and Song Minghai},
  journal={arXiv preprint arXiv:2403.06131},
  year={2024}
}

@inproceedings{28huang2024frameworkLLM,
  title={A Fast, Performant, Secure Distributed Training Framework For LLM},
  author={Huang Wei and Zhang Yi and Liu Jianjun and Chen Zhiyuan and Li Jie},
  booktitle={ICASSP 2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  year={2024}
}

@article{29pan2024cloudLLM,
  title={Cloud-Edge Collaborative Large Model Services: Challenges and Solutions},
  author={Pan Yanghe and Chen Jun and Du Linjun and Zhang Xiaobo and Zhao Hongyan},
  journal={IEEE Network},
  year={2024}
}

@article{30chua2023fedpeatLLM,
  title={FedPEAT: Convergence of Federated Learning, Parameter-Efficient Fine Tuning, and Emulator Assisted Tuning for AI Foundation Models with Mobile Edge Computing},
  author={Chua Terence Jie and Liang Chen and Yuan Xuesong and Zhao Xudong and Feng Bo},
  journal={arXiv preprint arXiv:2310.17491},
  year={2023}
}




@article{han2015deep,
  title={Deep compression: Compressing deep neural networks with pruning, trained quantization and Huffman coding},
  author={Han, Song and Mao, Huizi and Dally, William J},
  journal={arXiv preprint arXiv:1510.00149},
  year={2015}
}

@inproceedings{sanh2019distilbert,
  title={DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter},
  author={Sanh, Victor and Debut, Lysandre and Chaumond, Julien and Wolf, Thomas},
  booktitle={Proceedings of the 5th Workshop on Energy Efficient Machine Learning and Cognitive Computing},
  pages={1--6},
  year={2019}
}

@inproceedings{bai2020binarybert,
  title={BinaryBERT: Pushing the limit of BERT quantization},
  author={Bai, Yanyang and Zhang, Yichun and Yang, Jiawei and Liu, Junfeng and Tang, Jing and Wu, Jie and Gao, Jianfeng and Wang, Jian},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  pages={4334--4343},
  year={2020}
}

@inproceedings{jiao2020tinybert,
  title={TinyBERT: Distilling BERT for natural language understanding},
  author={Jiao, Xiaoqi and Yin, Yichun and Shang, Lifeng and Jiang, Xin and Chen, Xiao and Li, Linlin and Wang, Fang and Liu, Qun},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  pages={4163--4174},
  year={2020}
}

@article{shen2020q,
  title={Q-BERT: Hessian based ultra low precision quantization of BERT},
  author={Shen, Sheng and Dong, Zhen and Ye, Qing and Ma, Linjie and Wang, Pengcheng and Li, Zhewei and Zhu, Song Han and Dou, Dejing and Wang, Renqiang},
  journal={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={34},
  number={05},
  pages={8815--8821},
  year={2020}
}


@inproceedings{gafni2022make,
  title={Make-A-Scene: Scene-Based Text-to-Image Generation with Human Priors},
  author={Gafni, Oran and Polyak, Adam and Ashual, Oron and Shechtman, Eli and Park, Taesung},
  booktitle={European Conference on Computer Vision (ECCV)},
  year={2022},
  pages={39--55}
}

@misc{openai2023gpt4vsystemcard,
  author = {{OpenAI}},
  title = {GPT-4V System Card},
  year = {2023},
  url = {https://openai.com/index/gpt-4v-system-card/},
  note = {Accessed: 2024-10-29}
}

@article{alayrac2022flamingo,
  title={Flamingo: a Visual Language Model for Few-Shot Learning},
  author={Alayrac, Jean-Baptiste and Recasens, Adria and Schneider, Rapha\"el and others},
  journal={arXiv preprint arXiv:2204.14198},
  year={2022}
}

@article{li2023blip2,
  title={BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models},
  author={Li, Junnan and Li, Dongxu and Savarese, Silvio and Fei-Fei, Li},
  journal={arXiv preprint arXiv:2301.12597},
  year={2023}
}

@article{liu2023llava,
  title={Visual Instruction Tuning},
  author={Liu, Haotian and  others},
  journal={Advances in Neural Information Processing Systems (NeurIPS) },
  volume={36},
  year={2023}
}


@inproceedings{ganesh2021compressing,
  title={Compressing large-scale transformer-based models: A case study on BERT},
  author={Ganesh, Pradeep and Ramatlongo, Dieketseng and Pourdamghani, Nadir and Guo, Wei and Constant, Noah and Parthasarathy, Srinivasan and Sajjad, Hassan and Riccardi, Giuseppe and Faruqui, Manaal},
  booktitle={Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  pages={5290--5306},
  year={2021}
}


@article{schulman2017proximal,
  title={Proximal policy optimization algorithms},
  author={Schulman, John and Wolski, Filip and Dhariwal, Prafulla and Radford, Alec and Klimov, Oleg},
  journal={arXiv preprint arXiv:1707.06347},
  year={2017}
}



@article{31sani2024futureLLM,
  title={The Future of Large Language Model Pre-training is Federated},
  author={Sani, Lorenzo and Iacob, Alex and Cao, Zeyu and Marino, Bill and Gao, Yan and Paulik, Tomas and Zhao, Wanru and Shen, William F and Aleksandrov, Preslav and Qiu, Xinchi and others},
  journal={arXiv preprint arXiv:2405.10853},
  year={2024}
}

@article{32peng2024fedpftLLM,
  title={FedPFT: Federated Proxy Fine-Tuning of Foundation Models},
  author={Peng Zhaopeng and Zhang Wei and Li Hongwei},
  journal={arXiv preprint arXiv:2404.11536},
  year={2024}
}
@article{33liu2024timeFFMLLM,
  title={Time-FFM: Towards LM-Empowered Federated Foundation Model for Time Series Forecasting},
  author={Liu Qingxiang and Zhang Jianfeng and Zhang Tao},
  journal={arXiv preprint arXiv:2405.14252},
  year={2024}
}

@article{34li2024synergizingLLM,
  title={Synergizing Foundation Models and Federated Learning: A Survey},
  author={Li Shenghui and Liu Wei and Wang Lin},
  journal={arXiv preprint arXiv:2406.12844},
  year={2024}
}

@article{35wang2024cycleblackLLM,
  title={Save It All: Enabling Full Parameter Tuning for Federated Large Language Models via Cycle Black Gradient Descent},
  author={Wang Lin and Wang Zhichao and Tang Xiaoying},
  journal={arXiv preprint arXiv:2406.11187},
  year={2024}
}

@article{36qu2024swarmLLM,
  title={Federated Learning driven Large Language Models for Swarm Intelligence: A Survey},
  author={Qu Youyang and Zhang Jinwen and Chen Qi},
  journal={arXiv preprint arXiv:2406.09831},
  year={2024}
}

@article{37kang2023groundingLLM,
  title={Grounding Foundation Models through Federated Transfer Learning: A General Framework},
  author={Kang Yan and Zhang Wei and Liu Xinyu},
  journal={arXiv preprint arXiv:2311.17431},
  year={2023}
}


@article{38chen2023federated,
  title={Federated large language model: A position paper},
  author={Chen, Chaochao and Feng, Xiaohua and Zhou, Jun and Yin, Jianwei and Zheng, Xiaolin},
  journal={arXiv preprint arXiv:2307.08925},
  year={2023}
}
@article{39woisetschlager2024survey,
  title={A survey on efficient federated learning methods for foundation model training},
  author={Woisetschl{\"a}ger, Herbert and Isenko, Alexander and Wang, Shiqiang and Mayer, Ruben and Jacobsen, Hans-Arno},
  journal={arXiv preprint arXiv:2401.04472},
  year={2024}
}

@article{40yu2023federated,
  title={Federated foundation models: Privacy-preserving and collaborative learning for large models},
  author={Yu, Sixing and Mu{\~n}oz, J Pablo and Jannesari, Ali},
  journal={arXiv preprint arXiv:2305.11414},
  year={2023}
}

@article{41zhuang2023foundation,
  title={When foundation model meets federated learning: Motivations, challenges, and future directions},
  author={Zhuang, Weiming and Chen, Chen and Lyu, Lingjuan},
  journal={arXiv preprint arXiv:2306.15546},
  year={2023}
}






@article{42zheng2024safely,
  title={Safely Learning with Private Data: A Federated Learning Framework for Large Language Model},
  author={Zheng, JiaYing and Zhang, HaiNan and Wang, LingXiang and Qiu, WangJie and Zheng, HongWei and Zheng, ZhiMing},
  journal={arXiv preprint arXiv:2406.14898},
  year={2024}
}

@article{43qin2024empirical,
  title={Empirical Guidelines for Deploying LLMs onto Resource-constrained Edge Devices},
  author={Qin, Ruiyang and Liu, Dancheng and Yan, Zheyu and Tan, Zhaoxuan and Pan, Zixuan and Jia, Zhenge and Jiang, Meng and Abbasi, Ahmed and Xiong, Jinjun and Shi, Yiyu},
  journal={arXiv preprint arXiv:2406.03777},
  year={2024}
}


@inproceedings{44liu2024resource,
  title={Resource Allocation for Stable LLM Training in Mobile Edge Computing},
  author={Liu, Chang and Zhao, Jun},
  booktitle={Proceedings of the Twenty-fifth International Symposium on Theory, Algorithmic Foundations, and Protocol Design for Mobile Networks and Mobile Computing},
  pages={81--90},
  year={2024}
}



@inproceedings{45li2024collm,
  title={CoLLM: A Collaborative LLM Inference Framework for Resource-Constrained Devices},
  author={Li, Jinrong and Han, Biao and Li, Sudan and Wang, Xiaoyan and Li, Jie},
  booktitle={2024 IEEE/CIC International Conference on Communications in China (ICCC)},
  pages={185--190},
  year={2024},
  organization={IEEE}
}


@article{46pentyala2024paft,
  title={PAFT: A Parallel Training Paradigm for Effective LLM Fine-Tuning},
  author={Pentyala, Shiva Kumar and Wang, Zhichao and Bi, Bin and Ramnath, Kiran and Mao, Xiang-Bo and Radhakrishnan, Regunathan and Asur, Sitaram and others},
  journal={arXiv preprint arXiv:2406.17923},
  year={2024}
}



@article{47li2024unity,
  title={Unity is Power: Semi-Asynchronous Collaborative Training of Large-Scale Models with Structured Pruning in Resource-Limited Clients},
  author={Li, Yan and Li, Mingyi and Zhang, Xiao and Xu, Guangwei and Chen, Feng and Yuan, Yuan and Zou, Yifei and Zhao, Mengying and Lu, Jianbo and Yu, Dongxiao},
  journal={arXiv preprint arXiv:2410.08457},
  year={2024}
}



@inproceedings{48markov2023quantized,
  title={Quantized distributed training of large models with convergence guarantees},
  author={Markov, Ilia and Vladu, Adrian and Guo, Qi and Alistarh, Dan},
  booktitle={International Conference on Machine Learning},
  pages={24020--24044},
  year={2023},
  organization={PMLR}
}


@article{49koo2024towards,
  title={Towards Robust and Efficient Federated Low-Rank Adaptation with Heterogeneous Clients},
  author={Koo, Jabin and Jang, Minwoo and Ok, Jungseul},
  journal={arXiv preprint arXiv:2410.22815},
  year={2024}
}

@article{50xu2024device,
  title={On-device language models: A comprehensive review},
  author={Xu, Jiajun and Li, Zhiyuan and Chen, Wei and Wang, Qun and Gao, Xin and Cai, Qi and Ling, Ziyuan},
  journal={arXiv preprint arXiv:2409.00088},
  year={2024}
}

@article{51liu2024asynchronous,
  title={Asynchronous Local-SGD Training for Language Modeling},
  author={Liu, Bo and Chhaparia, Rachita and Douillard, Arthur and Kale, Satyen and Rusu, Andrei A and Shen, Jiajun and Szlam, Arthur and Ranzato, Marc'Aurelio},
  journal={arXiv preprint arXiv:2401.09135},
  year={2024}
}

@article{52yang2024perllm,
  title={PerLLM: Personalized Inference Scheduling with Edge-Cloud Collaboration for Diverse LLM Services},
  author={Yang, Zheming and Yang, Yuanhao and Zhao, Chang and Guo, Qi and He, Wenkai and Ji, Wen},
  journal={arXiv preprint arXiv:2405.14636},
  year={2024}
}

@article{53hagemann2023efficient,
  title={Efficient Parallelization Layouts for Large-Scale Distributed Model Training},
  author={Hagemann, Johannes and Weinbach, Samuel and Dobler, Konstantin and Schall, Maximilian and de Melo, Gerard},
  journal={arXiv preprint arXiv:2311.05610},
  year={2023}
}

@inproceedings{54huang2024distmm,
  title={DISTMM: Accelerating Distributed Multimodal Model Training},
  author={Huang, Jun and Zhang, Zhen and Zheng, Shuai and Qin, Feng and Wang, Yida},
  booktitle={21st USENIX Symposium on Networked Systems Design and Implementation (NSDI 24)},
  pages={1157--1171},
  year={2024}
}


@article{55wang2024efficient,
  title={Efficient Multi-Task Large Model Training via Data Heterogeneity-aware Model Management},
  author={Wang, Yujie and Zhu, Shenhan and Fu, Fangcheng and Miao, Xupeng and Zhang, Jie and Zhu, Juan and Hong, Fan and Li, Yong and Cui, Bin},
  journal={arXiv preprint arXiv:2409.03365},
  year={2024}
}


@article{56li2024tpi,
  title={TPI-LLM: Serving 70B-scale LLMs Efficiently on Low-resource Edge Devices},
  author={Li, Zonghang and Feng, Wenjiao and Guizani, Mohsen and Yu, Hongfang},
  journal={arXiv preprint arXiv:2410.00531},
  year={2024}
}


@article{57yang2024meta,
  title={Meta-Learning for Speeding Up Large Model Inference in Decentralized Environments},
  author={Yang, Yuzhe and Du, Yipeng and Farhan, Ahmad and Angione, Claudio and Zhao, Yue and Yang, Harry and Johnston, Fielding and Buban, James and Colangelo, Patrick},
  journal={arXiv preprint arXiv:2410.21340},
  year={2024}
}



@misc{58rayLLMscaling,
  author       = {Dong, Jiao and Zheng, Hao and  Zheng, Lianmin and Nguyen, Phi},
  title        = {Efficiently Scale LLM Training Across a Large GPU Cluster with Alpa and Ray},
  howpublished = {\url{https://developer.nvidia.com/blog/efficiently-scale-llm-training-across-a-large-gpu-cluster-with-alpa-and-ray/}},
  note         = {Accessed: 2024-11-02}
}



@article{59hu2023llm,
  title={LLM-adapters: An adapter family for parameter-efficient fine-tuning of large language models},
  author={Hu, Zhiqiang and Wang, Lei and Lan, Yihuai and Xu, Wanyu and Lim, Ee-Peng and Bing, Lidong and Xu, Xing and Poria, Soujanya and Lee, Roy Ka-Wei},
  journal={arXiv preprint arXiv:2304.01933},
  year={2023}
}

@article{60gao2024dlora,
  title={DLoRA: Distributed parameter-efficient fine-tuning solution for large language model},
  author={Gao, Chao and Zhang, Sai Qian},
  journal={arXiv preprint arXiv:2404.05182},
  year={2024}
}



@article{61gao2024fedpt,
  title={FedPT: Federated Proxy-Tuning of Large Language Models on Resource-Constrained Edge Devices},
  author={Gao, Zhidong and Zhang, Yu and Zhang, Zhenxiao and Gong, Yanmin and Guo, Yuanxiong},
  journal={arXiv preprint arXiv:2410.00362},
  year={2024}
}

@article{62ghiasvand2024communication,
  title={Communication-Efficient and Tensorized Federated Fine-Tuning of Large Language Models},
  author={Ghiasvand, Sajjad and Yang, Yifan and Xue, Zhiyu and Alizadeh, Mahnoosh and Zhang, Zheng and Pedarsani, Ramtin},
  journal={arXiv preprint arXiv:2410.13097},
  year={2024}
}

@article{63qin2024federated,
  title={Federated Data-Efficient Instruction Tuning for Large Language Models},
  author={Qin, Zhen and Wu, Zhaomin and He, Bingsheng and Deng, Shuiguang},
  journal={arXiv preprint arXiv:2410.10926},
  year={2024}
}


@article{64zhao2024frag,
  title={FRAG: Toward Federated Vector Database Management for Collaborative and Secure Retrieval-Augmented Generation},
  author={Zhao, Dongfang},
  journal={arXiv preprint arXiv:2410.13272},
  year={2024}
}

@article{65elbakary2024mira,
  title={MIRA: A Method of Federated MultI-Task Learning for LaRge LAnguage Models},
  author={Elbakary, Ahmed and Issaid, Chaouki Ben and ElBatt, Tamer and Seddik, Karim and Bennis, Mehdi},
  journal={arXiv preprint arXiv:2410.15524},
  year={2024}
}


@article{66qi2024fdlora,
  title={FDLoRA: Personalized Federated Learning of Large Language Model via Dual LoRA Tuning},
  author={Qi, Jiaxing and Luan, Zhongzhi and Huang, Shaohan and Fung, Carol and Yang, Hailong and Qian, Depei},
  journal={arXiv preprint arXiv:2406.07925},
  year={2024}
}


@article{67yao2024sharingLLM,
  title={Why Gradient Subspace? Identifying and Mitigating LoRA's Bottlenecks in Federated Fine-Tuning of Large Language Models},
  author={Mahla, Navyansh and Ramakrishnan, Ganesh},
  journal={arXiv preprint arXiv:2410.23111},
  year={2024}
}

@article{68yang2024research,
  title={Research on Key Technologies for Cross-Cloud Federated Training of Large Language Models},
  author={Yang, Haowei and Sui, Mingxiu and Liu, Shaobo and Qian, Xinyue and Zhang, Zhaoyang and Liu, Bingying},
  journal={arXiv preprint arXiv:2410.19130},
  year={2024}
}

@inproceedings{69ouyang2024pluto,
  title={Pluto and Charon: A Time and Memory Efficient Collaborative Edge AI Framework for Personal LLMs Fine-tuning},
  author={Ouyang, Bei and Ye, Shengyuan and Zeng, Liekang and Qian, Tianyi and Li, Jingyi and Chen, Xu},
  booktitle={Proceedings of the 53rd International Conference on Parallel Processing},
  pages={762--771},
  year={2024}
}
@inproceedings{tekdogan2021benchmarking,
  title={Benchmarking apache spark and hadoop mapreduce on big data classification},
  author={Tekdogan, Taha and Cakmak, Ali},
  booktitle={Proceedings of the 2021 5th International Conference on Cloud and Big Data Computing},
  pages={15--20},
  year={2021}
}

@article{70tang2024fusionllm,
  title={FusionLLM: A Decentralized LLM Training System on Geo-distributed GPUs with Adaptive Compression},
  author={Tang, Zhenheng and Kang, Xueze and Yin, Yiming and Pan, Xinglin and Wang, Yuxin and He, Xin and Wang, Qiang and Zeng, Rongfei and Zhao, Kaiyong and Shi, Shaohuai and others},
  journal={arXiv preprint arXiv:2410.12707},
  year={2024}
}

@article{71sheng2024hybridflow,
  title={HybridFlow: A Flexible and Efficient RLHF Framework},
  author={Sheng, Guangming and Zhang, Chi and Ye, Zilingfeng and Wu, Xibin and Zhang, Wang and Zhang, Ru and Peng, Yanghua and Lin, Haibin and Wu, Chuan},
  journal={arXiv preprint arXiv:2409.19256},
  year={2024}
}

@article{72shen2024edgeqat,
  title={EdgeQAT: Entropy and Distribution Guided Quantization-Aware Training for the Acceleration of Lightweight LLMs on the Edge},
  author={Shen, Xuan and Kong, Zhenglun and Yang, Changdi and Han, Zhaoyang and Lu, Lei and Dong, Peiyan and Lyu, Cheng and Li, Chih-hsiang and Guo, Xuehang and Shu, Zhihao and others},
  journal={arXiv preprint arXiv:2402.10787},
  year={2024}
}

@article{73wang2023privatelora,
  title={Privatelora for efficient privacy preserving LLM},
  author={Wang, Yiming and Lin, Yu and Zeng, Xiaodong and Zhang, Guannan},
  journal={arXiv preprint arXiv:2311.14030},
  year={2023}
}

@article{74du2024distributed,
  title={Distributed Foundation Models for Multi-Modal Learning in 6G Wireless Networks},
  author={Du, Jun and Lin, Tianyi and Jiang, Chunxiao and Yang, Qianqian and Bader, C Faouzi and Han, Zhu},
  journal={IEEE Wireless Communications},
  volume={31},
  number={3},
  pages={20--30},
  year={2024},
  publisher={IEEE}
}

@article{75chen2023confidant,
  title={Confidant: Customizing Transformer-based LLMs via Collaborative Edge Training},
  author={Chen, Yuhao and Yan, Yuxuan and Yang, Qianqian and Shu, Yuanchao and He, Shibo and Chen, Jiming},
  journal={arXiv preprint arXiv:2311.13381},
  year={2023}
}

@article{76huang2024edgellm,
  title={EdgeLLM: A highly efficient cpu-fpga heterogeneous edge accelerator for large language models},
  author={Huang, Mingqiang and Shen, Ao and Li, Kai and Peng, Haoxiang and Li, Boyu and Yu, Hao},
  journal={arXiv preprint arXiv:2407.21325},
  year={2024}
}

@article{77xu2024hethub,
  title={HetHub: A Heterogeneous distributed hybrid training system for large-scale models},
  author={Xu, Si and Huang, Zixiao and Zeng, Yan and Yan, Shengen and Ning, Xuefei and Ye, Haolin and Gu, Sipei and Shui, Chunsheng and Lin, Zhezheng and Zhang, Hao and others},
  journal={arXiv preprint arXiv:2405.16256},
  year={2024}
}

@article{78shuai2024mitigating,
  title={Mitigating Heterogeneity in Federated Multimodal Learning with Biomedical Vision-Language Pre-training},
  author={Shuai, Zitao and Shen, Liyue},
  journal={arXiv preprint arXiv:2404.03854},
  year={2024}
}


@article{79guo2024survey,
  title={A Survey: Collaborative Hardware and Software Design in the Era of Large Language Models},
  author={Guo, Cong and Cheng, Feng and Du, Zhixu and Kiessling, James and Ku, Jonathan and Li, Shiyu and Li, Ziru and Ma, Mingyuan and Molom-Ochir, Tergel and Morris, Benjamin and others},
  journal={arXiv preprint arXiv:2410.07265},
  year={2024}
}


@article{80fang2024automated,
  title={Automated federated pipeline for parameter-efficient fine-tuning of large language models},
  author={Fang, Zihan and Lin, Zheng and Chen, Zhe and Chen, Xianhao and Gao, Yue and Fang, Yuguang},
  journal={arXiv preprint arXiv:2404.06448},
  year={2024}
}

@article{81fan2023fate,
  title={Fate-LLM: A industrial grade federated learning framework for large language models},
  author={Fan, Tao and Kang, Yan and Ma, Guoqiang and Chen, Weijing and Wei, Wenbin and Fan, Lixin and Yang, Qiang},
  journal={arXiv preprint arXiv:2310.10049},
  year={2023}
}

@inproceedings{82woisetschlager2024federated,
  title={Federated fine-tuning of llms on the very edge: The good, the bad, the ugly},
  author={Woisetschl{\"a}ger, Herbert and Erben, Alexander and Wang, Shiqiang and Mayer, Ruben and Jacobsen, Hans-Arno},
  booktitle={Proceedings of the Eighth Workshop on Data Management for End-to-End Machine Learning},
  pages={39--50},
  year={2024}
}
@article{83friha2024llm,
  title={LLM-based edge intelligence: A comprehensive survey on architectures, applications, security and trustworthiness},
  author={Friha, Othmane and Ferrag, Mohamed Amine and Kantarci, Burak and Cakmak, Burak and Ozgun, Arda and Ghoualmi-Zine, Nassira},
  journal={IEEE Open Journal of the Communications Society},
  year={2024},
  publisher={IEEE}
}

@inproceedings{84fu2024serverlessllm,
  title={$\{$ServerlessLLM$\}$:$\{$Low-Latency$\}$ Serverless Inference for Large Language Models},
  author={Fu, Yao and Xue, Leyang and Huang, Yeqi and Brabete, Andrei-Octavian and Ustiugov, Dmitrii and Patel, Yuvraj and Mai, Luo},
  booktitle={18th USENIX Symposium on Operating Systems Design and Implementation (OSDI 24)},
  pages={135--153},
  year={2024}
}


@article{85xinimmediate,
  title={Immediate Communication for Distributed AI Tasks},
  author={Xin, Jihao and Bae, Seongjong and Park, KyoungSoo and Canini, Marco and Hwang, Changho}
}


@misc{86shabani2024harnessing,
  title={Harnessing Federated Learning for LLM Fine-Tuning: A Distributed Approach},
  author={Shabani, Naser},
  year={2024}
}


@article{87yan2024lightweight,
  title={Lightweight Unsupervised Federated Learning with Pretrained Vision Language Model},
  author={Yan, Hao and Guo, Yuhong},
  journal={arXiv preprint arXiv:2404.11046},
  year={2024}
}


@inproceedings{88zeng2024fair,
  title={Fair federated learning with biased vision-language models},
  author={Zeng, Huimin and Yue, Zhenrui and Zhang, Yang and Shang, Lanyu and Wang, Dong},
  booktitle={Findings of the Association for Computational Linguistics ACL 2024},
  pages={10002--10017},
  year={2024}
}

@phdthesis{89raje2024communication,
  title={Communication-Efficient LLM Training for Federated Learning},
  author={Raje, Arian},
  year={2024},
  school={Ph. D. thesis, Carnegie Mellon University Pittsburgh, PA}
}


@article{110zhao2023privacy,
  title={Privacy-preserving fine-tuning of artificial intelligence (ai) foundation models with federated learning, differential privacy, offsite tuning, and parameter-efficient fine-tuning (peft)},
  author={Zhao, Jun},
  journal={Authorea Preprints},
  year={2023},
  publisher={Authorea}
}



@inproceedings{90sadeepa2024disllm,
  title={DisLLM: Distributed LLMs for Privacy Assurance in Resource-Constrained Environments},
  author={Sadeepa, Sumudith and Kavinda, Keshara and Hashika, Emmanuel and Sandeepa, Chamara and Gamage, Tharindu and Liyanage, Madhusanka},
  booktitle={2024 IEEE Conference on Communications and Network Security (CNS)},
  pages={1--9},
  year={2024},
  organization={IEEE}
}

% article{91vavekanand2024cellm,
 % title={CELLM: An Efficient Communication in Large Language Models Training for Federated Learning},
  author={Vavekanand, Raja and Sam, Kira},
  journal={arXiv preprint arXiv:2407.20557},
  year={2024}
}

@inproceedings{91popov2018distributed,
  title={Distributed fine-tuning of language models on private data},
  author={Popov, Vadim and Kudinov, Mikhail and Piontkovskaya, Irina and Vytovtov, Petr and Nevidomsky, Alex},
  booktitle={International Conference on Learning Representations},
  year={2018}
}
@article{92lin2024splitlora,
  title={Splitlora: A split parameter-efficient fine-tuning framework for large language models},
  author={Lin, Zheng and Hu, Xuanjie and Zhang, Yuxin and Chen, Zhe and Fang, Zihan and Chen, Xianhao and Li, Ang and Vepakomma, Praneeth and Gao, Yue},
  journal={arXiv preprint arXiv:2407.00952},
  year={2024}
}
@article{93wu2024cg,
  title={CG-FedLLM: How to Compress Gradients in Federated Fune-tuning for Large Language Models},
  author={Wu, Huiwen and Li, Xiaohan and Zhang, Deyi and Xu, Xiaogang and Wu, Jiafei and Zhao, Puning and Liu, Zhe},
  journal={arXiv preprint arXiv:2405.13746},
  year={2024}
}

@inproceedings{albanie2018emotion,
  title={Emotion recognition in speech using cross-modal transfer in the wild},
  author={Albanie, Samuel and Nagrani, Arsha and Vedaldi, Andrea and Zisserman, Andrew},
  booktitle={Proceedings of the 26th ACM international conference on Multimedia},
  pages={292--301},
  year={2018}
}

@article{denton2014exploiting,
  title={Exploiting linear structure within convolutional networks for efficient evaluation},
  author={Denton, Emily L and Zaremba, Wojciech and Bruna, Joan and LeCun, Yann and Fergus, Rob},
  journal={Advances in neural information processing systems},
  volume={27},
  year={2014}
}

@inproceedings{he2017channel,
  title={Channel pruning for accelerating very deep neural networks},
  author={He, Yihui and Zhang, Xiangyu and Sun, Jian},
  booktitle={Proceedings of the IEEE international conference on computer vision},
  pages={1389--1397},
  year={2017}
}
@article{molchanov2016pruning,
  title={Pruning convolutional neural networks for resource efficient inference},
  author={Molchanov, Pavlo and Tyree, Stephen and Karras, Tero and Aila, Timo and Kautz, Jan},
  journal={arXiv preprint arXiv:1611.06440},
  year={2016}
}
@article{94sun2024improving,
  title={Improving loRA in privacy-preserving federated learning},
  author={Sun, Youbang and Li, Zitao and Li, Yaliang and Ding, Bolin},
  journal={arXiv preprint arXiv:2403.12313},
  year={2024}
}

@article{95bai2024federated,
  title={Federated fine-tuning of large language models under heterogeneous language tasks and client resources},
  author={Bai, Jiamu and Chen, Daoyuan and Qian, Bingchen and Yao, Liuyi and Li, Yaliang},
  journal={arXiv e-prints},
  pages={arXiv--2402},
  year={2024}
}
@inproceedings{96gao2024efficient,
  title={Efficient Adapting for Vision-language Foundation Model in Edge Computing Based on Personalized and Multi-Granularity Federated Learning},
  author={Gao, Fei and Zhao, Yunfeng and Qiu, Chao and Wang, Xiaofei},
  booktitle={IEEE INFOCOM 2024-IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS)},
  pages={1--6},
  year={2024},
  organization={IEEE}
}



@article{SLMNguyen2024Survey,
  title={A Survey of Small Language Models},
  author={Chien Van Nguyen and Xuan Shen and Ryan Aponte and Yu Xia and others},
  journal={arXiv preprint arXiv:2410.20011},
  year={2024}
}







@article{97wang2024flora,
  title={FLoRA: Federated fine-tuning large language models with heterogeneous low-rank adaptations},
  author={Wang, Ziyao and Shen, Zheyu and He, Yexiao and Sun, Guoheng and Wang, Hongyi and Lyu, Lingjuan and Li, Ang},
  journal={arXiv preprint arXiv:2409.05976},
  year={2024}
}

@article{98li2024mllm,
  title={MLLM-FL: Multimodal Large Language Model Assisted Federated Learning on Heterogeneous and Long-tailed Data},
  author={Li, Shenghui and Ye, Fanghua and Fang, Meng and Zhao, Jiaxu and Chan, Yun-Hin and Ngai, Edith C-H and Voigt, Thiemo},
  journal={arXiv preprint arXiv:2409.06067},
  year={2024}
}



@article{99zhang2024distributed,
  title={Distributed Foundation Models for Multi-Modal Learning in 6G Wireless Networks},
  author={Zhang, Haibo and Li, Shenghui and Ye, Fanghua and Fang, Meng and Zhao, Jiaxu and Chan, Yun-Hin and Ngai, Edith C-H and Voigt, Thiemo},
  journal={IEEE Communications Magazine},
  volume={62},
  number={6},
  pages={20--26},
  year={2024},
  publisher={IEEE}
}

@article{100nguyen2024flora,
  title={FLoRA: Enhancing Vision-Language Models with Parameter-Efficient Federated Learning},
  author={Nguyen, Duy Phuong and Munoz, J Pablo and Jannesari, Ali},
  journal={arXiv preprint arXiv:2404.15182},
  year={2024}
}


@inproceedings{104sun2024towards,
  title={Towards Multi-modal Transformers in Federated Learning},
  author={Sun, Guangyu and Mendieta, Matias and Dutta, Aritra and Li, Xin and Chen, Chen},
  booktitle={European Conference on Computer Vision},
  pages={1--17},
  year={2024},
  organization={Springer}
}

@article{jin2024decoagent,
  title={DeCoAgent: Large Language Model Empowered Decentralized Autonomous Collaboration Agents Based on Smart Contracts},
  author={Jin, Anan and Ye, Yuhang and Lee, Brian and Qiao, Yuansong},
  journal={IEEE Access},
  year={2024},
  publisher={IEEE}
}

@inproceedings{106zeng2024open,
  title={Open-Vocabulary Federated Learning with Multimodal Prototyping},
  author={Zeng, Huimin and Yue, Zhenrui and Wang, Dong},
  booktitle={Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies},
  pages={1--12},
  year={2024}
}







@misc{gibiansky2017bringing,
  title={Bringing HPC techniques to deep learning},
  author={Gibiansky, Andrew},
  year={2017},
  note={Available at \url{https://eng.uber.com/horovod/}},
}
@article{sergeev2018horovod,
  title={Horovod: fast and easy distributed deep learning in TensorFlow},
  author={Sergeev, Alexander and Del Balso, Mike},
  journal={arXiv preprint arXiv:1802.05799},
  year={2018}
}

@article{rasley2020deepspeed,
  title={Deepspeed: System optimizations enable training deep learning models with over 100 billion parameters},
  author={Rasley, Jeff and Rajbhandari, Samyam and Ruwase, Olatunji and Yang, Shaden and Zhang, Yong and He, Yuxiong},
  journal={arXiv preprint arXiv:2007.00072},
  year={2020}
}



@article{ouyang2022training,
  title={Training language models to follow instructions with human feedback},
  author={Ouyang, Long and Wu, Jeffrey and Jiang, Xu and Almeida, Diogo and Wainwright, Carroll and Mishkin, Pamela and Zhang, Chong and Agarwal, Sandhini and Slama, Katarina and Ray, Alex and others},
  journal={arXiv preprint arXiv:2203.02155},
  year={2022}
}

@inproceedings{christiano2017deep,
  title={Deep reinforcement learning from human preferences},
  author={Christiano, Paul F and Leike, Jan and Brown, Tom B and Martic, Miljan and Legg, Shane and Amodei, Dario},
  booktitle={Advances in Neural Information Processing Systems},
  pages={4299--4307},
  year={2017}
}





@inproceedings{brants2009distributed,
  title={Distributed language models},
  author={Brants, Thorsten and Xu, Peng},
  booktitle={Proceedings of Human Language Technologies: The 2009 Annual Conference of the North American Chapter of the Association for Computational Linguistics, Companion Volume: Tutorial Abstracts},
  pages={3--4},
  year={2009}
}





@inproceedings{Brown2020language,
  author = {Brown, T. and others},
  title = {Language Models Are Few-Shot Learners},
  booktitle = {NeurIPS},
  year = {2020}
}

@article{dean2008mapreduce,
  title={MapReduce: simplified data processing on large clusters},
  author={Dean, Jeffrey and Ghemawat, Sanjay},
  journal={Communications of the ACM},
  volume={51},
  number={1},
  pages={107--113},
  year={2008},
  publisher={ACM New York, NY, USA}
}
@inproceedings{zaharia2010spark,
  title={Spark: Cluster computing with working sets},
  author={Zaharia, Matei and Chowdhury, Mosharaf and Franklin, Michael J and Shenker, Scott and Stoica, Ion},
  booktitle={2nd USENIX workshop on hot topics in cloud computing (HotCloud 10)},
  year={2010}
}

@article{Wei2021zero_shot,
  author = {Wei, J. and others},
  title = {Finetuned Language Models Are Zero-Shot Learners},
  journal = {ArXiv:2109.01652},
  year = {2021}
}

@article{Zhu2023minigpt4,
  author = {Zhu, D. and others},
  title = {MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models},
  journal = {ArXiv:2304.10592},
  year = {2023}
}

@article{Driess2023palme,
  author = {Driess, D. and others},
  title = {Palm-E: An Embodied Multimodal Language Model},
  journal = {ArXiv:2303.03378},
  year = {2023}
}

@article{Su2023pandagpt,
  author = {Su and others},
  title = {PandaGPT: One Model to Instruction-Follow Them All},
  year = {2023}
}

@article{hu2021lora,
  title={Lora: Low-rank adaptation of large language models},
  author={Hu, Edward J and Shen, Yelong and Wallis, Phillip and Allen-Zhu, Zeyuan and Li, Yuanzhi and Wang, Shean and Wang, Lu and Chen, Weizhu},
  journal={arXiv preprint arXiv:2106.09685},
  year={2021}
}

@article{imteaj2021survey,
  title={A survey on federated learning for resource-constrained IoT devices},
  author={Imteaj, Ahmed and Thakker, Urmish and Wang, Shiqiang and Li, Jian and Amini, M Hadi},
  journal={IEEE Internet of Things Journal},
  volume={9},
  number={1},
  pages={1--24},
  year={2021},
  publisher={IEEE}
}


%VLM@article{101vlmchiang2023vicuna,
  title={Vicuna: An open-source chatbot impressing gpt-4 with 90\%* chatgpt quality},
  author={Chiang, Wei-Lin and Li, Zhuohan and Lin, Zi and Sheng, Ying and Wu, Zhanghao and Zhang, Hao and Zheng, Lianmin and Zhuang, Siyuan and Zhuang, Yonghao and Gonzalez, Joseph E and others},
  journal={See https://vicuna. lmsys. org (accessed 14 April 2023)},
  volume={2},
  number={3},
  pages={6},
  year={2023}
}
@article{102vlmliu2024visual,
  title={Visual instruction tuning},
  author={Liu, Haotian and Li, Chunyuan and Wu, Qingyang and Lee, Yong Jae},
  journal={Advances in neural information processing systems},
  volume={36},
  year={2024}
}

@article{103vlmshi2023clip,
  title={Clip-guided federated learning on heterogeneous and long-tailed data},
  author={Shi, Jiangming and Zheng, Shanshan and Yin, Xiangbo and Lu, Yang and Xie, Yuan and Qu, Yanyun},
  journal={arXiv preprint arXiv:2312.08648},
  year={2023}
}
@inproceedings{104vlmzhuminigpt,
  title={MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models},
  author={Zhu, Deyao and Chen, Jun and Shen, Xiaoqian and Li, Xiang and Elhoseiny, Mohamed},
  booktitle={The Twelfth International Conference on Learning Representations},
  year={2024}
}
@article{105vlmimteaj2024tripleplay,
  title={TriplePlay: Enhancing Federated Learning with CLIP for Non-IID Data and Resource Efficiency},
  author={Imteaj, Ahmed and Hossain, Md Zarif and Zaman, Saika and Shahid, Abdur R},
  journal={2024 IEEE Conference on Big Data},
  year={2024}
}
@inproceedings{106vlmlu2023fedclip,
  title={FEDCLIP: FAST GENERALIZATION AND PERSONALIZATION FOR CLIP IN FEDERATED LEARNING},
  author={Lu, Wang and Xixu, HU and Wang, Jindong and Xie, Xing},
  booktitle={ICLR 2023 Workshop on Trustworthy and Reliable Large-Scale Machine Learning Models},
  year={2023}

}
@article{107vlmnguyen2024flora,
  title={Flora: Enhancing vision-language models with parameter-efficient federated learning},
  author={Nguyen, Duy Phuong and Munoz, J Pablo and Jannesari, Ali},
  journal={arXiv preprint arXiv:2404.15182},
  year={2024}
}
@inproceedings{108vlmradford2021learning,
  title={Learning transferable visual models from natural language supervision},
  author={Radford, Alec and Kim, Jong Wook and Hallacy, Chris and Ramesh, Aditya and Goh, Gabriel and Agarwal, Sandhini and Sastry, Girish and Askell, Amanda and Mishkin, Pamela and Clark, Jack and others},
  booktitle={International conference on machine learning},
  pages={8748--8763},
  year={2021},
  organization={PMLR}
}
@inproceedings{109vlmguo2023pfedprompt,
  title={Pfedprompt: Learning personalized prompt for vision-language models in federated learning},
  author={Guo, Tao and Guo, Song and Wang, Junxiao},
  booktitle={Proceedings of the ACM Web Conference 2023},
  pages={1364--1374},
  year={2023}
}



@article{110vlmalayrac2022flamingo,
  title={Flamingo: a visual language model for few-shot learning},
  author={Alayrac, Jean-Baptiste and others},
  journal={Advances in Neural Information Processing Systems  (NeurIPS) },
  volume={35},
  pages={23716--23736},
  year={2022}
}

@inproceedings{111vlmchen2024feddat,
  title={Feddat: An approach for foundation model finetuning in multi-modal heterogeneous federated learning},
  author={Chen, Haokun and Zhang, Yao and Krompass, Denis and Gu, Jindong and Tresp, Volker},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={38},
  number={10},
  pages={11285--11293},
  year={2024}
}

@misc{139vlmtechtargetWhatMachine,
    author = {},
    title = {{W}hat is {M}achine {L}earning {B}ias ({A}{I} {B}ias)? | {D}efinition from {T}ech{T}arget --- techtarget.com},
    howpublished = {\url{https://www.techtarget.com/searchenterpriseai/definition/machine-learning-bias-algorithm-bias-or-AI-bias}},
    year = {},
    note = {[Accessed 17-01-2025]},
}

@inproceedings{112vlmzeng2024fair,
  title={Fair federated learning with biased vision-language models},
  author={Zeng, Huimin and Yue, Zhenrui and Zhang, Yang and Shang, Lanyu and Wang, Dong},
  booktitle={Findings of the Association for Computational Linguistics ACL 2024},
  pages={10002--10017},
  year={2024}
}
@article{113vlmdosovitskiy2020image,
  title={An image is worth 16x16 words: Transformers for image recognition at scale},
  author={Dosovitskiy, Alexey},
  journal={arXiv preprint arXiv:2010.11929},
  year={2020}
}

@inproceedings{114vlmli2022blip,
  title={Blip: Bootstrapping language-image pre-training for unified vision-language understanding and generation},
  author={Li, Junnan and Li, Dongxu and Xiong, Caiming and Hoi, Steven},
  booktitle={International conference on machine learning},
  pages={12888--12900},
  year={2022},
  organization={PMLR}
}


@inproceedings{115vlmseth2023dear,
  title={Dear: Debiasing vision-language models with additive residuals},
  author={Seth, Ashish and Hemani, Mayur and Agarwal, Chirag},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={6820--6829},
  year={2023}
}

@inproceedings{116vlmwang2019balanced,
  title={Balanced datasets are not enough: Estimating and mitigating gender bias in deep image representations},
  author={Wang, Tianlu and Zhao, Jieyu and Yatskar, Mark and Chang, Kai-Wei and Ordonez, Vicente},
  booktitle={Proceedings of the IEEE/CVF international conference on computer vision},
  pages={5310--5319},
  year={2019}
}

@inproceedings{117vlmzhang2025grace,
  title={GRACE: Graph-Based Contextual Debiasing for Fair Visual Question Answering},
  author={Zhang, Yifeng and Jiang, Ming and Zhao, Qi},
  booktitle={European Conference on Computer Vision},
  pages={176--194},
  year={2025},
  organization={Springer}
}

@inproceedings{118vlmhoward2024socialcounterfactuals,
  title={SocialCounterfactuals: Probing and Mitigating Intersectional Social Biases in Vision-Language Models with Counterfactual Examples},
  author={Howard, Phillip and Madasu, Avinash and Le, Tiep and Moreno, Gustavo Lujan and Bhiwandiwalla, Anahita and Lal, Vasudev},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={11975--11985},
  year={2024}
}

@inproceedings{119vlmyang2023alip,
  title={Alip: Adaptive language-image pre-training with synthetic caption},
  author={Yang, Kaicheng and Deng, Jiankang and An, Xiang and Li, Jiawei and Feng, Ziyong and Guo, Jia and Yang, Jing and Liu, Tongliang},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={2922--2931},
  year={2023}
}

@inproceedings{120vlmradford2021learning,
  title={Learning transferable visual models from natural language supervision},
  author={Radford, Alec and Kim, Jong Wook and Hallacy, Chris and Ramesh, Aditya and Goh, Gabriel and Agarwal, Sandhini and Sastry, Girish and Askell, Amanda and Mishkin, Pamela and Clark, Jack and others},
  booktitle={International conference on machine learning},
  pages={8748--8763},
  year={2021},
  organization={PMLR}
}
@article{zhao2024galore,
  title={Galore: Memory-efficient llm training by gradient low-rank projection},
  author={Zhao, Jiawei and Zhang, Zhenyu and Chen, Beidi and Wang, Zhangyang and Anandkumar, Anima and Tian, Yuandong},
  journal={arXiv preprint arXiv:2403.03507},
  year={2024}
}

@inproceedings{121singh2022flava,
  title={Flava: A foundational language and vision alignment model},
  author={Singh, Amanpreet and Hu, Ronghang and Goswami, Vedanuj and Couairon, Guillaume and Galuba, Wojciech and Rohrbach, Marcus and Kiela, Douwe},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={15638--15650},
  year={2022}
}

@article{122vlmfan2024improving,
  title={Improving clip training with language rewrites},
  author={Fan, Lijie and Krishnan, Dilip and Isola, Phillip and Katabi, Dina and Tian, Yonglong},
  journal={Advances in Neural Information Processing Systems},
  volume={36},
  year={2024}
}

@inproceedings{123vlmcherti2023reproducible,
  title={Reproducible scaling laws for contrastive language-image learning},
  author={Cherti, Mehdi and Beaumont, Romain and Wightman, Ross and Wortsman, Mitchell and Ilharco, Gabriel and Gordon, Cade and Schuhmann, Christoph and Schmidt, Ludwig and Jitsev, Jenia},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={2818--2829},
  year={2023}
}

@inproceedings{124vlmmu2022slip,
  title={Slip: Self-supervision meets language-image pre-training},
  author={Mu, Norman and Kirillov, Alexander and Wagner, David and Xie, Saining},
  booktitle={European conference on computer vision},
  pages={529--544},
  year={2022},
  organization={Springer}
}

@article{125vlmbrown2020language,
  title={Language models are few-shot learners},
  author={Brown, Tom and Mann, Benjamin and Ryder, Nick and Subbiah, Melanie and Kaplan, Jared D and Dhariwal, Prafulla and Neelakantan, Arvind and Shyam, Pranav and Sastry, Girish and Askell, Amanda and others},
  journal={Advances in neural information processing systems},
  volume={33},
  pages={1877--1901},
  year={2020}
}


@article{126vlmzhao2017men,
  title={Men also like shopping: Reducing gender bias amplification using corpus-level constraints},
  author={Zhao, Jieyu and Wang, Tianlu and Yatskar, Mark and Ordonez, Vicente and Chang, Kai-Wei},
  journal={arXiv preprint arXiv:1707.09457},
  year={2017}
}

@inproceedings{127vlmli2022blip,
  title={Blip: Bootstrapping language-image pre-training for unified vision-language understanding and generation},
  author={Li, Junnan and Li, Dongxu and Xiong, Caiming and Hoi, Steven},
  booktitle={International conference on machine learning},
  pages={12888--12900},
  year={2022},
  organization={PMLR}
}

@inproceedings{128vlmmcmahan2017communication,
  title={Communication-efficient learning of deep networks from decentralized data},
  author={McMahan, Brendan and Moore, Eider and Ramage, Daniel and Hampson, Seth and y Arcas, Blaise Aguera},
  booktitle={Artificial intelligence and statistics},
  pages={1273--1282},
  year={2017},
  organization={PMLR}
}

@inproceedings{129vlmmohri2019agnostic,
  title={Agnostic federated learning},
  author={Mohri, Mehryar and Sivek, Gary and Suresh, Ananda Theertha},
  booktitle={International conference on machine learning},
  pages={4615--4625},
  year={2019},
  organization={PMLR}
}

@inproceedings{130vlmezzeldin2023fairfed,
  title={Fairfed: Enabling group fairness in federated learning},
  author={Ezzeldin, Yahya H and Yan, Shen and He, Chaoyang and Ferrara, Emilio and Avestimehr, A Salman},
  booktitle={Proceedings of the AAAI conference on artificial intelligence},
  volume={37},
  number={6},
  pages={7494--7502},
  year={2023}
}

@inproceedings{131vlmhong2021federated,
  title={Federated adversarial debiasing for fair and transferable representations},
  author={Hong, Junyuan and Zhu, Zhuangdi and Yu, Shuyang and Wang, Zhangyang and Dodge, Hiroko H and Zhou, Jiayu},
  booktitle={Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery \& Data Mining},
  pages={617--627},
  year={2021}
}

@article{132vlmhe2024parameter,
  title={Parameter-Efficient Fine-Tuning Medical Multimodal Large Language Models for Medical Visual Grounding},
  author={He, Jinlong and Li, Pengfei and Liu, Gang and Zhong, Shenjun},
  journal={arXiv preprint arXiv:2410.23822},
  year={2024}
}

@article{133vlmhu2021lora,
  title={Lora: Low-rank adaptation of large language models},
  author={Hu, Edward J and Shen, Yelong and Wallis, Phillip and Allen-Zhu, Zeyuan and Li, Yuanzhi and Wang, Shean and Wang, Lu and Chen, Weizhu},
  journal={arXiv preprint arXiv:2106.09685},
  year={2021}
}

@inproceedings{134vlmye2024mplug,
  title={mplug-owl2: Revolutionizing multi-modal large language model with modality collaboration},
  author={Ye, Qinghao and Xu, Haiyang and Ye, Jiabo and Yan, Ming and Hu, Anwen and Liu, Haowei and Qian, Qi and Zhang, Ji and Huang, Fei},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={13040--13051},
  year={2024}
}

@inproceedings{135vlmchen2022visualgpt,
  title={Visualgpt: Data-efficient adaptation of pretrained language models for image captioning},
  author={Chen, Jun and Guo, Han and Yi, Kai and Li, Boyang and Elhoseiny, Mohamed},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={18030--18040},
  year={2022}
}

@inproceedings{136vlmramesh2021zero,
  title={Zero-shot text-to-image generation},
  author={Ramesh, Aditya and Pavlov, Mikhail and Goh, Gabriel and Gray, Scott and Voss, Chelsea and Radford, Alec and Chen, Mark and Sutskever, Ilya},
  booktitle={International conference on machine learning},
  pages={8821--8831},
  year={2021},
  organization={Pmlr}
}
@article{137vlmli2019visualbert,
  title={Visualbert: A simple and performant baseline for vision and language},
  author={Li, Liunian Harold and Yatskar, Mark and Yin, Da and Hsieh, Cho-Jui and Chang, Kai-Wei},
  journal={arXiv preprint arXiv:1908.03557},
  year={2019}
}
@inproceedings{LLMH9kenton2019bert,
  title={BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding},
  author={Kenton, Jacob Devlin Ming-Wei Chang and Toutanova, Lee Kristina},
  booktitle={Proceedings of NAACL-HLT},
  pages={4171--4186},
  year={2019}
}



@article{139vlmyao2022detclip,
  title={Detclip: Dictionary-enriched visual-concept paralleled pre-training for open-world detection},
  author={Yao, Lewei and Han, Jianhua and Wen, Youpeng and Liang, Xiaodan and Xu, Dan and Zhang, Wei and Li, Zhenguo and Xu, Chunjing and Xu, Hang},
  journal={Advances in Neural Information Processing Systems},
  volume={35},
  pages={9125--9138},
  year={2022}
}

@article{140vlmdou2022coarse,
  title={Coarse-to-fine vision-language pre-training with fusion in the backbone},
  author={Dou, Zi-Yi and Kamath, Aishwarya and Gan, Zhe and Zhang, Pengchuan and Wang, Jianfeng and Li, Linjie and Liu, Zicheng and Liu, Ce and LeCun, Yann and Peng, Nanyun and others},
  journal={Advances in neural information processing systems},
  volume={35},
  pages={32942--32956},
  year={2022}
}

@inproceedings{141vlmxu2022groupvit,
  title={Groupvit: Semantic segmentation emerges from text supervision},
  author={Xu, Jiarui and De Mello, Shalini and Liu, Sifei and Byeon, Wonmin and Breuel, Thomas and Kautz, Jan and Wang, Xiaolong},
  booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition},
  pages={18134--18144},
  year={2022}
}

@inproceedings{142vlmzhong2022regionclip,
  title={Regionclip: Region-based language-image pretraining},
  author={Zhong, Yiwu and Yang, Jianwei and Zhang, Pengchuan and Li, Chunyuan and Codella, Noel and Li, Liunian Harold and Zhou, Luowei and Dai, Xiyang and Yuan, Lu and Li, Yin and others},
  booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition},
  pages={16793--16803},
  year={2022}
}

@inproceedings{143vlmfavero2024multi,
  title={Multi-modal hallucination control by visual information grounding},
  author={Favero, Alessandro and Zancato, Luca and Trager, Matthew and Choudhary, Siddharth and Perera, Pramuditha and Achille, Alessandro and Swaminathan, Ashwin and Soatto, Stefano},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={14303--14312},
  year={2024}
}

@inproceedings{144vlmwang2024haloquest,
  title={Haloquest: A visual hallucination dataset for advancing multimodal reasoning},
  author={Wang, Zhecan and Bingham, Garrett and Yu, Adams Wei and Le, Quoc V and Luong, Thang and Ghiasi, Golnaz},
  booktitle={European Conference on Computer Vision},
  pages={288--304},
  year={2024},
  organization={Springer}
}

@inproceedings{145vlmguan2024hallusionbench,
  title={Hallusionbench: an advanced diagnostic suite for entangled language hallucination and visual illusion in large vision-language models},
  author={Guan, Tianrui and Liu, Fuxiao and Wu, Xiyang and Xian, Ruiqi and Li, Zongxia and Liu, Xiaoyu and Wang, Xijun and Chen, Lichang and Huang, Furong and Yacoob, Yaser and others},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={14375--14385},
  year={2024}
}


@article{146vlmbitton2024visual,
  title={Visual riddles: A commonsense and world knowledge challenge for large vision and language models},
  author={Bitton Guetta, Nitzan and Slobodkin, Aviv and Maimon, Aviya and Habba, Eliya and Rassin, Royi and Bitton, Yonatan and Szpektor, Idan and Globerson, Amir and Elovici, Yuval},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={139561--139588},
  year={2024}


@inproceedings{147vlmkwon2024toward,
  title={Toward grounded commonsense reasoning},
  author={Kwon, Minae and Hu, Hengyuan and Myers, Vivek and Karamcheti, Siddharth and Dragan, Anca and Sadigh, Dorsa},
  booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)},
  pages={5463--5470},
  year={2024},
  organization={IEEE}
}

@article{148vlmxenos2024vllms,
  title={Vllms provide better context for emotion understanding through common sense reasoning},
  author={Xenos, Alexandros and Foteinopoulou, Niki Maria and Ntinou, Ioanna and Patras, Ioannis and Tzimiropoulos, Georgios},
  journal={arXiv preprint arXiv:2404.07078},
  year={2024}
}

@article{149vlmhossain2024sim,
  title={Sim-clip: Unsupervised siamese adversarial fine-tuning for robust and semantically-rich vision-language models},
  author={Hossain, Md Zarif and Imteaj, Ahmed},
  journal={arXiv preprint arXiv:2407.14971},
  year={2024}
}

@inproceedings{150vlmschlarmann2024robust,
  title={Robust CLIP: Unsupervised Adversarial Fine-Tuning of Vision Embeddings for Robust Large Vision-Language Models},
  author={Schlarmann, Christian and Singh, Naman Deep and Croce, Francesco and Hein, Matthias},
  booktitle={International Conference on Machine Learning},
  pages={43685--43704},
  year={2024},
  organization={PMLR}
}

@inproceedings{151vlmhossain2024securing,
  title={Securing vision-language models with a robust encoder against jailbreak and adversarial attacks},
  author={Hossain, Md Zarif and Imteaj, Ahmed},
  booktitle={2024 IEEE International Conference on Big Data (BigData)},
  pages={6250--6259},
  year={2024},
  organization={IEEE}
}

@inproceedings{152vlmzhu2024seer,
  title={Seer: Backdoor detection for vision-language models through searching target text and image trigger jointly},
  author={Zhu, Liuwan and Ning, Rui and Li, Jiang and Xin, Chunsheng and Wu, Hongyi},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={38},
  number={7},
  pages={7766--7774},
  year={2024}
}

@inproceedings{153vlmlyu2024trojvlm,
  title={Trojvlm: Backdoor attack against vision language models},
  author={Lyu, Weimin and Pang, Lu and Ma, Tengfei and Ling, Haibin and Chen, Chao},
  booktitle={European Conference on Computer Vision},
  pages={467--483},
  year={2024},
  organization={Springer}
}

@inproceedings{154vlmwang2024break,
  title={Break the visual perception: Adversarial attacks targeting encoded visual tokens of large vision-language models},
  author={Wang, Yubo and Liu, Chaohu and Qu, Yanqiu and Cao, Haoyu and Jiang, Deqiang and Xu, Linli},
  booktitle={Proceedings of the 32nd ACM International Conference on Multimedia},
  pages={1072--1081},
  year={2024}
}

@article{155vlmliu2024survey,
  title={A survey of attacks on large vision-language models: Resources, advances, and future trends},
  author={Liu, Daizong and Yang, Mingyu and Qu, Xiaoye and Zhou, Pan and Cheng, Yu and Hu, Wei},
  journal={arXiv preprint arXiv:2407.07403},
  year={2024}
}

@article{156vlmlaurenccon2024matters,
  title={What matters when building vision-language models?},
  author={Lauren{\c{c}}on, Hugo and Tronchon, L{\'e}o and Cord, Matthieu and Sanh, Victor},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={87874--87907},
  year={2024}
}

@article{157vlmxing2024survey,
  title={A survey of efficient fine-tuning methods for vision-language models—prompt and adapter},
  author={Xing, Jialu and Liu, Jianping and Wang, Jian and Sun, Lulu and Chen, Xi and Gu, Xunxun and Wang, Yingfei},
  journal={Computers \& Graphics},
  volume={119},
  pages={103885},
  year={2024},
  publisher={Elsevier}
}

@article{158vlmlee2024vhelm,
  title={Vhelm: A holistic evaluation of vision language models},
  author={Lee, Tony and Tu, Haoqin and Wong, Chi Heem and Zheng, Wenhao and Zhou, Yiyang and Mai, Yifan and Roberts, Josselin and Yasunaga, Michihiro and Yao, Huaxiu and Xie, Cihang and others},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={140632--140666},
  year={2024}
}

@inproceedings{159vlmxie2024advancing,
  title={Advancing Multimodal Large Language Models with Quantization-Aware Scale Learning for Efficient Adaptation},
  author={Xie, Jingjing and Zhang, Yuxin and Lin, Mingbao and Cao, Liujuan and Ji, Rongrong},
  booktitle={Proceedings of the 32nd ACM International Conference on Multimedia},
  pages={10582--10591},
  year={2024}
}

@inproceedings{160vlmhao2024quantized,
  title={Quantized prompt for efficient generalization of vision-language models},
  author={Hao, Tianxiang and Ding, Xiaohan and Feng, Juexiao and Yang, Yuhong and Chen, Hui and Ding, Guiguang},
  booktitle={European Conference on Computer Vision},
  pages={54--73},
  year={2024},
  organization={Springer}
}

@INPROCEEDINGS{161vlm10903230,
  author={Imteaj, Ahmed and Hossain, Md Zarif and Zaman, Saika and Shahid, Abdur R.},
  booktitle={2024 International Conference on Machine Learning and Applications (ICMLA)}, 
  title={TriplePlay: Enhancing Federated Learning with CLIP for Non-IID Data and Resource Efficiency}, 
  year={2024},
  volume={},
  number={},
  pages={1474-1480},
  keywords={Training;Adaptation models;Quantization (signal);Heavily-tailed distribution;Foundation models;Federated learning;Computational modeling;Simulation;Data models;Optimization;Federated Learning;foundation model;CLIP;personalization;GAN;resource optimization},
  doi={10.1109/ICMLA61862.2024.00228}}

@article{162vlmwu2024transferring,
  title={Transferring vision-language models for visual recognition: A classifier perspective},
  author={Wu, Wenhao and Sun, Zhun and Song, Yuxin and Wang, Jingdong and Ouyang, Wanli},
  journal={International Journal of Computer Vision},
  volume={132},
  number={2},
  pages={392--409},
  year={2024},
  publisher={Springer}
}

@inproceedings{163vlmgao2020listen,
  title={Listen to look: Action recognition by previewing audio},
  author={Gao, Ruohan and Oh, Tae-Hyun and Grauman, Kristen and Torresani, Lorenzo},
  booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition},
  pages={10457--10467},
  year={2020}
}

@inproceedings{164vlmzhou2022conditional,
  title={Conditional prompt learning for vision-language models},
  author={Zhou, Kaiyang and Yang, Jingkang and Loy, Chen Change and Liu, Ziwei},
  booktitle={Proceedings of the IEEE/CVF conference on computer vision and pattern recognition},
  pages={16816--16825},
  year={2022}
}

@article{165vlmzhang2021tip,
  title={Tip-adapter: Training-free clip-adapter for better vision-language modeling},
  author={Zhang, Renrui and Fang, Rongyao and Zhang, Wei and Gao, Peng and Li, Kunchang and Dai, Jifeng and Qiao, Yu and Li, Hongsheng},
  journal={arXiv preprint arXiv:2111.03930},
  year={2021}
}

@inproceedings{166vlmzoudynamath,
  title={DynaMath: A Dynamic Visual Benchmark for Evaluating Mathematical Reasoning Robustness of Vision Language Models},
  author={Zou, Chengke and Guo, Xingang and Yang, Rui and Zhang, Junyu and Hu, Bin and Zhang, Huan},
  booktitle={The Thirteenth International Conference on Learning Representations}
}

@article{167vlmlu2021inter,
  title={Inter-GPS: Interpretable geometry problem solving with formal language and symbolic reasoning},
  author={Lu, Pan and Gong, Ran and Jiang, Shibiao and Qiu, Liang and Huang, Siyuan and Liang, Xiaodan and Zhu, Song-Chun},
  journal={arXiv preprint arXiv:2105.04165},
  year={2021}
}

@article{168vlmpeng2024multimath,
  title={Multimath: Bridging visual and mathematical reasoning for large language models},
  author={Peng, Shuai and Fu, Di and Gao, Liangcai and Zhong, Xiuqin and Fu, Hongguang and Tang, Zhi},
  journal={arXiv preprint arXiv:2409.00147},
  year={2024}
}
@article{169vlmlu2023mathvista,
  title={Mathvista: Evaluating mathematical reasoning of foundation models in visual contexts},
  author={Lu, Pan and Bansal, Hritik and Xia, Tony and Liu, Jiacheng and Li, Chunyuan and Hajishirzi, Hannaneh and Cheng, Hao and Chang, Kai-Wei and Galley, Michel and Gao, Jianfeng},
  journal={arXiv preprint arXiv:2310.02255},
  year={2023}
}
@article{170vlmjha2024clap4clip,
  title={Clap4clip: Continual learning with probabilistic finetuning for vision-language models},
  author={Jha, Saurav and Gong, Dong and Yao, Lina},
  journal={arXiv preprint arXiv:2403.19137},
  year={2024}
}
@article{171vlmzhou2025learning,
  title={Learning without forgetting for vision-language models},
  author={Zhou, Da-Wei and Zhang, Yuanhan and Wang, Yan and Ning, Jingyi and Ye, Han-Jia and Zhan, De-Chuan and Liu, Ziwei},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year={2025},
  publisher={IEEE}
}
@inproceedings{172vlmzheng2023preventing,
  title={Preventing zero-shot transfer degradation in continual learning of vision-language models},
  author={Zheng, Zangwei and Ma, Mingyuan and Wang, Kai and Qin, Ziheng and Yue, Xiangyu and You, Yang},
  booktitle={Proceedings of the IEEE/CVF international conference on computer vision},
  pages={19125--19136},
  year={2023}
}
@article{173vlmzhao2024explainability,
  title={Explainability for large language models: A survey},
  author={Zhao, Haiyan and Chen, Hanjie and Yang, Fan and Liu, Ninghao and Deng, Huiqi and Cai, Hengyi and Wang, Shuaiqiang and Yin, Dawei and Du, Mengnan},
  journal={ACM Transactions on Intelligent Systems and Technology},
  volume={15},
  number={2},
  pages={1--38},
  year={2024},
  publisher={ACM New York, NY}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%



@inproceedings{174vlmben2024lvlm,
  title={LVLM-Intrepret: An Interpretability Tool for Large Vision-Language Models},
  author={Ben Melech Stan, Gabriela and Aflalo, Estelle and Rohekar, Raanan Yehezkel and Bhiwandiwalla, Anahita and Tseng, Shao-Yen and Olson, Matthew Lyle and Gurwicz, Yaniv and Wu, Chenfei and Duan, Nan and Lal, Vasudev},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={8182--8187},
  year={2024}
}
@inproceedings{175vlmyuan2024back,
  title={Back to the future: Towards explainable temporal reasoning with large language models},
  author={Yuan, Chenhan and Xie, Qianqian and Huang, Jimin and Ananiadou, Sophia},
  booktitle={Proceedings of the ACM Web Conference 2024},
  pages={1963--1974},
  year={2024}
}
@article{176vlmkazmierczak5106267explainability,
  title={Explainability for Vision Foundation Models: A Survey},
  author={Kazmierczak, R{\'e}mi and Berthier, Elo{\"\i}se and Frehse, Goran and Franchi, Gianni},
  journal={Available at SSRN 5106267},
  year={2025}

}


@article{tang2023does,
  title={Does synthetic data generation of llms help clinical text mining?},
  author={Tang, Ruixiang and Han, Xiaotian and Jiang, Xiaoqian and Hu, Xia},
  journal={arXiv preprint arXiv:2303.04360},
  year={2023}
}
@article{long2024llms,
  title={On llms-driven synthetic data generation, curation, and evaluation: A survey},
  author={Long, Lin and Wang, Rui and Xiao, Ruixuan and Zhao, Junbo and Ding, Xiao and Chen, Gang and Wang, Haobo},
  journal={arXiv preprint arXiv:2406.15126},
  year={2024}
}
@article{li2023synthetic,
  title={Synthetic data generation with large language models for text classification: Potential and limitations},
  author={Li, Zhuoyan and Zhu, Hangxiao and Lu, Zhuoran and Yin, Ming},
  journal={arXiv preprint arXiv:2310.07849},
  year={2023}
}
@article{guo2024generative,
  title={Generative AI for Synthetic Data Generation: Methods, Challenges and the Future},
  author={Guo, Xu and Chen, Yiqiang},
  journal={arXiv preprint arXiv:2403.04190},
  year={2024}
}

@article{rafailov2024direct,
  title={Direct preference optimization: Your language model is secretly a reward model},
  author={Rafailov, Rafael and Sharma, Archit and Mitchell, Eric and Manning, Christopher D and Ermon, Stefano and Finn, Chelsea},
  journal={Advances in Neural Information Processing Systems},
  volume={36},
  year={2024}
}
@article{dubey2024llama,
  title={The llama 3 herd of models},
  author={Dubey, Abhimanyu and Jauhri, Abhinav and Pandey, Abhinav and Kadian, Abhishek and Al-Dahle, Ahmad and Letman, Aiesha and Mathur, Akhil and Schelten, Alan and Yang, Amy and Fan, Angela and others},
  journal={arXiv preprint arXiv:2407.21783},
  year={2024}
}

@article{srinivasan2023training,
  title={Training large language models efficiently with sparsity and dataflow},
  author={Srinivasan, Venkat and Gandhi, Darshan and Thakker, Urmish and Prabhakar, Raghu},
  journal={arXiv preprint arXiv:2304.05511},
  year={2023}
}
@article{wang2023bitnet,
  title={Bitnet: Scaling 1-bit transformers for large language models},
  author={Wang, Hongyu and Ma, Shuming and Dong, Li and Huang, Shaohan and Wang, Huaijie and Ma, Lingxiao and Yang, Fan and Wang, Ruiping and Wu, Yi and Wei, Furu},
  journal={arXiv preprint arXiv:2310.11453},
  year={2023}
}
@inproceedings{ryabinin2023swarm,
  title={Swarm parallelism: Training large models can be surprisingly communication-efficient},
  author={Ryabinin, Max and Dettmers, Tim and Diskin, Michael and Borzunov, Alexander},
  booktitle={International Conference on Machine Learning},
  pages={29416--29440},
  year={2023},
  organization={PMLR}
}

@article{gu2023mamba,
  title={Mamba: Linear-time sequence modeling with selective state spaces},
  author={Gu, Albert and Dao, Tri},
  journal={arXiv preprint arXiv:2312.00752},
  year={2023}
}

@article{zhang2024lolcats,
  title={LoLCATs: On Low-Rank Linearizing of Large Language Models},
  author={Zhang, Michael and Arora, Simran and Chalamala, Rahul and Wu, Alan and Spector, Benjamin and Singhal, Aaryan and Ramesh, Krithik and R{\'e}, Christopher},
  journal={arXiv preprint arXiv:2410.10254},
  year={2024}
}

@inproceedings{ren2021zero,
  title={$\{$Zero-offload$\}$: Democratizing $\{$billion-scale$\}$ model training},
  author={Ren, Jie and Rajbhandari, Samyam and Aminabadi, Reza Yazdani and Ruwase, Olatunji and Yang, Shuangyan and Zhang, Minjia and Li, Dong and He, Yuxiong},
  booktitle={2021 USENIX Annual Technical Conference (USENIX ATC 21)},
  pages={551--564},
  year={2021}
}


@inproceedings{fang2023large,
  title={Large Language Models (LLMs) Inference Offloading and Resource Allocation in Cloud-Edge Networks: An Active Inference Approach},
  author={Fang, Jingcheng and He, Ying and Yu, F Richard and Li, Jianqiang and Leung, Victor C},
  booktitle={2023 IEEE 98th Vehicular Technology Conference (VTC2023-Fall)},
  pages={1--5},
  year={2023},
  organization={IEEE}
}

@inproceedings{liu2024cachegen,
  title={Cachegen: Kv cache compression and streaming for fast large language model serving},
  author={Liu, Yuhan and Li, Hanchen and Cheng, Yihua and Ray, Siddhant and Huang, Yuyang and Zhang, Qizheng and Du, Kuntai and Yao, Jiayi and Lu, Shan and Ananthanarayanan, Ganesh and others},
  booktitle={Proceedings of the ACM SIGCOMM 2024 Conference},
  pages={38--56},
  year={2024}
}



@article{panchal2024thinking,
  title={Thinking Forward: Memory-Efficient Federated Finetuning of Language Models},
  author={Panchal, Kunjal and Parikh, Nisarg and Choudhary, Sunav and Zhang, Lijun and Brun, Yuriy and Guan, Hui},
  journal={arXiv preprint arXiv:2405.15551},
  year={2024}
}


@article{pisarchyk2020efficient,
  title={Efficient memory management for deep neural net inference},
  author={Pisarchyk, Yury and Lee, Juhyun},
  journal={arXiv preprint arXiv:2001.03288},
  year={2020}
}

@inproceedings{markov2023quantized,
  title={Quantized distributed training of large models with convergence guarantees},
  author={Markov, Ilia and Vladu, Adrian and Guo, Qi and Alistarh, Dan},
  booktitle={International Conference on Machine Learning},
  pages={24020--24044},
  year={2023},
  organization={PMLR}
}


@article{wang2020linformer,
  title={Linformer: Self-attention with linear complexity},
  author={Wang, Sinong and Li, Belinda Z and Khabsa, Madian and Fang, Han and Ma, Hao},
  journal={arXiv preprint arXiv:2006.04768},
  year={2020}
}


@article{sanh2020movement,
  title={Movement pruning: Adaptive sparsity by fine-tuning},
  author={Sanh, Victor and Wolf, Thomas and Rush, Alexander},
  journal={Advances in neural information processing systems},
  volume={33},
  pages={20378--20389},
  year={2020}
}


@article{shi2019understanding,
  title={Understanding top-k sparsification in distributed deep learning},
  author={Shi, Shaohuai and Chu, Xiaowen and Cheung, Ka Chun and See, Simon},
  journal={arXiv preprint arXiv:1911.08772},
  year={2019}
}


@article{huang2024edgellm,
  title={Edgellm: A highly efficient cpu-fpga heterogeneous edge accelerator for large language models},
  author={Huang, Mingqiang and Shen, Ao and Li, Kai and Peng, Haoxiang and Li, Boyu and Yu, Hao},
  journal={arXiv preprint arXiv:2407.21325},
  year={2024}
}

@article{kim2023greenscale,
  title={GreenScale: Carbon-Aware Systems for Edge Computing},
  author={Kim, Young Geun and Gupta, Udit and McCrabb, Andrew and Son, Yonglak and Bertacco, Valeria and Brooks, David and Wu, Carole-Jean},
  journal={arXiv preprint arXiv:2304.00404},
  year={2023}
}


@article{huang2024efficient,
  title={Efficient Multi-modal Large Language Models via Visual Token Grouping},
  author={Huang, Minbin and Huang, Runhui and Shi, Han and Chen, Yimeng and Zheng, Chuanyang and Sun, Xiangguo and Jiang, Xin and Li, Zhenguo and Cheng, Hong},
  journal={arXiv preprint arXiv:2411.17773},
  year={2024}
}

@inproceedings{lyu2024unibind,
  title={UniBind: LLM-Augmented Unified and Balanced Representation Space to Bind Them All},
  author={Lyu, Yuanhuiyi and Zheng, Xu and Zhou, Jiazhou and Wang, Lin},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={26752--26762},
  year={2024}
}



@article{zhou2024multimax,
  title={MultiMax: Sparse and Multi-Modal Attention Learning},
  author={Zhou, Yuxuan and Fritz, Mario and Keuper, Margret},
  journal={arXiv preprint arXiv:2406.01189},
  year={2024}
}

@article{zhu2024energy,
  title={An Energy-Efficient Dynamic Offloading Algorithm for Edge Computing Based on Deep Reinforcement Learning},
  author={Zhu, Keyu and Li, Shaobo and Zhang, Xingxing and Wang, Jinming and Xie, Cankun and Wu, Fengbin and Xie, RongXiang},
  journal={IEEE Access},
  year={2024},
  publisher={IEEE}
}


@article{yoo2024code,
  title={Code-Switching Curriculum Learning for Multilingual Transfer in LLMs},
  author={Yoo, Haneul and Park, Cheonbok and Yun, Sangdoo and Oh, Alice and Lee, Hwaran},
  journal={arXiv preprint arXiv:2411.02460},
  year={2024}
}

@article{fallah2020personalized,
  title={Personalized federated learning: A meta-learning approach},
  author={Fallah, Alireza and Mokhtari, Aryan and Ozdaglar, Asuman},
  journal={arXiv preprint arXiv:2002.07948},
  year={2020}
}



@article{yangsparse,
  title={Sparse Gradient Compression for Fine-Tuning Large Language Models},
  author={Yang, David H and Amiri, Mohammad Mohammadi and Pedapati, Tejaswini and Chaudhury, Subhajit and Chen, Pin-Yu}
}

@article{das2023beyond,
  title={Beyond size: How gradients shape pruning decisions in large language models},
  author={Das, Rocktim Jyoti and Sun, Mingjie and Ma, Liqun and Shen, Zhiqiang},
  journal={arXiv preprint arXiv:2311.04902},
  year={2023}
}

@article{wang2024language,
  title={Language Models as Zero-shot Lossless Gradient Compressors: Towards General Neural Parameter Prior Models},
  author={Wang, Hui-Po and Fritz, Mario},
  journal={arXiv preprint arXiv:2409.17836},
  year={2024}
}


@inproceedings{jia2024adaptive,
  title={Adaptive Hierarchical Aggregation for Federated Object Detection},
  author={Jia, Ruofan and Xie, Weiying and Lei, Jie and Li, Yunsong},
  booktitle={Proceedings of the 32nd ACM International Conference on Multimedia},
  pages={3732--3740},
  year={2024}
}

@article{abrahamyan2021learned,
  title={Learned gradient compression for distributed deep learning},
  author={Abrahamyan, Lusine and Chen, Yiming and Bekoulis, Giannis and Deligiannis, Nikos},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  volume={33},
  number={12},
  pages={7330--7344},
  year={2021},
  publisher={IEEE}
}

@inproceedings{ren2023accshield,
  title={AccShield: a New Trusted Execution Environment with Machine-Learning Accelerators},
  author={Ren, Wei and Kozlowski, William and Koteshwara, Sandhya and Ye, Mengmei and Franke, Hubertus and Chen, Deming},
  booktitle={2023 60th ACM/IEEE Design Automation Conference (DAC)},
  pages={1--6},
  year={2023},
  organization={IEEE}
}

@inproceedings{li2024adafl,
  title={Adafl: Adaptive client selection and dynamic contribution evaluation for efficient federated learning},
  author={Li, Qingming and Li, Xiaohang and Zhou, Li and Yan, Xiaoran},
  booktitle={ICASSP 2024-2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={6645--6649},
  year={2024},
  organization={IEEE}
}

@article{huang2025ensemble,
  title={Ensemble Learning for Heterogeneous Large Language Models with Deep Parallel Collaboration},
  author={Huang, Yichong and Feng, Xiaocheng and Li, Baohang and Xiang, Yang and Wang, Hui and Liu, Ting and Qin, Bing},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={119838--119860},
  year={2025}
}

@article{chen2023fedbone,
  title={Fedbone: Towards large-scale federated multi-task learning},
  author={Chen, Yiqiang and Zhang, Teng and Jiang, Xinlong and Chen, Qian and Gao, Chenlong and Huang, Wuliang},
  journal={arXiv preprint arXiv:2306.17465},
  year={2023}
}

@inproceedings{shen2024adaptive,
  title={An Adaptive Aggregation Method for Federated Learning via Meta Controller},
  author={Shen, Tao and Li, Zexi and Zhao, Ziyu and Zhu, Didi and Lv, Zheqi and Zhang, Shengyu and Kuang, Kun and Wu, Fei},
  booktitle={Proceedings of the 6th ACM International Conference on Multimedia in Asia Workshops},
  pages={1--1},
  year={2024}
}

@article{choukroun2024adaptive,
  title={Adaptive Consensus Gradients Aggregation for Scaled Distributed Training},
  author={Choukroun, Yoni and Azoulay, Shlomi and Kisilev, Pavel},
  journal={arXiv preprint arXiv:2411.03742},
  year={2024}
}


@article{efthymiadis2024advanced,
  title={Advanced Optimization Techniques for Federated Learning on Non-IID Data},
  author={Efthymiadis, Filippos and Karras, Aristeidis and Karras, Christos and Sioutas, Spyros},
  journal={Future Internet},
  volume={16},
  number={10},
  pages={370},
  year={2024},
  publisher={Multidisciplinary Digital Publishing Institute}
}

@article{behera2022fedsyn,
  title={Fedsyn: Synthetic data generation using federated learning},
  author={Behera, Monik Raj and Upadhyay, Sudhir and Shetty, Suresh and Priyadarshini, Sudha and Patel, Palka and Lee, Ker Farn},
  journal={arXiv preprint arXiv:2203.05931},
  year={2022}
}

@article{ali2025dy,
  title={dy-TACFL: Dynamic Temporal Adaptive Clustered Federated Learning for Heterogeneous Clients},
  author={Ali, Syed Saqib and Ali, Mazhar and Bhatti, Dost Muhammad Saqib and Choi, Bong-Jun},
  journal={Electronics},
  volume={14},
  number={1},
  pages={152},
  year={2025},
  publisher={MDPI}
}

@inproceedings{chen2022federated,
  title={Federated Learning Meets Edge Computing: A Hierarchical Aggregation Mechanism for Mobile Devices},
  author={Chen, Jiewei and Li, Wenjing and Yang, Guoming and Qiu, Xuesong and Guo, Shaoyong},
  booktitle={International Conference on Wireless Algorithms, Systems, and Applications},
  pages={456--467},
  year={2022},
  organization={Springer}
}


@inproceedings{wang2021resource,
  title={Resource-efficient federated learning with hierarchical aggregation in edge computing},
  author={Wang, Zhiyuan and Xu, Hongli and Liu, Jianchun and Huang, He and Qiao, Chunming and Zhao, Yangming},
  booktitle={IEEE INFOCOM 2021-IEEE conference on computer communications},
  pages={1--10},
  year={2021},
  organization={IEEE}
}

@inproceedings{ji2019learning,
  title={Learning private neural language modeling with attentive aggregation},
  author={Ji, Shaoxiong and Pan, Shirui and Long, Guodong and Li, Xue and Jiang, Jing and Huang, Zi},
  booktitle={2019 International joint conference on neural networks (IJCNN)},
  pages={1--8},
  year={2019},
  organization={IEEE}
}


@article{wang2024dynamic,
  title={Dynamic Resource Aggregation Method Based on Statistical Capacity Distribution},
  author={Wang, Yuexin and You, Jiali and Li, Yang},
  journal={Electronics},
  volume={13},
  number={23},
  pages={4617},
  year={2024},
  publisher={MDPI}
}

@article{tan2022towards,
  title={Towards personalized federated learning},
  author={Tan, Alysa Ziying and Yu, Han and Cui, Lizhen and Yang, Qiang},
  journal={IEEE transactions on neural networks and learning systems},
  volume={34},
  number={12},
  pages={9587--9603},
  year={2022},
  publisher={IEEE}
}

@article{liu2023sparse,
  title={Sparse federated learning with hierarchical personalization models},
  author={Liu, Xiaofeng and Wang, Qing and Shao, Yunfeng and Li, Yinchuan},
  journal={IEEE Internet of Things Journal},
  volume={11},
  number={5},
  pages={8539--8551},
  year={2023},
  publisher={IEEE}
}

@article{chen2022pfl,
  title={{PFL}-bench: A comprehensive benchmark for personalized federated learning},
  author={Chen, Daoyuan and Gao, Dawei and Kuang, Weirui and Li, Yaliang and Ding, Bolin},
  journal={Advances in Neural Information Processing Systems},
  volume={35},
  pages={9344--9360},
  year={2022}
}

@inproceedings{chen2024mixed,
  title={Mixed-precision quantization for federated learning on resource-constrained heterogeneous devices},
  author={Chen, Huancheng and Vikalo, Haris},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={6138--6148},
  year={2024}
}

@article{zhu2024efficient,
  title={Efficient Model Compression for Hierarchical Federated Learning},
  author={Zhu, Xi and Yu, Songcan and Wang, Junbo and Yang, Qinglin},
  journal={arXiv preprint arXiv:2405.17522},
  year={2024}
}

@article{ahia2024magnet,
  title={MAGNET: Improving the Multilingual Fairness of Language Models with Adaptive Gradient-Based Tokenization},
  author={Ahia, Orevaoghene and Kumar, Sachin and Gonen, Hila and Hoffman, Valentin and Limisiewicz, Tomasz and Tsvetkov, Yulia and Smith, Noah A},
  journal={arXiv preprint arXiv:2407.08818},
  year={2024}
}


@article{moskvoretskii2024low,
  title={Low-Resource Machine Translation through the Lens of Personalized Federated Learning},
  author={Moskvoretskii, Viktor and Tupitsa, Nazarii and Biemann, Chris and Horv{\'a}th, Samuel and Gorbunov, Eduard and Nikishina, Irina},
  journal={arXiv preprint arXiv:2406.12564},
  year={2024}
}


@article{wang2024q,
  title={Q-VLM: Post-training Quantization for Large Vision-Language Models},
  author={Wang, Changyuan and Wang, Ziwei and Xu, Xiuwei and Tang, Yansong and Zhou, Jie and Lu, Jiwen},
  journal={arXiv preprint arXiv:2410.08119},
  year={2024}
}

@inproceedings{jiang2023multi,
  title={Multi-modality deep network for extreme learned image compression},
  author={Jiang, Xuhao and Tan, Weimin and Tan, Tian and Yan, Bo and Shen, Liquan},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={37},
  number={1},
  pages={1033--1041},
  year={2023}
}


@article{zhao2023tuning,
  title={Tuning LayerNorm in Attention: Towards efficient multi-modal llm finetuning},
  author={Zhao, Bingchen and Tu, Haoqin and Wei, Chen and Mei, Jieru and Xie, Cihang},
  journal={arXiv preprint arXiv:2312.11420},
  year={2023}
}

@article{huang2023towards,
  title={Towards Green AI in Fine-tuning Large Language Models via Adaptive Backpropagation},
  author={Huang, Kai and Yin, Hanyun and Huang, Heng and Gao, Wei},
  journal={arXiv preprint arXiv:2309.13192},
  year={2023}
}

@article{shi2024efficient,
  title={Efficient and green large language models for software engineering: Vision and the road ahead},
  author={Shi, Jieke and Yang, Zhou and Lo, David},
  journal={ACM Transactions on Software Engineering and Methodology},
  year={2024},
  publisher={ACM New York, NY}
}

@inproceedings{petoumenos2015power,
  title={Power capping: What works, what does not},
  author={Petoumenos, Pavlos and Mukhanov, Lev and Wang, Zheng and Leather, Hugh and Nikolopoulos, Dimitrios S},
  booktitle={2015 IEEE 21st International Conference on Parallel and Distributed Systems (ICPADS)},
  pages={525--534},
  year={2015},
  organization={IEEE}
}

@article{li2025energy,
  title={Energy-Efficient Split Learning for Fine-Tuning Large Language Models in Edge Networks},
  author={Li, Zuguang and Wu, Shaohua and Li, Liang and Zhang, Songge},
  journal={IEEE Networking Letters},
  year={2025},
  publisher={IEEE}
}

@article{nguyen2024automatic,
  title={Automatic Structured Pruning for Efficient Architecture in Federated Learning},
  author={Nguyen, Thai Vu and Le, Long Bao and Avila, Anderson},
  journal={arXiv preprint arXiv:2411.01759},
  year={2024}
}


@article{zhao2024alisa,
  title={ALISA: Accelerating Large Language Model Inference via Sparsity-Aware KV Caching},
  author={Zhao, Youpeng and Wu, Di and Wang, Jun},
  journal={arXiv preprint arXiv:2403.17312},
  year={2024}
}

@article{fu2024moa,
  title={Moa: Mixture of sparse attention for automatic large language model compression},
  author={Fu, Tianyu and Huang, Haofeng and Ning, Xuefei and Zhang, Genghan and Chen, Boju and Wu, Tianqi and Wang, Hongyi and Huang, Zixiao and Li, Shiyao and Yan, Shengen and others},
  journal={arXiv preprint arXiv:2406.14909},
  year={2024}
}


@article{beltagy2020longformer,
  title={Longformer: The long-document transformer},
  author={Beltagy, Iz and Peters, Matthew E and Cohan, Arman},
  journal={arXiv preprint arXiv:2004.05150},
  year={2020}
}


@article{dao2022flashattention,
  title={Flashattention: Fast and memory-efficient exact attention with io-awareness},
  author={Dao, Tri and Fu, Dan and Ermon, Stefano and Rudra, Atri and R{\'e}, Christopher},
  journal={Advances in Neural Information Processing Systems},
  volume={35},
  pages={16344--16359},
  year={2022}
}


@article{choromanski2020rethinking,
  title={Rethinking attention with performers},
  author={Choromanski, Krzysztof and Likhosherstov, Valerii and Dohan, David and Song, Xingyou and Gane, Andreea and Sarlos, Tamas and Hawkins, Peter and Davis, Jared and Mohiuddin, Afroz and Kaiser, Lukasz and others},
  journal={arXiv preprint arXiv:2009.14794},
  year={2020}
}


@article{li2023fptq,
  title={Fptq: Fine-grained post-training quantization for large language models},
  author={Li, Qingyuan and Zhang, Yifan and Li, Liang and Yao, Peng and Zhang, Bo and Chu, Xiangxiang and Sun, Yerui and Du, Li and Xie, Yuchen},
  journal={arXiv preprint arXiv:2308.15987},
  year={2023}
}


@article{wilkins2024offline,
  title={Offline energy-optimal llm serving: Workload-based energy models for llm inference on heterogeneous systems},
  author={Wilkins, Grant and Keshav, Srinivasan and Mortier, Richard},
  journal={arXiv preprint arXiv:2407.04014},
  year={2024}
}


@article{hu2024blockllm,
  title={Blockllm: Multi-tenant finer-grained serving for large language models},
  author={Hu, Bodun and Li, Jiamin and Xu, Le and Lee, Myungjin and Jajoo, Akshay and Kim, Geon-Woo and Xu, Hong and Akella, Aditya},
  journal={arXiv preprint arXiv:2404.18322},
  year={2024}
}

@article{corallo2024finch,
  title={FINCH: Prompt-guided Key-Value Cache Compression for Large Language Models},
  author={Corallo, Giulio and Papotti, Paolo},
  journal={Transactions of the Association for Computational Linguistics},
  volume={12},
  pages={1517--1532},
  year={2024},
  publisher={MIT Press 255 Main Street, 9th Floor, Cambridge, Massachusetts 02142, USA~…}
}

@article{liu2024minicache,
  title={MiniCache: KV Cache Compression in Depth Dimension for Large Language Models},
  author={Liu, Akide and Liu, Jing and Pan, Zizheng and He, Yefei and Haffari, Gholamreza and Zhuang, Bohan},
  journal={arXiv preprint arXiv:2405.14366},
  year={2024}
}


@article{nawrot2024dynamic,
  title={Dynamic memory compression: Retrofitting llms for accelerated inference},
  author={Nawrot, Piotr and {\L}a{\'n}cucki, Adrian and Chochowski, Marcin and Tarjan, David and Ponti, Edoardo M},
  journal={arXiv preprint arXiv:2403.09636},
  year={2024}
}


@inproceedings{gangidi2024rdma,
  title={Rdma over ethernet for distributed training at meta scale},
  author={Gangidi, Adithya and Miao, Rui and Zheng, Shengbao and Bondu, Sai Jayesh and Goes, Guilherme and Morsy, Hany and Puri, Rohit and Riftadi, Mohammad and Shetty, Ashmitha Jeevaraj and Yang, Jingyi and others},
  booktitle={Proceedings of the ACM SIGCOMM 2024 Conference},
  pages={57--70},
  year={2024}
}


@inproceedings{guo2024gmlake,
  title={GMLake: Efficient and Transparent GPU Memory Defragmentation for Large-scale DNN Training with Virtual Memory Stitching},
  author={Guo, Cong and Zhang, Rui and Xu, Jiale and Leng, Jingwen and Liu, Zihan and Huang, Ziyu and Guo, Minyi and Wu, Hao and Zhao, Shouren and Zhao, Junping and others},
  booktitle={Proceedings of the 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2},
  pages={450--466},
  year={2024}
}

@article{fahad2022multi,
  title={A multi-queue priority-based task scheduling algorithm in fog computing environment},
  author={Fahad, Muhammad and Shojafar, Mohammad and Abbas, Mubashir and Ahmed, Israr and Ijaz, Humaira},
  journal={Concurrency and Computation: Practice and Experience},
  volume={34},
  number={28},
  pages={e7376},
  year={2022},
  publisher={Wiley Online Library}
}

@article{borzunov2022petals,
  title={Petals: Collaborative inference and fine-tuning of large models},
  author={Borzunov, Alexander and Baranchuk, Dmitry and Dettmers, Tim and Ryabinin, Max and Belkada, Younes and Chumachenko, Artem and Samygin, Pavel and Raffel, Colin},
  journal={arXiv preprint arXiv:2209.01188},
  year={2022}
}

@article{gu2021efficiently,
  title={Efficiently modeling long sequences with structured state spaces},
  author={Gu, Albert and Goel, Karan and R{\'e}, Christopher},
  journal={arXiv preprint arXiv:2111.00396},
  year={2021}
}

@misc{superannotate_dpo,
  author = {{SuperAnnotate}},
  title = {Direct Preference Optimization (DPO): Complete Overview},
  year = {2024},
  url = {https://www.superannotate.com/blog/direct-preference-optimization-dpo},
  note = {Accessed: 2024-10-29}
}


%%%%Lightweight LLMs

@article{lu2024small,
  title={Small language models: Survey, measurements, and insights},
  author={Lu, Zhenyan and Li, Xiang and Cai, Dongqi and Yi, Rongjie and Liu, Fangming and Zhang, Xiwen and Lane, Nicholas D and Xu, Mengwei},
  journal={arXiv preprint arXiv:2409.15790},
  year={2024}
}

@article{li2024advances,
  title={Advances in APPFL: A Comprehensive and Extensible Federated Learning Framework},
  author={Li, Zilinghan and He, Shilan and Yang, Ze and Ryu, Minseok and Kim, Kibaek and Madduri, Ravi},
  journal={arXiv preprint arXiv:2409.11585},
  year={2024}
}

@article{sanh2019distilbert,
  title={DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter},
  author={Sanh, V},
  journal={arXiv preprint arXiv:1910.01108},
  year={2019}
}

@article{jiao2019tinybert,
  title={Tinybert: Distilling bert for natural language understanding},
  author={Jiao, Xiaoqi and Yin, Yichun and Shang, Lifeng and Jiang, Xin and Chen, Xiao and Li, Linlin and Wang, Fang and Liu, Qun},
  journal={arXiv preprint arXiv:1909.10351},
  year={2019}
}

@article{sun2020mobilebert,
  title={Mobilebert: a compact task-agnostic bert for resource-limited devices},
  author={Sun, Zhiqing and Yu, Hongkun and Song, Xiaodan and Liu, Renjie and Yang, Yiming and Zhou, Denny},
  journal={arXiv preprint arXiv:2004.02984},
  year={2020}
}

@article{radford2019language,
  title={Language Models are Unsupervised Multitask Learners},
  author={Radford, Alec and Wu, Jeff and Child, Rewon and Luan, David and Amodei, Dario and Sutskever, Ilya},
  year={2019}
}


@article{black2022gpt,
  title={Gpt-neox-20b: An open-source autoregressive language model},
  author={Black, Sid and Biderman, Stella and Hallahan, Eric and Anthony, Quentin and Gao, Leo and Golding, Laurence and He, Horace and Leahy, Connor and McDonell, Kyle and Phang, Jason and others},
  journal={arXiv preprint arXiv:2204.06745},
  year={2022}
}

@inproceedings{sanh2019distilbert,
  title={DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter},
  author={Sanh, Victor and Debut, Lysandre and Chaumond, Julien and Wolf, Thomas},
  booktitle={NeurIPS EMC^2 Workshop},
  year={2019}
}

@misc{FlanT5-small,
  doi = {10.48550/ARXIV.2210.11416},
  
  url = {https://arxiv.org/abs/2210.11416},
  
  author = {Chung, Hyung Won and Hou, Le and Longpre, Shayne and Zoph, Barret and Tay, Yi and Fedus, William and Li, Eric and Wang, Xuezhi and Dehghani, Mostafa and Brahma, Siddhartha and Webson, Albert and Gu, Shixiang Shane and Dai, Zhuyun and Suzgun, Mirac and Chen, Xinyun and Chowdhery, Aakanksha and Narang, Sharan and Mishra, Gaurav and Yu, Adams and Zhao, Vincent and Huang, Yanping and Dai, Andrew and Yu, Hongkun and Petrov, Slav and Chi, Ed H. and Dean, Jeff and Devlin, Jacob and Roberts, Adam and Zhou, Denny and Le, Quoc V. and Wei, Jason},
  
  keywords = {Machine Learning (cs.LG), Computation and Language (cs.CL), FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {Scaling Instruction-Finetuned Language Models},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {Creative Commons Attribution 4.0 International}
}

@inproceedings{biderman2023pythia,
  title={Pythia: A suite for analyzing large language models across training and scaling},
  author={Biderman, Stella and Schoelkopf, Hailey and Anthony, Quentin Gregory and Bradley, Herbie and O’Brien, Kyle and Hallahan, Eric and Khan, Mohammad Aflah and Purohit, Shivanshu and Prashanth, USVSN Sai and Raff, Edward and others},
  booktitle={International Conference on Machine Learning},
  pages={2397--2430},
  year={2023},
  organization={PMLR}
}

@inproceedings{GALACTICA,
    title={GALACTICA: A Large Language Model for Science},
    author={Ross Taylor and Marcin Kardas and Guillem Cucurull and Thomas Scialom and Anthony Hartshorn and Elvis Saravia and Andrew Poulton and Viktor Kerkez and Robert Stojnic},
    year={2022}
}


@article{muennighoff2022crosslingual,
  title={Crosslingual generalization through multitask finetuning},
  author={Muennighoff, Niklas and Wang, Thomas and Sutawika, Lintang and Roberts, Adam and Biderman, Stella and Scao, Teven Le and Bari, M Saiful and Shen, Sheng and Yong, Zheng-Xin and Schoelkopf, Hailey and others},
  journal={arXiv preprint arXiv:2211.01786},
  year={2022}
}

@article{team2023gemini,
  title={Gemini: a family of highly capable multimodal models},
  author={Team, Gemini and Anil, Rohan and Borgeaud, Sebastian and Alayrac, Jean-Baptiste and Yu, Jiahui and Soricut, Radu and Schalkwyk, Johan and Dai, Andrew M and Hauth, Anja and Millican, Katie and others},
  journal={arXiv preprint arXiv:2312.11805},
  year={2023}
}

@article{javaheripi2023phi,
  title={Phi-2: The surprising power of small language models},
  author={Javaheripi, Mojan and Bubeck, S{\'e}bastien and Abdin, Marah and Aneja, Jyoti and Bubeck, Sebastien and Mendes, Caio C{\'e}sar Teodoro and Chen, Weizhu and Del Giorno, Allie and Eldan, Ronen and Gopi, Sivakanth and others},
  journal={Microsoft Research Blog},
  volume={1},
  number={3},
  pages={3},
  year={2023}
}

@article{raffel2020exploring,
  title={Exploring the limits of transfer learning with a unified text-to-text transformer},
  author={Raffel, Colin and Shazeer, Noam and Roberts, Adam and Lee, Katherine and Narang, Sharan and Matena, Michael and Zhou, Yanqi and Li, Wei and Liu, Peter J},
  journal={Journal of machine learning research},
  volume={21},
  number={140},
  pages={1--67},
  year={2020}
}

@article{lan2019albert,
  title={Albert: A lite bert for self-supervised learning of language representations},
  author={Lan, Zhenzhong},
  journal={arXiv preprint arXiv:1909.11942},
  year={2019}
}

@article{touvron2023llama,
  title={Llama 2: Open foundation and fine-tuned chat models},
  author={Touvron, Hugo and Martin, Louis and Stone, Kevin and Albert, Peter and Almahairi, Amjad and Babaei, Yasmine and Bashlykov, Nikolay and Batra, Soumya and Bhargava, Prajjwal and Bhosale, Shruti and others},
  journal={arXiv preprint arXiv:2307.09288},
  year={2023}
}

@misc{zhang2024tinyllama,
      title={TinyLlama: An Open-Source Small Language Model}, 
      author={Peiyuan Zhang and Guangtao Zeng and Tianduo Wang and Wei Lu},
      year={2024},
      eprint={2401.02385},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

@article{dey2023cerebras,
  title={Cerebras-gpt: Open compute-optimal language models trained on the cerebras wafer-scale cluster},
  author={Dey, Nolan and Gosal, Gurpreet and Khachane, Hemant and Marshall, William and Pathria, Ribhu and Tom, Marvin and Hestness, Joel and others},
  journal={arXiv preprint arXiv:2304.03208},
  year={2023}
}

@article{team2024gemma,
  title={Gemma 2: Improving open language models at a practical size},
  author={Team, Gemma and Riviere, Morgane and Pathak, Shreya and Sessa, Pier Giuseppe and Hardin, Cassidy and Bhupatiraju, Surya and Hussenot, L{\'e}onard and Mesnard, Thomas and Shahriari, Bobak and Ram{\'e}, Alexandre and others},
  journal={arXiv preprint arXiv:2408.00118},
  year={2024}
}

@article{kitaev2020reformer,
  title={Reformer: The efficient transformer},
  author={Kitaev, Nikita and Kaiser, {\L}ukasz and Levskaya, Anselm},
  journal={arXiv preprint arXiv:2001.04451},
  year={2020}
}

@article{yao2024minicpm,
  title={MiniCPM-V: A GPT-4V Level MLLM on Your Phone},
  author={Yao, Yuan and Yu, Tianyu and Zhang, Ao and Wang, Chongyi and Cui, Junbo and Zhu, Hongji and Cai, Tianchi and Li, Haoyu and Zhao, Weilin and He, Zhihui and others},
  journal={arXiv preprint arXiv:2408.01800},
  year={2024}
}

@misc{zhang2022opt,
      title={OPT: Open Pre-trained Transformer Language Models}, 
      author={Susan Zhang and Stephen Roller and Naman Goyal and Mikel Artetxe and Moya Chen and Shuohui Chen and Christopher Dewan and Mona Diab and Xian Li and Xi Victoria Lin and Todor Mihaylov and Myle Ott and Sam Shleifer and Kurt Shuster and Daniel Simig and Punit Singh Koura and Anjali Sridhar and Tianlu Wang and Luke Zettlemoyer},
      year={2022},
      eprint={2205.01068},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

@article{xue2022byt5,
  title={Byt5: Towards a token-free future with pre-trained byte-to-byte models},
  author={Xue, Linting and Barua, Aditya and Constant, Noah and Al-Rfou, Rami and Narang, Sharan and Kale, Mihir and Roberts, Adam and Raffel, Colin},
  journal={Transactions of the Association for Computational Linguistics},
  volume={10},
  pages={291--306},
  year={2022},
  publisher={MIT Press One Broadway, 12th Floor, Cambridge, Massachusetts 02142, USA~…}
}

@article{lyu2023macaw,
  title={Macaw-llm: Multi-modal language modeling with image, audio, video, and text integration},
  author={Lyu, Chenyang and Wu, Minghao and Wang, Longyue and Huang, Xinting and Liu, Bingshuai and Du, Zefeng and Shi, Shuming and Tu, Zhaopeng},
  journal={arXiv preprint arXiv:2306.09093},
  year={2023}
}

@inproceedings{radford2023robust,
  title={Robust speech recognition via large-scale weak supervision},
  author={Radford, Alec and Kim, Jong Wook and Xu, Tao and Brockman, Greg and McLeavey, Christine and Sutskever, Ilya},
  booktitle={International conference on machine learning},
  pages={28492--28518},
  year={2023},
  organization={PMLR}
}

@article{guo2025deepseek,
  title={Deep{S}eek-{R}1: Incentivizing Reasoning Capability in {LLM}s via Reinforcement Learning},
  author={Guo, Daya and  others},
  journal={arXiv preprint arXiv:2501.12948},
  year={2025}
}
@article{yuan2025survey, title={A Survey of Multimodal Learning: Methods, Applications, and Future}, author={Yuan, Yuan and Li, Zhaojian and Zhao, Bin}, journal={ACM Computing Surveys}, year={2025}, publisher={ACM New York, NY} }



@article{friha2024llm,
  title={Llm-based edge intelligence: A comprehensive survey on architectures, applications, security and trustworthiness},
  author={Friha, Othmane and Ferrag, Mohamed Amine and Kantarci, Burak and Cakmak, Burak and Ozgun, Arda and Ghoualmi-Zine, Nassira},
  journal={IEEE Open Journal of the Communications Society},
  year={2024},
  publisher={IEEE}
}

@article{lou2023discrete,
  title={Discrete diffusion modeling by estimating the ratios of the data distribution},
  author={Lou, Aaron and Meng, Chenlin and Ermon, Stefano},
  journal={arXiv preprint arXiv:2310.16834},
  year={2023}
}

@article{kuang2024natural,
  title={Natural Language Understanding and Inference with {MLLM} in Visual Question Answering: A Survey},
  author={Kuang, Jiayi and Shen, Ying and Xie, Jingyou and Luo, Haohao and Xu, Zhe and Li, Ronghao and Li, Yinghui and Cheng, Xianfeng and Lin, Xika and Han, Yu},
  journal={ACM Computing Surveys},
  year={2025},
  publisher={ACM New York, NY}
}
```
