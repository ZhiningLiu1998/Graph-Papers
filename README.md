> Template: | ConfName | PaperTitle | [[pdf]()] [[code]()] |

Contents
- [Fair Graph Mining](#fair-graph-mining)
  - [Degree-related bias](#degree-related-bias)
  - [Class-related bias](#class-related-bias)
  - [Supervision-related bias](#supervision-related-bias)
- [Graph Learning with Weak Supervision](#graph-learning-with-weak-supervision)
- [Graph Neural Network Architecture](#graph-neural-network-architecture)
- [Graph Anomaly Detection](#graph-anomaly-detection)
- [Graph Data Augmentation](#graph-data-augmentation)
- [Graph Uncertainty](#graph-uncertainty)
- [Graph Contrastive Learning](#graph-contrastive-learning)
- [Spatio-temporal Graph Mining](#spatio-temporal-graph-mining)


## Fair Graph Mining

### Degree-related bias 

| Venue   | Title                                                                              | Links                                                                                        |
| ------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| WWW'22  | Rawlsgcn: Towards rawlsian difference principle on graph convolutional network     | [[pdf](https://arxiv.org/pdf/2202.13547v1.pdf)] [[code](https://github.com/jiank2/RawlsGCN)] |
| CIKM'20 | Investigating and mitigating degree-related biases in graph convoltuional networks | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3340531.3411872)]                                  |

### Class-related bias

| Venue      | Title                                                                                                                                | Links                                                                                                        |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| ICML'22    | TAM: Topology-Aware Margin Loss for Class-Imbalanced Node Classification                                                             | [[pdf](https://proceedings.mlr.press/v162/song22a/song22a.pdf)] [[code](https://github.com/Jaeyun-Song/TAM)] |
| ICLR'22    | GraphENS: Neighbor-Aware Ego Network Synthesis for Class-Imbalanced Node Classification                                              | [[pdf](https://openreview.net/pdf?id=MXEl7i-iru)] [[code](https://github.com/JoonHyung-Park/GraphENS)]       |
| CIKM'22    | LTE4G: Long-Tail Experts for Graph Neural Networks                                                                                   | [[pdf](https://arxiv.org/pdf/2208.10205.pdf)] [[code](https://github.com/SukwonYun/LTE4G)]                   |
| arXiv'21   | GraphMixup: Improving Class-Imbalanced Node Classification on Graphs by Self-supervised Context Prediction                           | [[pdf](https://arxiv.org/pdf/2106.11133v1.pdf)]                                                              |
| NeurIPS'21 | Topology-Imbalance Learning for Semi-Supervised Node Classification [[中文博客](https://zhuanlan.zhihu.com/p/561261334)]             | [[pdf](https://arxiv.org/pdf/2110.04099v1.pdf)] [[code](https://github.com/victorchen96/renode)]             |
| WSDM'21    | GraphSMOTE: Imbalanced Node Classification on Graphs with Graph Neural Networks [[中文博客](https://zhuanlan.zhihu.com/p/561260176)] | [[pdf](https://arxiv.org/pdf/2103.08826v1.pdf)] [[code](https://github.com/TianxiangZhao/GraphSmote)]        |
| IJCAI'20   | Multi-Class Imbalanced Graph Convolutional Network Learning                                                                          | [[pdf](https://par.nsf.gov/servlets/purl/10199469)]                                                          |
| J MIA      | RA-GCN: Graph Convolutional Network for Disease Prediction Problems with Imbalanced Data                                             | [[pdf](https://arxiv.org/pdf/2103.00221v3.pdf)]                                                              |

### Supervision-related bias

| Venue      | Title                                                                          | Links                                                                                                                                                       |
| ---------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| NeurIPS'21 | Shift-Robust GNNs: Overcoming the Limitations of Localized Graph Training Data | [[pdf](https://proceedings.neurips.cc/paper/2021/file/eb55e369affa90f77dd7dc9e2cd33b16-Paper.pdf)] [[code](https://github.com/GentleZhu/Shift-Robust-GNNs)] |


## Graph Learning with Weak Supervision

- https://github.com/kaize0409/awesome-few-shot-gnn

| Venue   | Title                                                                                                  | Links                                                                                                                            |
| ------- | ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| AAAI'20 | Multi-Stage Self-Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes | [[pdf](https://zhouchenlin.github.io/Publications/2020-AAAI-M3S.pdf)]                                                            |
| arXiv   | Toward Robust Graph Semi-Supervised Learning against Extreme Data Scarcity                             | [[pdf](https://arxiv.org/pdf/2208.12422.pdf)]                                                                                    |
| WSDM'23 | Few-shot Node Classification with Extremely Weak Supervision                                           | [[pdf](https://arxiv.org/pdf/2301.02708.pdf)] [[code](https://github.com/SongW-SW/X-FNC)]                                        |
| ICDM'22 | Generalized Few-Shot Node Classification                                                               | [[pdf](https://www.public.asu.edu/~kding9/pdf/Zhe_FewShotClassification_ICDM22.pdf)] [[code](https://github.com/pricexu/STAGER)] |


## Graph Neural Network Architecture

| Venue   | Title                                    | Links                                                     |
| ------- | ---------------------------------------- | --------------------------------------------------------- |
| ICML'19 | Simplifying Graph Convolutional Networks | [[pdf](http://proceedings.mlr.press/v97/wu19e/wu19e.pdf)] |

## Graph Anomaly Detection

| Venue   | Title                                                                         | Links                                                                                                                                                                                                                         |
| ------- | ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TKDE'21 | A Comprehensive Survey on Graph Anomaly Detection with Deep Learning          | [[pdf](https://arxiv.org/pdf/2106.07178v5.pdf)] [[code](https://github.com/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection)]                                                                                               |
| ICDM'21 | FRAUDRE: Fraud Detection Dual-Resistant to Graph Inconsistency and Imbalance  | [[pdf](https://ieeexplore.ieee.org/iel7/9678506/9678989/09679178.pdf?casa_token=u388Zhq6ExwAAAAA:nzpXPJ8mfR45579H4tyiGAjlfxSrh2LukB9BRQYXKBNzMIGe0RAAJZNfQ5mnUT-0W3vKOJin-A)] [[code](https://github.com/GeZhangMQ/FRAUDRE_)] |
| WWW'21  | Pick and Choose: A GNN-based Imbalanced Learning Approach for Fraud Detection | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3442381.3449989)] [[code](https://github.com/PonderLY/PC-GNN)]                                                                                                                      |
| WWW'21  | Few-shot Network Anomaly Detection via Cross-network Meta-learning            | [[pdf](https://arxiv.org/pdf/2102.11165v1.pdf)] [[code](https://github.com/kaize0409/Meta-GDN_AnomalyDetection)]                                                                                                              |

## Graph Data Augmentation

- https://github.com/kaize0409/awesome-graph-data-augmentaion

| Venue    | Title                                                                            | Links                                                                                                                 |
| -------- | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| arXiv'22 | Graph Data Augmentation for Graph Machine Learning: A Survey                     | [[pdf](https://arxiv.org/pdf/2202.08871v1.pdf)] [[code](https://github.com/zhao-tong/graph-data-augmentation-papers)] |
| KDD'22   | COSTA: Covariance-Preserving Feature Augmentation for Graph Contrastive Learning | [[pdf](https://arxiv.org/pdf/2206.04726v2.pdf)] [[code](https://github.com/yifeiacc/COSTA)]                           |

## Graph Uncertainty

| Venue  | Title                                                                      | Links                                                                                                                                                                |
| ------ | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| KDD'22 | JuryGCN: Quantifying Jackknife Uncertainty on Graph Convolutional Networks | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3534678.3539286?casa_token=AxaBEu59ZI4AAAAA:2sV37drJUdBybc9z1mCnh3YZMD9MMUBlqRVTrTZTOaTKQHGLySycFjSFLElglFqWpI_talPfJEzp)] |

## Graph Contrastive Learning

| Venue    | Title                                                           | Links                                                                                                 |
| -------- | --------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| IJCAI'21 | CuCo: Graph Representation with Curriculum Contrastive Learning | [[pdf](https://www.ijcai.org/proceedings/2021/0317.pdf)] [[code](https://github.com/BUPT-GAMMA/CuCo)] |


## Spatio-temporal Graph Mining

| Venue            | Title                                                                                                  | Links                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| CSUR'18 (Survey) | Spatio-temporal data mining: A survey of problems and methods                                          | [[pdf](https://dl.acm.org/doi/pdf/10.1145/3161602)]                                                       |
| CIKM'21 (Survey) | DL-Traff: Survey and Benchmark of Deep Learning Models for Urban Traffic Prediction                    | [[pdf](https://arxiv.org/pdf/2108.09091v1.pdf)] [[code](https://github.com/deepkashiwa20/dl-traff-graph)] |
| AAAI'21          | Hierarchical Graph Convolution Network for Traffic Forecasting                                         | [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/16088/15895)]                                     |
| AAAI'21          | Spatial-temporal fusion graph neural networks for traffic flow forecasting                             | [[pdf](https://arxiv.org/pdf/2012.09641v2.pdf)] [[code](https://github.com/MengzhangLI/STFGNN)]           |
| WWW'21           | Network of Tensor Time Series                                                                          | [[pdf](https://arxiv.org/pdf/2102.07736v3.pdf)] [[code](https://github.com/baoyujing/NET3)]               |
| IJCAI'18         | STGCN: Spatio-temporal graph convolutional networks: a deep learning framework for traffic forecasting | [[pdf](https://arxiv.org/pdf/1709.04875v4.pdf)] [[code](https://github.com/VeritasYin/STGCN_IJCAI-18)]    |
| ICLR'18          | DCRNN: Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting               | [[pdf](https://arxiv.org/pdf/1707.01926v3.pdf)] [[code](https://github.com/liyaguang/DCRNN)]              |
