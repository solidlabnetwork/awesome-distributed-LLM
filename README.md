# awesome-distributed-LLM
An Evolving List of Distributed LLM and Multimodal LLM Papers and Repositories

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
