# Awesome Continual Learning for Information Retrieval

Continual Learning (CL) (also known as Incremental or Lifelong Learning) in Information Retrieval (IR) remains underexplored, but is gaining increasing attention, motivating the need for a well-curated collection of relevant literature.

This repository aims to serve as a resource for the IR community and related research areas.


## Surveys
- [**TOIS'25**] From Matching to Generation: A Survey on Generative Information Retrieval. [[Paper](https://dl.acm.org/doi/10.1145/3722552)][[Github](https://github.com/RUC-NLPIR/GenIR-Survey)]
- [**TOIS'24**] Dense Text Retrieval Based on Pretrained Language Models: A Survey. [[Paper](https://dl.acm.org/doi/10.1145/3637870)][[Github](https://github.com/RUCAIBox/DenseRetrieval)]

## Papers

### Text/Document Retrieval
- [**KDD'26**] CREAM: Continual Retrieval on Dynamic Streaming Corpora with Adaptive Soft Memory. [[Paper](http://arxiv.org/abs/2601.02708)][[Code](https://github.com/DAIS-KU/CREAM)]
- [**Information Sciences'25**] Advancing continual lifelong learning in neural information retrieval: Definition, dataset, framework, and empirical evaluation. [[Paper](https://www.sciencedirect.com/science/article/pii/S0020025524012829)][[Code](https://github.com/JingruiHou/CLNIR)]
- [**CoLLAs'25**] Query Drift Compensation: Enabling Compatibility in Continual Learning of Retrieval Embedding Models. [[Paper](http://arxiv.org/abs/2506.00037)][[Code](https://github.com/dipamgoswami/QDC)]
- [**SIGIR'25**] Replication and Exploration of Generative Retrieval over Dynamic Corpora. [[Paper](https://dl.acm.org/doi/epdf/10.1145/3726302.3730314)][[Code](https://github.com/zhangzhen-research/dynamicGR)]
- [**EMNLP'25**] MixLoRA-DSI: Dynamically Expandable Mixture-of-LoRA Experts for Rehearsal-Free Generative Retrieval over Dynamic Corpora. [[Paper](https://aclanthology.org/2025.emnlp-main.20/)][[Code](https://github.com/LouisDo2108/MixLoRA-DSI)]
- [**TOIS'25**] CorpusBrain++: A Continual Generative Pre-Training Framework for Knowledge-Intensive Language Tasks. [[Paper](https://arxiv.org/abs/2402.16767)][[Code](https://github.com/Sherlock-Coder/CorpusBrainPlusPlus)]
- [**ECIR'25**] On the Robustness of Generative Retrieval Models: An Out-of-Distribution Perspective. [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-88711-6_26)]
- [**ECML PKDD'25**] PromptDSI: Prompt-based Rehearsal-free Continual Learning for Document Retrieval. [[Paper](https://dl.acm.org/doi/10.1007/978-3-032-06109-6_22)][[Code](https://github.com/LouisDo2108/PromptDSI)]
- [**EMNLP'24**] Exploring the Practicality of Generative Retrieval on Dynamic Corpora. [[Paper](https://aclanthology.org/2024.emnlp-main.755)]
- [**ICML'23**] IncDSI: Incrementally Updatable Document Retrieval. [[Paper](https://proceedings.mlr.press/v202/kishore23a.html)][[Code](https://github.com/varshakishore/IncDSI)]
- [**CIKM'23**] L2R: Lifelong Learning for First-stage Retrieval with Backward-Compatible Representations. [[Paper](https://dl.acm.org/doi/10.1145/3583780.3614947)][[Code](https://github.com/caiyinqiong/L-2R)]
- [**CIKM'23**] Continual Learning for Generative Retrieval over Dynamic Corpora. [[Paper](https://dl.acm.org/doi/10.1145/3583780.3614821)][[Code](https://github.com/ict-bigdatalab/CLEVER)]
- [**EMNLP'23**] DSI++: Updating Transformer Memory with New Documents. [[Paper](https://aclanthology.org/2023.emnlp-main.510)]
- [**ECIR'22**] Continual Learning of Long Topic Sequences in Neural Information Retrieval. [[Paper](https://dl.acm.org/doi/10.1007/978-3-030-99736-6_17)][[Code](https://github.com/tgeral68/continual_learning_of_long_topic)]
- [**ECIR'21**] Studying Catastrophic Forgetting in Neural Ranking Models. [[Paper](https://dl.acm.org/doi/10.1007/978-3-030-72113-8_25)][[Code](https://github.com/jeslev/OpenNIR-Lifelong)]

### Image Retrieval
- [**CVPR'21**] Continual Learning for Visual Search with Backward Consistent Feature Embedding. [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wan_Continual_Learning_for_Visual_Search_With_Backward_Consistent_Feature_Embedding_CVPR_2022_paper.pdf)][[Code](https://github.com/ivclab/CVS)]
- [**BMVC'20**] On the Exploration of Incremental Learning for Fine-grained Image Retrieval. [[Paper](https://www.bmva-archive.org.uk/bmvc/2020/assets/papers/0079.pdf)]
- [**CVPR'19**] Deep incremental hashing network for efficient image retrieval. [[Paper](https://www.bmva-archive.org.uk/bmvc/2020/assets/papers/0079.pdf)][[Code](https://github.com/IIE-MR/DIHN)]

### Cross-modal Retrieval
- [**CVPR'21 Workshop**] Continual learning in cross-modal retrieval. [[Paper](https://openaccess.thecvf.com/content/CVPR2021W/CLVision/Papers/Wang_Continual_Learning_in_Cross-Modal_Retrieval_CVPRW_2021_Paper.pdf)]

### Multimodal Retrieval
- [**NeurIPS'25**] Continual Multimodal Contrastive Learning. [[Paper](https://neurips.cc/virtual/2025/poster/116428][[Code](https://github.com/Xiaohao-Liu/CMCL)]
- [**ICLR'25**] C-CLIP: Multimodal Continual Learning for Vision-Language Model. [[Paper](https://proceedings.iclr.cc/paper_files/paper/2025/file/72fb9ab442fc60b7ae5d53bf6b478273-Paper-Conference.pdf][[Code](https://github.com/SmallPigPeppa/C-CLIP)]

## Others

### Temporal IR
---
Temporal information is a fundamental source of non-stationarity in data distributions, making Temporal IR inherently relevant to CL in IR.

#### Surveys
- [**arxiv'25**] It's High Time: A Survey of Temporal Question Answering. [[Paper](https://arxiv.org/abs/2505.20243)]
- [**Foundations and Trends® in IR**] Temporal Information Retrieval. [[Paper](https://dl.acm.org/doi/abs/10.1561/1500000043)]

#### Papers
- [**arxiv'26**] Efficient Temporal-aware Matryoshka Adaptation
for Temporal Information Retrieval. [[Paper](https://arxiv.org/pdf/2601.05549)]
- [**WSDM'26**] TempRetriever: Fusion-based Temporal Dense Passage Retrieval for Time-Sensitive Questions. [[Paper](https://dl.acm.org/doi/10.1145/3773966.3777938)][[Code](https://github.com/DataScienceUIBK/TempRetriever)]
- [**EMNLP'25 Findings**] MRAG: A modular retrieval framework for time-sensitive question answering. [[Paper](https://aclanthology.org/2025.findings-emnlp.167)][[Code](https://github.com/siyue-zhang/MRAG)]
- [**ACL'25 Workshop**] Temporal information retrieval via time-specifier model merging. [[Paper](https://aclanthology.org/2025.knowllm-1.1)][[Code](https://github.com/seungyoonee/TSM)]
- [**CIKM'24**] Time-Sensitve Retrieval-Augmented Genera-
tion for Question Answering. [[Paper](https://dl.acm.org/doi/10.1145/3627673.3679800)][[Code](https://github.com/suzhou-22/TS-Retriever)]




### Fundamental CL
---
- [**Nature Machine Intelligence'22**] Three scenarios for continual learning. [[Paper](https://openreview.net/forum?id=9aZ2ixiYGd)][[Code](https://github.com/GMvandeVen/continual-learning)]
- [**Trends in Cognitive Sciences'99**] Catastrophic forgetting in connectionist networks. [[Paper](https://lead.ube.fr/wp-content/uploads/2023/09/000282-catastrophic-forgetting-in-connectionist-networks.pdf)]
- [**Psychology of Learning and Motivation'89**] Catastrophic Interference in Connectionist Networks: The Sequential Learning Problem. [[Paper](https://www.sciencedirect.com/science/chapter/bookseries/abs/pii/S0079742108605368)]


### Lists
---
- **gabriben/awesome-generative-information-retrieval**. [[Github](https://github.com/gabriben/awesome-generative-information-retrieval)]
- **Chriskuei/awesome-generative-retrieval-models**. [[Github](https://github.com/Chriskuei/awesome-generative-retrieval-models)]

## Note
This repository focuses on CL for IR, including text, image, cross-modal, and multimodal retrieval, as well as retrieval-augmented generation (RAG), with a particular focus on the retriever component.

We do not cover CL for classification tasks, which have been extensively studied, particularly in the computer vision community, and already have well-established benchmarks and surveys. 
To avoid redundancy and keep this collection focused on retrieval-centric problems, we recommend the following comprehensive survey for a broader overview of CL:

[**TPAMI 2024**] A Comprehensive Survey of Continual Learning: Theory, Method and Application. [[Paper](https://arxiv.org/abs/2302.00487)] [[Code](https://github.com/lywang3081/Awesome-Continual-Learning)]

We also recommend this curated list:  
[xialeiliu/Awesome-Incremental-Learning](https://github.com/xialeiliu/Awesome-Incremental-Learning), which offers a comprehensive overview of CL but does not specifically focus on IR.

## Feel free to contact me or simply open an issue if you find any interesting paper is missing. :D

Contact: louisdo2108[at]gmail.com 