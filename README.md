# Sparsity Constrained Optimization

----

`Outlier Detection <https://en.wikipedia.org/wiki/Anomaly_detection>`_
(also known as *Anomaly Detection*) is an exciting yet challenging field,
which aims to identify outlying objects that are deviant from the general data distribution.
Outlier detection has been proven critical in many fields, such as credit card
fraud analytics, network intrusion detection, and mechanical unit defect detection.

This repository collects:


#. Books & Academic Papers 
#. Online Courses and Videos
#. Outlier Datasets
#. Open-source and Commercial Libraries/Toolkits
#. Key Conferences & Journals


**More items will be added to the repository**.
Please feel free to suggest other key resources by opening an issue report,
submitting a pull request, or dropping me an email @ (zhaoy@cmu.edu).
Enjoy reading!

BTW, you may find my `[GitHub] <https://github.com/yzhao062>`_ and
`[outlier detection papers] <https://scholar.google.com/citations?user=zoGDYsoAAAAJ&hl=en>`_ useful.

----


### Survey (综述文章)
* \[Arxiv 2021\] **FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks.** [paper](https://arxiv.org/pdf/2104.07145) 
*  \[Arxiv 2021\] **Federated Graph Learning -- A Position Paper.** [paper](https://arxiv.org/pdf/2105.11099)
*  \[Arxiv 2022\] **Federated Graph Neural Networks: Overview, Techniques and Challenges** [paper](https://arxiv.org/pdf/2202.07256)


### Theory （理论文章）

1. \[Arxiv 2020\] **Federated Dynamic GNN with Secure Aggregation.** [paper](https://arxiv.org/pdf/2009.07351)
2. \[Arxiv 2020\] **Privacy-Preserving Graph Neural Network for Node Classification.** [paper](https://arxiv.org/pdf/2005.11903)
3. \[Arxiv 2020\] **ASFGNN: Automated Separated-Federated Graph Neural Network.** [paper](https://arxiv.org/pdf/2011.03248)
4. \[Arxiv 2020\] **GraphFL: A Federated Learning Framework for Semi-Supervised Node Classification on Graphs.** [paper](https://arxiv.org/pdf/2012.04187)
5. \[Arxiv 2021\] **FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation.** [paper](https://arxiv.org/pdf/2102.04925)
6. \[ICLR-DPML 2021\] **FedGraphNN: A Federated Learning System and Benchmark for Graph Neural Networks.** [paper](https://arxiv.org/pdf/2104.07145) [code](https://github.com/FedML-AI/FedGraphNN)
7. \[Arxiv 2021\] **FL-AGCNS: Federated Learning Framework for Automatic Graph Convolutional Network Search.** [paper](https://arxiv.org/pdf/2104.04141)
8. \[CVPR 2021\] **Cluster-driven Graph Federated Learning over Multiple Domains.** [paper](https://arxiv.org/pdf/2104.14628)
9. \[Arxiv 2021\] **FedGL: Federated Graph Learning Framework with Global Self-Supervision.** [paper](https://arxiv.org/pdf/2105.03170)
10. \[AAAI 2022\] **SpreadGNN: Serverless Multi-task Federated Learning for Graph Neural Networks.** [paper](https://arxiv.org/pdf/2106.02743)
12. \[KDD 2021\] **Cross-Node Federated Graph Neural Network for Spatio-Temporal Data Modeling.** [paper](https://arxiv.org/pdf/2106.05223) [code](https://github.com/mengcz13/KDD2021_CNFGNN)
13. \[Arxiv 2021\] **A Vertical Federated Learning Framework for Graph Convolutional Network.** [paper](https://arxiv.org/pdf/2106.11593)
14. \[NeurIPS 2021\] **Federated Graph Classification over Non-IID Graphs.** [paper](https://arxiv.org/pdf/2106.13423)
15. \[NeurIPS 2021\] **Subgraph Federated Learning with Missing Neighbor Generation.** [paper](https://arxiv.org/pdf/2106.13430)
16. \[CIKM 2021\] **Differentially Private Federated Knowledge Graphs Embedding.** [paper](https://arxiv.org/pdf/2105.07615) [code](https://github.com/HKUST-KnowComp/FKGE)
17. \[MICCAI Workshop 2021\] **A Federated Multigraph Integration Approach for Connectional Brain Template Learning.** [paper](https://link.springer.com/chapter/10.1007/978-3-030-89847-2_4)
18. \[TPDS 2021] **FedGraph: Federated Graph Learning with Intelligent Sampling.** [paper](https://ieeexplore.ieee.org/abstract/document/9606516/) 
19. [ACM TIST 2021] **Federated Social Recommendation with Graph Neural Network** [paper](https://arxiv.org/pdf/2111.10778)
20. [CISS 2022] **Decentralized Graph Federated Multitask Learning for Streaming Data** [paper](https://doi.org/10.1109/CISS53076.2022.9751160)
21. [JBHI 2022] **Dynamic Neural Graphs Based Federated Reptile for Semi-Supervised Multi-Tasking in Healthcare Applications** [paper](https://ieeexplore.ieee.org/document/9648036)
22. [CIKM Workshop 2022] **FedGCN: Convergence and Communication Tradeoffs in Federated Training of Graph Convolutional Networks** [paper](https://arxiv.org/abs/2201.12433) [code](https://github.com/yh-yao/FedGCN)

### Algorithm （算法文章）
1. \[IJCKG 2021\] **FedE: Embedding Knowledge Graphs in Federated Setting.** [paper](https://dl.acm.org/doi/abs/10.1145/3502223.3502233) [code](https://github.com/AnselCmy/FedE)
2. \[Arxiv 2020\] **Improving Federated Relational Data Modeling via Basis Alignment and Weight Penalty.** [paper](https://arxiv.org/pdf/2011.11369)
3. \[CIKM 2021\] **Federated Knowledge Graphs Embedding.**[paper](https://arxiv.org/pdf/2105.07615)
4. \[Arxiv 2021\] **Leveraging a Federation of Knowledge Graphs to Improve Faceted Search in Digital Libraries.** [paper](https://arxiv.org/pdf/2107.05447)
5. \[ACL Workshop 2022\] **Efficient Federated Learning on Knowledge Graphs via Privacy-preserving Relation Embedding Aggregation.** [paper](https://arxiv.org/abs/2203.09553) [code](https://github.com/taokz/FedR)
6. \[IJCAI 2022\] **Meta-Learning Based Knowledge Extrapolation for Knowledge Graphs in the Federated Setting.** [paper](https://arxiv.org/abs/2205.04692) [code](https://github.com/zjukg/MaKEr)

## Private Graph Neural Networks
1. \[IEEE Big Data 2019\] **A Graph Neural Network Based Federated Learning Approach by Hiding Structure.** [paper](https://www.researchgate.net/profile/Shijun_Liu3/publication/339482514_SGNN_A_Graph_Neural_Network_Based_Federated_Learning_Approach_by_Hiding_Structure/links/5f48365d458515a88b790595/SGNN-A-Graph-Neural-Network-Based-Federated-Learning-Approach-by-Hiding-Structure.pdf)
2. \[Arxiv 2020\] **Locally Private Graph Neural Networks.** [paper](https://arxiv.org/pdf/2006.05535)
3. \[Arxiv 2021\] **Privacy-Preserving Graph Convolutional Networks for Text Classification.** [paper](https://arxiv.org/pdf/2102.09604)
4. \[Arxiv 2021\] **GraphMI: Extracting Private Graph Data from Graph Neural Networks.** [paper](https://arxiv.org/pdf/2106.02820)
5. \[Arxiv 2021\] **Towards Representation Identical Privacy-Preserving Graph Neural Network via Split Learning.** [paper](https://arxiv.org/abs/2107.05917)


## Datasets（数据集）
1. \[IEEE TNNLS 2020\] **A Comprehensive Survey on Graph Neural Networks.** [paper](https://arxiv.org/pdf/1901.00596)
2. \[IEEE TKDE 2020\] **Deep Learning on Graphs: A Survey.** [paper](https://arxiv.org/pdf/1812.04202.pdf%E3%80%82)
3. \[AI Open\] **Graph Neural Networks: A Review of Methods and Applications.** [paper](https://www.sciencedirect.com/science/article/pii/S2666651021000012)
4. \[ArXiv 2021\] **Graph Neural Networks in Network Neuroscience.** [paper](https://arxiv.org/pdf/2106.03535.pdf) -- [GitHub repo of all reviewed papers](https://github.com/basiralab/GNNs-in-Network-Neuroscience)

