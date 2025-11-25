# A Survey on Deep Learning for Travel Time Estimation: Methods, Trends, Applications, and Future Directions

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![Code](https://img.shields.io/badge/Code-python-purple)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

✨ A Detailed & Curated Survey on Deep Learning for Travel Time Estimation (TTE) and Estimated Time of Arrival (ETA).

搜集/汇总有关 **旅行时间估计 (Travel Time Estimation, TTE)** 和 **预计到达时间 (Estimated Time of Arrival, ETA)** 的相关【学术界】和【工业界 (滴滴、百度、高德 & 谷歌地图等等)】的最新研究成果与进展。

- ① 论文大多来自顶刊顶会或CS-Q1主流期刊，整理各种**交通+轨迹数据集**，欢迎小伙伴们补充+交流~
- ② 综述撰写中，**arXiv可见将通知，整理不易，请勿🔶侵权©️~** 
- ③ **Updating 持续更新中✅~**
  
⭐ **本仓库始建于**【2024-9-27号】, 截止【2024-11-5号】, 本仓库共整理了 **49篇高质量论文** (涉及旅行时间估计、时空轨迹挖掘、时空图学习方法、智能交通与智慧城市等) + **20个交通+轨迹数据集**! ⭐
  
## Table of Contents

- [What is TTE or ETA?](#what-is-tte-or-eta)
- [Relationship Between TTE and Other SpatioTemporal Tasks](#relationship-between-tte-and-other-spatiotemporal-tasks)
  - [Attention](#attention)
- [Route-based Researches](#route-based-researches)
  - [2024 year with 7 papers](#2024-year-with-7-papers)
  - [2023 year with 10 papers](#2023-year-with-10-papers)
  - [2022 year with 10 papers](#2022-year-with-10-papers)
  - [2021 year with 3 papers](#2021-year-with-3-papers)
  - [2020 year with 6 papers](#2020-year-with-6-papers)
  - [2019 year with 3 papers](#2019-year-with-3-papers)
  - [2018 year with 3 papers](#2018-year-with-3-papers)
- [OD-based Researches](#od-based-researches)
  - [From 2018 to 2023 with 7 papers](#from-2018-to-2023-with-7-papers)
- [Summary List of Ten Open Source Models](#summary-list-of-ten-open-source-models)
- [Proposed TTE Models by DiDi and Baidu](#proposed-tte-models-by-didi-and-baidu)
- [Open Source Traffic and Trajectory Datasets](#open-source-traffic-and-trajectory-datasets)
  - [Top 10 Popular Datasets](#top-10-popular-datasets)
  - [Other Datasets](#other-datasets)
- [Related Resources](#related-resources)

  
## What is TTE or ETA?
- The popularity of location technology has produced massive trajectory data of moving vehicles, such as the driving trajectories of taxis, buses, private cars, and other automobiles.
- ***Travel time estimation (TTE)***, also known as the ***Estimated Time of Arrival (ETA)***, predicts the actual travel duration time of the driving route and assists the driver in planning the route and avoiding congested road segments.
- It is significant in traffic management, carpooling, vehicle dispatching, and other location-based service (LBS) applications.
  
<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig1_TTE+ETA.png"/>
</p>
<p align = "center">
<b>Figure 1. Illustration of Travel-Time-Estimation (TTE) & Estimated-Time-of-Arrival (ETA). </b> 
</p>

## Relationship Between TTE and Other SpatioTemporal Tasks
- **(1) Traffic Imputation**: Ensures the completeness of traffic data and enhances the predictive performance of traffic forecasting models.  
- **(2) Road Network Representation Learning**: Captures the spatial and topological relationships between road segments, improving the accuracy of traffic prediction.  
- **(3) Traffic Prediction**: Provides dynamic and real-time traffic conditions for travel time estimation.  
- **(4) Travel Time Estimation**: Infers the estimated time of arrival and plans routes while avoiding congestion for given origin-destination pairs. It is widely applied in navigation systems, route planning, ride-hailing services, and more.

<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig_ITS.png" width="600"/>
</p>
<p align = "center">
<b>Figure 2. Relationship Between TTE and Other SpatioTemporal Tasks. </b> 
</p>

- Overall, these tasks collectively form the critical components of **Intelligent Transportation Systems (ITS)**. They are interdependent and complementary, working together to enhance urban transportation networks' overall efficiency.


### Attention
- Subsequent list format: **[Model abbreviation]--[Paper title]--[DOI link]--[Github]**

## Route-based Researches

### 2024 year with 7 papers

#### TITS 2024
* [GMM] Improving Urban Travel Time Estimation Using Gaussian Mixture Models [[paper1](https://doi.org/10.1109/TITS.2024.3390792)] 
* [MulT-TTE] Multi-Faceted Route Representation Learning for Travel Time Estimation [[paper2](https://doi.org/10.1109/TITS.2024.3371071)] [[code](https://github.com/TXLiao/MulT-TTE)]
* [KDTTE] Knowledge Distillation for Travel Time Estimation [[paper3](https://doi.org/10.1109/TITS.2024.3374325)]
  
#### IoTJ 2024
* [GT-TTE] GT-TTE: Modeling Trajectories as Graphs for Travel Time Estimation [[paper4](https://doi.org/10.1109/JIOT.2024.3417432)]

#### ESWA 2024
* [DMTL] An Adaptive Deep Multi-task Learning Approach for Citywide Travel Time Collaborative Estimation [[paper5](https://doi.org/10.1016/j.eswa.2023.123009)]

#### INFU 2024
* [DMN] A Deep Multimodal Network for Multi-task Trajectory Prediction [[paper6](https://doi.org/10.1016/j.inffus.2024.102597)]

#### WWW 2024
* [JGRM] More Than Routing: Joint GPS and Route Modeling for Refine Trajectory Representation Learning [[paper7](https://doi.org/10.1145/3589334.3645644)] [[code](https://github.com/mamazi0131/JGRM)]

### 2023 year with 10 papers

#### TITS 2023
* [MT-STAN] When Will We Arrive? A Novel Multi-Task Spatio-Temporal Attention Network Based on Individual Preference for Estimating Travel Time [[paper8](https://doi.org/10.1109/TITS.2023.3276916)] [[code](https://github.com/zouguojian/Travel-time-prediction)] 
* [RTAG] Travel Time Distribution Estimation by Learning Representations Over Temporal Attributed Graphs [[paper9](https://doi.org/10.1109/TITS.2023.3247884)]

#### TKDE 2023
* [DeepTTDE] Citywide Estimation of Travel Time Distributions With Bayesian Deep Graph Learning [[paper10](https://doi.org/10.1109/TKDE.2021.3117986)]
  
#### ACM-TIST 2023
* [Auto-STDGCN] Dual Graph Convolution Architecture Search for Travel Time Estimation [[paper11](https://doi.org/10.1145/3591361)]
  
#### ESWA 2023
* [HLGST] HLGST: Hybrid Local–global Spatio-temporal Model for Travel Time Estimation Using Siamese Graph Convolutional With Triplet Networks [[paper12](https://doi.org/10.1016/j.eswa.2023.120502)]

#### ICDE 2023
* [START] Self-supervised Trajectory Representation Learning with Temporal Regularities and Travel Semantics [[paper13](https://doi.org/10.1109/ICDE55515.2023.00070)] [[code](https://github.com/aptx1231/START)] 

#### KDD 2023
* [ProbTTE] Uncertainty-Aware Probabilistic Travel Time Prediction for On-Demand Ride-Hailing at DiDi [[paper14](https://doi.org/10.1145/3580305.3599925)]

#### CIKM 2023
* [GBTTE] GBTTE: Graph Attention Network Based Bus Travel Time Estimation [[paper15](https://doi.org/10.1145/3583780.3614730)]

#### IJCNN 2023
* [SGED-Net] SGED-Net: A Self-organizing Graph Embedding Deep Network for Travel Time Estimation [[paper16](https://doi.org/10.1109/IJCNN54540.2023.10191790)]
* [TCPSG] Triplet-contrastive Periodical Siamese Graph Networks for Travel Time Estimation [[paper17](https://doi.org/10.1109/IJCNN54540.2023.10191875)]
  
### 2022 year with 10 papers

#### TITS 2022
* [Du-Bus] Du-Bus: A Realtime Bus Waiting Time Estimation System Based On Multi-Source Data [[paper18](https://doi.org/10.1109/TITS.2022.3210170)]
* [CoDriver-ETA] CoDriver ETA: Combine Driver Information in Estimated Time of Arrival by Driving Style Learning Auxiliary Task [[paper19](https://doi.org/10.1109/TITS.2020.3040386)]
* [CatETA] CatETA: A Categorical Approximate Approach for Estimating Time of Arrival [[paper20](https://doi.org/10.1109/TITS.2022.3207894)]
* [CTTUE] Cross-Area Travel Time Uncertainty Estimation From Trajectory Data: A Federated Learning Approach [[paper21](https://doi.org/10.1109/TITS.2022.3203457)]
* [CTTE] CTTE: Customized Travel Time Estimation via Mobile Crowdsensing [[paper22](https://doi.org/10.1109/TITS.2022.3160468)]
* [STTE] Multi-Semantic Path Representation Learning for Travel Time Estimation [[paper23](https://doi.org/10.1109/TITS.2021.3119887)]
* [MetaTTE] Fine-Grained Trajectory-Based Travel Time Estimation for Multi-City Scenarios Based on Deep Meta-Learning [[paper24](https://doi.org/10.1109/TITS.2022.3145382)] [[code](https://github.com/morningstarwang/MetaTTE)] 

#### TKDE 2022
* [TTPNet] TTPNet: A Neural Network for Travel Time Prediction Based on Tensor Decomposition and Graph Embedding [[paper25](https://doi.org/10.1109/TKDE.2020.3038259)] [[code](https://github.com/YibinShen/TTPNet)] 

#### FGCS 2022
* [STGNN-TTE] STGNN-TTE: Travel Time Estimation via Spatial-Temporal Graph Neural Network [[paper26](https://doi.org/10.1016/j.future.2021.07.012)]

#### KDD 2022
* [HierETA] Interpreting Trajectories from Multiple Views: A Hierarchical Self-Attention Network for Estimating the Time of Arrival [[paper27](https://doi.org/10.1145/3534678.3539051)] [[code](https://github.com/YuejiaoGong/HierETA)] 

### 2021 year with 3 papers

#### IEEE letter 2021
* [GraphTTE] GraphTTE: Travel Time Estimation Based on Attention-Spatiotemporal Graphs [[paper28](https://doi.org/10.1109/LSP.2020.3048849)]

#### CIKM 2021
* [ETA-GNN] ETA Prediction with Graph Neural Networks in Google Maps [[paper29](https://doi.org/10.1145/3459637.3481916)]

#### KDD 2021
* [SSML] SSML: Self-Supervised Meta-Learner for En Route Travel Time Estimation at Baidu Maps [[paper30](https://doi.org/10.1145/3447548.3467060)]

### 2020 year with 6 papers

#### INS 2020
* [TP-SCF] Learning Heterogeneous Traffic Patterns for Travel Time Prediction of Bus Journeys [[paper31](https://doi.org/10.1016/j.ins.2019.10.073)]

#### TVT 2020
* [Hybrid] Freeway Travel Time Prediction Using Deep Hybrid Model – Taking Sun Yat-Sen Freeway as an Example [[paper32](https://doi.org/10.1109/TVT.2020.2999358)]

#### TII 2020
* [Nei-TTE] Nei-TTE: Intelligent Traffic Time Estimation Based on Fine-Grained Time Derivation of Road Segments for Smart City [[paper33](https://doi.org/10.1109/TII.2019.2943906)]

#### KDD 2020
* [HetETA] HetETA: Heterogeneous Information Network Embedding for Estimating Time of Arrival [[paper34](https://doi.org/10.1145/3394486.3403294)] [[code](https://github.com/didi/heteta)]
* [CompactETA] CompactETA: A Fast Inference System for Travel Time Prediction [[paper35](https://doi.org/10.1145/3394486.3403386)]
* [ConSTGAT] ConSTGAT: Contextual Spatial-Temporal Graph Attention Network for Travel Time Estimation at Baidu Maps [[paper36](https://doi.org/10.1145/3394486.3403320)]

### 2019 year with 3 papers

#### WWW 2019
* [DeepGTT] Learning Travel Time Distributions with Deep Generative Model [[paper37](https://doi.org/10.1145/3308558.3313418)] [[code](https://github.com/boathit/deepgtt)]

#### CIKM 2019
* [DeepIST] DeepIST: Deep Image-based Spatio-Temporal Network for Travel Time Estimation [[paper38](https://doi.org/10.1145/3357384.3357870)]

#### IJCAI 2019
* [DeepI2T] Travel Time Estimation without Road Networks: An Urban Morphological Layout Representation Approach [[paper39](https://doi.org/10.24963/ijcai.2019/245)]

### 2018 year with 3 papers

#### KDD 2018
* [WDR] Learning to Estimate the Travel Time [[paper40](https://doi.org/10.1145/3219819.3219900)]

#### IJCAI 2018
* [DeepTravel] DeepTRAVEL: A Neural Network Based Travel Time Estimation Model With Auxiliary Supervision [[paper41](https://doi.org/10.24963/ijcai.2018/508)]

#### AAAI 2018
* [DeepTTE] When will you arrive? Estimating Travel Time Based on Deep Neural Networks [[paper42](https://www.microsoft.com/en-us/research/uploads/prod/2018/01/travel-time-estimation-dnn.pdf)] [[code](https://github.com/UrbComp/DeepTTE)]


## OD-based Researches

### From 2018 to 2023 with 7 papers

#### TKDE 2023
* [MWSL-TTE] Multi-Task Weakly Supervised Learning for Origin-Destination Travel Time Estimation [[paper43](https://doi.org/10.1109/TKDE.2023.3236060)]

#### JAT 2022
* [JSTC] JSTC: Travel Time Prediction With a Joint Spatial-Temporal Correlation Mechanism [[paper44](https://doi.org/10.1155/2022/1213221)]

#### ICASSP 2021
* [FMA-ETA] FMA-ETA: Estimating Travel Time Entirely Based on FFN with Attention [[paper45](https://doi.org/10.1109/ICASSP39728.2021.9414054)]

#### IJCNN 2021
* [ZED-TTE] ZED-TTE: Zone Embedding and Deep neural network based Travel Time Estimation Approach [[paper46](https://doi.org/10.1109/IJCNN52387.2021.9533456)]

#### SIGMOD 2020
* [DeepOD] Effective Travel Time Estimation: When Historical Trajectories over Road Networks Matter [[paper47](https://doi.org/10.1145/3318464.3389771)]

#### ACM-TIST 2019
* [TEMP] A Simple Baseline for Travel Time Estimation using Large-scale Trip Data [[paper48](https://doi.org/10.1145/3293317)]

#### KDD 2018
* [MURAT] Multi-task Representation Learning for Travel Time Estimation [[paper49](https://doi.org/10.1145/3219819.3220033)]

## Summary List of Ten Open Source Models
| NO. | Year | Model | Method | Paper | Code | 
|:--:| :--: | :--: | :--: | :--: | :--: |
| 1 | TITS 2024 | [MulT-TTE] | Transformer, Self-supervised Learning| [[paper](https://doi.org/10.1109/TITS.2024.3371071)] | [[code](https://github.com/TXLiao/MulT-TTE)]|
| 2 | WWW 2024  | [JGRM] | Bi-GRU, Attention, Self-Supervised Learning| [[paper](https://doi.org/10.1145/3589334.3645644)] | [[code](https://github.com/mamazi0131/JGRM)] |
| 3 | TITS 2023 | [MT-STAN] | Bridge/Semantic Attention, Cross-network| [[paper](https://doi.org/10.1109/TITS.2023.3276916)] | [[code](https://github.com/zouguojian/Travel-time-prediction)] |
| 4 | ICDE 2023 | [START] | TPE-GAT, TAT-Enc, Self-Attention| [[paper](https://doi.org/10.1109/ICDE55515.2023.00070)] | [[code](https://github.com/aptx1231/START)] |
| 5 | TITS 2022 | [MetaTTE] | Meta-Learning, Attention| [[paper](https://doi.org/10.1109/TITS.2022.3145382)] | [[code](https://github.com/morningstarwang/MetaTTE)] |
| 6 | TKDE 2022 | [TTPNet] | LSTM, CNN, SDNE, Embedding| [[paper](https://doi.org/10.1109/TKDE.2020.3038259)] | [[code](https://github.com/YibinShen/TTPNet)] |
| 7 | KDD 2022  | [HierETA] | Bi-LSTM, Hierarchical Self-Attention|[[paper](https://doi.org/10.1145/3534678.3539051)]   |[[code](https://github.com/YuejiaoGong/HierETA)] |
| 8 | KDD 2020  | [HetETA] | ChebNet, Gated-CNN, MLP| [[paper](https://doi.org/10.1145/3394486.3403294)] | [[code](https://github.com/didi/heteta)]|
| 9 | WWW 2019  | [DeepGTT] | Deep Generative Model, CNN, Embed| [[paper](https://doi.org/10.1145/3308558.3313418)] | [[code](https://github.com/boathit/deepgtt)] |
| 10| AAAI 2018 | [DeepTTE] | Geo-Conv, LSTM, Attention, Multitask| [[paper](https://www.microsoft.com/en-us/research/uploads/prod/2018/01/travel-time-estimation-dnn.pdf)] | [[code](https://github.com/UrbComp/DeepTTE)] |

## Proposed TTE Models by DiDi and Baidu
- DiDi and Baidu, two leading corporations, have each developed models for Travel Time Estimation (TTE) with the goal of improving the efficiency of intelligent transportation systems (ITS), navigation, route planning, and ride-hailing services.
<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig2_DiDi+Baidu.png"/>
</p>
<p align = "center">
<b>Figure 3. The Technological Development Trends of Two Well-known Companies in the TTE Field. </b> 
</p>

- DiDi's representative approach was the **Wide-Deep-Recurrent (WDR)** model in 2018. This model combines a wide linear model, deep neural networks, and recurrent neural networks to capture both the global statistical information and the local detailed information of a route. Later, by integrating Graph Convolutional Networks (GCNs) and attention mechanisms, **DiDi proposed the HetETA (2020) and HierETA (2022)**.
- Baidu's representative method was the proposal of the **ConSTGAT model** in 2020, an end-to-end neural framework that integrates traffic prediction and contextual information of a route. This model employs a novel graph attention mechanism to fully leverage the joint relationships of spatial and temporal information. Subsequently, building upon ConSTGAT, **Baidu introduced the DuETA (2022) and GBTTE (2023)**, both of which have been deployed on Baidu Maps, handling billions of requests daily.
- **In summary**, DiDi focuses on utilizing a diverse array of features, including route information, traffic conditions, and personalized information. Baidu, in addition to utilizing these features, also places special emphasis on the contextual information of routes, such as the connectivity between adjacent road segments.

## Open Source Traffic and Trajectory Datasets
- Here, we have collected and organized #20 **Trajectory-based datasets** that can be used for **Traffic Prediction (flow, speed, etc.) and Travel Time Estimation (TTE/ETA)** tasks!
  
### Top 10 Popular Datasets
  
| NO.  | Name | Source | Timespan | Description | Web-Link | 
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | Porto | Kaggle| From July 1st, 2013 to June 30th, 2014 | Dataset Size: 1,710,670 trajectories (83,409,386 GPS records, 1.8 GB) of 442 taxis, and Sample Rate is 15 seconds | [[kaggle1](https://www.kaggle.com/competitions/pkdd-15-taxi-trip-time-prediction-ii/code)]✅, [[kaggle2](https://www.kaggle.com/crailtap/taxi-trajectory)]✅ |
| 2 | Chengdu-14 | DataCastle | From August 3rd to 30th, 2014 |Dataset Size: 9,737,557 (DeepTTE) OR 1,540,438 (MetaTTE) trajectories (1.4 billion GPS records) of 14,864 taxis| [[DataCastle](https://challenge.datacastle.cn/v3/cmptDetail.html?id=175)]🔶, [[DeepTTE](https://github.com/UrbComp/DeepTTE)]✅, [[MetaTTE](https://github.com/morningstarwang/MetaTTE)]✅ |
| 3 | Chengdu-16 | DiDi | From October 1st to November 30th, 2016 | Dataset Size: 5,421,666 trajectories of 41,527 taxis, Sample Rate is 2-4 seconds | [[DIDI-GAIA](https://outreach.didichuxing.com/)] 🔶|
| 4 | Xi'an-16   | DiDi | From October 1st to November 30th, 2016 | Dataset Size: 6,518,840 trajectories of 20,053 taxis, Sample Rate is 2-4 seconds | [[DIDI-GAIA](https://outreach.didichuxing.com/)] 🔶|
| 5 | Shenzhen-20 | DiDi | From August 1st to 31st, 2020 | Dataset Size: 8,651,005 trajectories (18.6 GB) of 80,886 taxis which contains 882,389 links/road segments | [[ACM2021-GISCUP](https://www.biendata.xyz/competition/didi-eta/)] 🔶|
| 6 | Q-Traffic-BJ-17 | Baidu | From April 1st to May 31st, 2017 | Dataset Size: comprises 114 million crowd user queries, geographical attributes, and traffic flow of 15,073 road segments | [[BaiduTraffic](https://github.com/JingqingZ/BaiduTraffic)]✅, [[Baidu](https://ai.baidu.com/broad/introduction)]✅ |
| 7 | NYC-taxi-13 | NYC | A complete year From January 1st to December 31st, 2013 | Dataset Size: Trip Data (11.0GB) & Fare Data (7.7GB) | [[Taxi-Trip](http://chriswhong.com/open-data/foiling-nycs-boro-taxi-trip-data/)]✅, [[Foil-NYC-Taxi](http://chriswhong.com/open-data/foil_nyc_taxi/)]✅ |
| 8 | NYC-taxi-16 | NYC | From Jan. 1st to Jun. 30th in 2016 |  Dataset Size: 69,406,520 trajectories (10.1 GB) | [[TLC-Trip](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)]✅ |
| 9 | NYC-bike-20 | Lyft | A complete year From January 1st to December 31st, 2020 |  Lyft ride-sharing company (USA) | [[Tripdata](https://s3.amazonaws.com/tripdata/index.html)]🔶 |
| 10 | OpenPFLOW | OpenPFLOW | A complete year From January 1st to December 31st, 2010 |  Collected 68 million GPS sample points from 617,040 users in Tokyo who used different modes of transportation| [[OpenPFLOW](https://github.com/sekilab/OpenPFLOW)]✅ |

* ✅ — Valid  links, i.e., complete data downloadable.
* 🔶 — Invalid link, i.e., data cannot be downloaded after a certain time. **[If you want to obtain them, Please contact me~]**
  
<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig3_NYC.png" width="600"/>
</p>

<b>Figure 4. GPS Spatial Distribution of Origin-Destination (Pick-ups and Drop-offs) in NYC (From [[SGED-Net](https://doi.org/10.1109/IJCNN54540.2023.10191790)]).</b> 

<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig4_Porto.png" width="700"/>
</p>

<b>Figure 5. GPS Spatial Distribution of Origin-Destination (Pick-ups and Drop-offs) in Porto City (From [[SGED-Net](https://doi.org/10.1109/IJCNN54540.2023.10191790)]).</b> 

### Other Datasets
  
| NO. | Name |  Web-Link | 
| :--: | :--: | :--: |
| 1 | Harbin | [[DeepGTT](https://github.com/boathit/deepgtt)] |
| 2 | Shenyang-19 | [[HetETA](https://github.com/didi/heteta)] |
| 3 | Beijing-13 | [[TTPNet](https://github.com/YibinShen/TTPNet)] |
| 4 | Guangzhou-21 | [[HierETA](https://github.com/YuejiaoGong/HierETA)] |
| 5 | Yinchuan | [[MT-STAN](https://github.com/zouguojian/Travel-time-prediction)] |
| 6 | PeMST | [[PeMS](https://pems.dot.ca.gov)] |
| 7 | Rio de Janeiro | [[BUS1](http://goo.gl/HIuSPX)] |
| 8 | Denmark | [[BUS2](https://github.com/niklascp/bus-arrival-convlstm)] |
| 9 | TaxiBJ-13 | [[DeepST](https://github.com/TolicWang/DeepST/blob/master/data/TaxiBJ/README.md)] |
| 10 | CD | [[CD](https://ieee-dataport.org/documents/travel-time-data-chengdu-road-network)] |

- Visualization of Road Network in Beijing, Chengdu & Xi'an
<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig5_BJ.png"/>
</p>
<p align = "center">
<b>Figure 6. Visualization of Road Network Map in Beijing and the Effect of Regional Clustering at Different Scales. </b> 
</p>

<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig6_CD+XA.png" width="600"/>
</p>
<p align = "center">
<b>Figure 7. Visualization of Road Network Map in Chengdu & Xi'an. </b> 
</p>

## Related Resources

- In addition, you may need some additional tools or industry information to better complete your **Traffic Forecasting or Travel Time Estimation** tasks~

* Fast Map Matching: [[FMM](https://fmm-wiki.github.io/)]
* Baidu PaddlePaddle at Spatial-Temporal Data-Mining: [[PaddlePaddle](https://github.com/PaddlePaddle/Research/tree/master/ST_DM)]
* DiDi Travel Time Index (TTI): [[DIDI-TTI](https://github.com/didi/TrafficIndex)]
* Baidu Map Smart Transportation & China Urban Transport Report: [[Baidu-Smart](https://jiaotong.baidu.com/)]

<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig_DL.png"/>
</p>
<p align = "center">
<b>Figure 8. Milestone Models in the Field of Deep Learning (DL). </b> 
</p>

## Cite
If you feel that this work has been helpful for your research, please cite it as: 

- J. Zuo, Y. Yao and Y. Zhang, "TriDGNet: Triple Feature Encoder-Based Dual Granularity Graph Learning Network for Enhanced Travel Time Estimation," in IEEE Transactions on Intelligent Transportation Systems, doi: https://doi.org/10.1109/TITS.2025.3624395.

or

```tex
@ARTICLE{TriDGNet,
  author={Zuo, Jiankai and Yao, Yuxiang and Zhang, Yaying},
  journal={IEEE Transactions on Intelligent Transportation Systems}, 
  title={TriDGNet: Triple Feature Encoder-Based Dual Granularity Graph Learning Network for Enhanced Travel Time Estimation}, 
  year={2025},
  volume={},
  number={},
  pages={1-15},
  doi={10.1109/TITS.2025.3624395}}

```

Keywords: Intelligent Transportation Systems; Travel Time Estimation; Graph Neural Network; Global Spatial Dependence; Local Contextual Information.











