# Survey of Data Heterogeneous  Federated learning

 > Addressing Skewed Heterogeneity via Federated Prototype Rectification with Personalization
 > Shunxin Guo, Hongsong Wang, Xin Geng et al.  TNNLS, 2024.
## Abstract
Federated learning (FL) is an efficient framework designed to facilitate collaborative model training across multiple distributed devices while preserving user data privacy. A significant challenge of FL is data-level heterogeneity, i.e., skewed or long-tailed distribution of private data. Although various methods have been proposed to address this challenge, most of them assume that the underlying global data are uniformly distributed across all clients. This article investigates data-level heterogeneity FL with a brief review and redefines a more practical and challenging setting called skewed heterogeneous FL (SHFL). Accordingly, we propose a novel federated prototype rectification with personalization (FedPRP) which consists of two parts: federated personalization and federated prototype rectification. The former aims to construct balanced decision boundaries between dominant and minority classes based on private data, while the latter exploits both interclass discrimination and intraclass consistency to rectify empirical prototypes. Experiments on three popular benchmarks show that the proposed approach outperforms current state-of-the-art methods and achieves balanced performance in both personalization and generalization.

![The taxonomy of data heterogeneity of federated learning.](https://github.com/shunxinguo/Survey-of-Data-Heterogeneous-Federated-Learning/blob/main/Survey%20of%20Data%20Heterogeneous%20%20Federated%20learning.png)

## Citation
    @article{guo2024addressing,
    title={Addressing Skewed Heterogeneity via Federated Prototype Rectification With Personalization},
    author={Guo, Shunxin and Wang, Hongsong and Lin, Shuxia and Kou, Zhiqiang and Geng, Xin},
    journal={IEEE Transactions on Neural Networks and Learning Systems},
    year={2024},
    publisher={IEEE}
    }
    
## Relevant Projects
[1] Shunxin Guo, Hongsong Wang, Xin Geng. Dynamic heterogeneous federated learning with multi-level prototypes[J]. Pattern Recognition, 2024, 153: 110542. [PDF](https://arxiv.org/pdf/2312.09881)

    @article{guo2024dynamic,
    title={Dynamic heterogeneous federated learning with multi-level prototypes},
    author={Guo, Shunxin and Wang, Hongsong and Geng, Xin},
    journal={Pattern Recognition},
    volume={153},
    pages={110542},
    year={2024},
    publisher={Elsevier}
    }
