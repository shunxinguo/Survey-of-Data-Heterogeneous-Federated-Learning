# Survey of Data Heterogeneous  Federated Learning

 > Addressing Skewed Heterogeneity via Federated Prototype Rectification with Personalization.\
 > Shunxin Guo, Hongsong Wang, Xin Geng et al.  TNNLS, 2024. [PDF](https://arxiv.org/pdf/2408.07966)
## Abstract
Federated learning (FL) is an efficient framework designed to facilitate collaborative model training across multiple distributed devices while preserving user data privacy. A significant challenge of FL is data-level heterogeneity, i.e., skewed or long-tailed distribution of private data. Although various methods have been proposed to address this challenge, most of them assume that the underlying global data are uniformly distributed across all clients. This article investigates data-level heterogeneity FL with a brief review and redefines a more practical and challenging setting called skewed heterogeneous FL (SHFL). Accordingly, we propose a novel federated prototype rectification with personalization (FedPRP) which consists of two parts: federated personalization and federated prototype rectification. The former aims to construct balanced decision boundaries between dominant and minority classes based on private data, while the latter exploits both interclass discrimination and intraclass consistency to rectify empirical prototypes. Experiments on three popular benchmarks show that the proposed approach outperforms current state-of-the-art methods and achieves balanced performance in both personalization and generalization. 

 - [ ] Illustration of data heterogeneous federated learning
![enter image description here](https://github.com/shunxinguo/Survey-of-Data-Heterogeneous-Federated-Learning/blob/main/Illustration%20of%20data%20heterogeneous%20federated%20learning.png)
 
 - [ ] The taxonomy of data heterogeneity of federated learning
![The taxonomy of data heterogeneity of federated learning.](https://github.com/shunxinguo/Survey-of-Data-Heterogeneous-Federated-Learning/blob/main/A%20Taxonomy%20of%20Data%20Heterogeneous%20%20Federated%20learning.jpg)

 - **Class Re-balancing**\
[64] T.-M. H. Hsu, H. Qi, and M. Brown, Federated visual classification with real-world data distribution, in Proc. 16th Eur. Conf. Comput. Vis., 2020, pp. 76–92.\
[65] Z. Tang et al., Data resampling for federated learning with non-IID labels, in Proc. Internation Joint Conf. Artif. Intell., 2021, pp. 1–7.\
[66] T. Qi, F. Wu, L. Lyu, Y. Huang, and X. Xie, FedSampling: A better sampling strategy for federated learning, 2023, arXiv:2306.14245.\
[67] Y. Ding, Y. Xiao, R. Mathews, M. Chen, and L. Zhou, Improved federated learning for handling long-tail words, Tech. Discl. Commons, vol. 62, no. 35, pp. 1–8, 2023.\
[68] P. Qian, Y. Lu, and H. Wang, Long-tailed federated learning via aggregated meta mapping, in Proc. IEEE Int. Conf. Image Process. (ICIP), Oct. 2023, pp. 2010–2014.\
[69] Y. Jiang et al., A secure aggregation for federated learning on long-tailed data, 2023, arXiv:2307.08324.\
[70] L. Zhang, Y. Wu, L. Chen, L. Fan, and A. Nallanathan, Scoring aided federated learning on long-tailed data for wireless IoMT based healthcare system, IEEE J. Biomed. Health Informat., vol. 28, no. 6, pp. 3341–3348, Jun. 2024. \
[71] H. Wang, L. Wang, and J. Shen, Logit calibration for non-IID and long-tailed data in federated learning, in Proc. IEEE Intl. Conf. Parallel Distrib. Process. Appl., Big Data Cloud Comput., Sustain. Comput. Commun., Social Comput. Netw. (ISPA/BDCloud/SocialCom/SustainCom), Dec. 2022, pp. 782–789.\
[72] C. Chen, Y. Liu, X. Ma, and L. Lyu, Calfat: Calibrated federated adversarial training with label skewness, in Proc. Adv. Neural Inf. Process. Syst., vol. 35, 2022, pp. 3569–3581.\
[73] X. Shang, Y. Lu, Y.-M. Cheung, and H. Wang, FEDIC: Federated learning on non-IID and long-tailed data via calibrated distillation, 2022, arXiv:2205.00172.\
[74] D. Yan, J. Wang, Q. Huang, J. Huang, and X. Li, LTNI-FGML: Federated graph machine learning on long-tailed and non-IID data via logit calibration, in Proc. Int. Conf. Artif. Neural Netw., 2023, pp. 486–498.

 - **Knowledge Assistance**\
	 [75] Y. Zeng, L. Liu, L. Liu, L. Shen, S. Liu, and B. Wu, Global balanced experts for federated long-tailed learning, in Proc. IEEE/CVF Int. Conf. Comput. Vis. (ICCV), Oct. 2023, pp. 4815–4825.\
	 [76] X. Shuai, Y. Shen, S. Jiang, Z. Zhao, Z. Yan, and G. Xing, BalanceFL: Addressing class imbalance in long-tail federated learning, in Proc. 21st ACM/IEEE Int. Conf. Inf. Process. Sens. Netw. (IPSN), Jul. 2022, pp. 271–284.
 - **Network Architecture Design**\
	 [26] X. Shang, Y. Lu, G. Huang, and H. Wang, Federated learning on heterogeneous and long-tailed data via classifier re-training with federated features, in Proc. 31st Int. Joint Conf. Artif. Intell., Jul. 2022, pp. 2218–2224.\
	 [27] W. Yang, D. Chen, H. Zhou, F. Meng, J. Zhou, and X. Sun, Integrating local real data with global gradient prototypes for classifier re-balancing in federated long-tailed learning, 2023, arXiv:2301.10394.\
	 [77] J. Wicaksana, Z. Yan, and K.-T. Cheng, FCA: Taming long-tailed federated medical image classification by classifier anchoring, 2023, arXiv:2305.00738.\
	 [78] X. Li, S. Sun, M. Liu, J. Ren, X. Jiang, and T. He, Federated classification tasks in long-tailed data environments via classifier representation adjustment and calibration, Authorea Preprints, vol. 14, no. 8, pp. 1–16, 2023.\
	 [79] Z. Xiao et al., Fed-GraB: Federated long-tailed learning with self-adjusting gradient balancer, 2023, arXiv:2310.07587.
 
 - **Personalized FL**\
	[80] Z. Chen, S. Liu, H. Wang, H. H. Yang, T. Q. S. Quek, and Z. Liu, Towards federated long-tailed learning, 2022, arXiv:2206.14988.\
	[81] Y. Lu, P. Qian, G. Huang, and H. Wang, Personalized federated learning on long-tailed data via adversarial feature augmentation, in Proc. IEEE Int. Conf. Acoust., Speech Signal Process. (ICASSP), Jun. 2023, pp. 1–5.
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
