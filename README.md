# Deep Learning for Travel Time Estimation (TTE) & Estimated Time of Arrival (ETA): A Survey

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Visits Badge](https://badges.pufler.dev/visits/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA)](https://badges.pufler.dev/visits/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA)

A curated list/survey of/on Deep learning for Travel Time Estimation (TTE) and Estimated Time of Arrival (ETA).

搜集/汇总有关 **旅行时间估计 (Travel Time Estimation, TTE)** 和 **预计到达时间 (Estimated Time of Arrival, ETA)** 的相关【学术界】和【工业界 (滴滴、百度、高德、谷歌地图等等)】的最新研究成果与进展。

- 论文大多来自顶刊顶会或其它Q1主流期刊，欢迎小伙伴们补充+交流~
- **Updating 持续更新中~**

## What is TTE or ETA?
- The popularity of location technology has produced massive trajectory data of moving vehicles, such as the driving trajectories of taxis, buses, private cars, and other automobiles. ***Travel time estimation (TTE)***, also known as the ***Estimated Time of Arrival (ETA)***, predicts the actual travel duration time of the driving route and assists the driver in planning the route and avoiding congested road segments. This is of great significance toward traffic management, carpooling, vehicle dispatching, and other location-based service (LBS) applications.
  
<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig1.png"/>
</p>

## Attention
- Subsequent list format: **[Model abbreviation]--[Paper title]--[DOI link]--[Github]**

# Route-based方向的期刊+顶会论文

## TITS 2024
* [GMM] Improving Urban Travel Time Estimation Using Gaussian Mixture Models [[paper](https://doi.org/10.1109/TITS.2024.3390792)] 
* [MulT-TTE] Multi-Faceted Route Representation Learning for Travel Time Estimation [[paper](https://doi.org/10.1109/TITS.2024.3371071)] [[code](https://github.com/TXLiao/MulT-TTE)]
* [KDTTE] Knowledge Distillation for Travel Time Estimation [[paper](https://doi.org/10.1109/TITS.2024.3374325)]
  
## IoTJ 2024
* [GT-TTE] GT-TTE: Modeling Trajectories as Graphs for Travel Time Estimation [[paper](https://doi.org/10.1109/JIOT.2024.3417432)]

## ESWA 2024
* [DMTL] An Adaptive Deep Multi-task Learning Approach for Citywide Travel Time Collaborative Estimation [[paper](https://doi.org/10.1016/j.eswa.2023.123009)]

## INFU 2024
* [DMN] A Deep Multimodal Network for Multi-task Trajectory Prediction [[paper](https://doi.org/10.1016/j.inffus.2024.102597)]

## WWW 2024
* [JGRM] More Than Routing: Joint GPS and Route Modeling for Refine Trajectory Representation Learning [[paper](https://doi.org/10.1145/3589334.3645644)] [[code](https://github.com/mamazi0131/JGRM)] 

## TITS 2023
* [MT-STAN] When Will We Arrive? A Novel Multi-Task Spatio-Temporal Attention Network Based on Individual Preference for Estimating Travel Time [[paper](https://doi.org/10.1109/TITS.2023.3276916)] [[code](https://github.com/zouguojian/Travel-time-prediction)] 
* [RTAG] Travel Time Distribution Estimation by Learning Representations Over Temporal Attributed Graphs [[paper](https://doi.org/10.1109/TITS.2023.3247884)]

## TKDE 2023
* [DeepTTDE] Citywide Estimation of Travel Time Distributions With Bayesian Deep Graph Learning [[paper](https://doi.org/10.1109/TKDE.2021.3117986)]
  
## ACM-TIST 2023
* [Auto-STDGCN] Dual Graph Convolution Architecture Search for Travel Time Estimation [[paper](https://doi.org/10.1145/3591361)]
  
## ESWA 2023
* [HLGST] HLGST: Hybrid Local–global Spatio-temporal Model for Travel Time Estimation Using Siamese Graph Convolutional With Triplet Networks [[paper](https://doi.org/10.1016/j.eswa.2023.120502)]

## ICDE 2023
* [START] Self-supervised Trajectory Representation Learning with Temporal Regularities and Travel Semantics [[paper](https://doi.org/10.1109/ICDE55515.2023.00070)] [[code](https://github.com/aptx1231/START)] 

## KDD 2023
* [ProbTTE] Uncertainty-Aware Probabilistic Travel Time Prediction for On-Demand Ride-Hailing at DiDi [[paper](https://doi.org/10.1145/3580305.3599925)]

## CIKM 2023
* [GBTTE] GBTTE: Graph Attention Network Based Bus Travel Time Estimation [[paper](https://doi.org/10.1145/3583780.3614730)]

## IJCNN 2023
* [SGED-Net] SGED-Net: A Self-organizing Graph Embedding Deep Network for Travel Time Estimation [[paper](https://doi.org/10.1109/IJCNN54540.2023.10191790)]
* [TCPSG] Triplet-contrastive Periodical Siamese Graph Networks for Travel Time Estimation [[paper](https://doi.org/10.1109/IJCNN54540.2023.10191875)]

## TITS 2022
* [Du-Bus] Du-Bus: A Realtime Bus Waiting Time Estimation System Based On Multi-Source Data [[paper](https://doi.org/10.1109/TITS.2022.3210170)]
* [CoDriver-ETA] CoDriver ETA: Combine Driver Information in Estimated Time of Arrival by Driving Style Learning Auxiliary Task [[paper](https://doi.org/10.1109/TITS.2020.3040386)]
* [CatETA] CatETA: A Categorical Approximate Approach for Estimating Time of Arrival [[paper](https://doi.org/10.1109/TITS.2022.3207894)]
* [CTTUE] Cross-Area Travel Time Uncertainty Estimation From Trajectory Data: A Federated Learning Approach [[paper](https://doi.org/10.1109/TITS.2022.3203457)]
* [CTTE] CTTE: Customized Travel Time Estimation via Mobile Crowdsensing [[paper](https://doi.org/10.1109/TITS.2022.3160468)]
* [STTE] Multi-Semantic Path Representation Learning for Travel Time Estimation [[paper](https://doi.org/10.1109/TITS.2021.3119887)]
* [MetaTTE] Fine-Grained Trajectory-Based Travel Time Estimation for Multi-City Scenarios Based on Deep Meta-Learning [[paper](https://doi.org/10.1109/TITS.2022.3145382)] [[code](https://github.com/morningstarwang/MetaTTE)] 

## TKDE 2022
* [TTPNet] TTPNet: A Neural Network for Travel Time Prediction Based on Tensor Decomposition and Graph Embedding [[paper](https://doi.org/10.1109/TKDE.2020.3038259)] [[code](https://github.com/YibinShen/TTPNet)] 

## FGCS 2022
* [STGNN-TTE] STGNN-TTE: Travel Time Estimation via Spatial-Temporal Graph Neural Network [[paper](https://doi.org/10.1016/j.future.2021.07.012)]

## KDD 2022
* [HierETA] Interpreting Trajectories from Multiple Views: A Hierarchical Self-Attention Network for Estimating the Time of Arrival [[paper](https://doi.org/10.1145/3534678.3539051)] [[code](https://github.com/YuejiaoGong/HierETA)] 

## IEEE letter 2021
* [GraphTTE] GraphTTE: Travel Time Estimation Based on Attention-Spatiotemporal Graphs [[paper](https://doi.org/10.1109/LSP.2020.3048849)]

## CIKM 2021
* [ETA-GNN] ETA Prediction with Graph Neural Networks in Google Maps [[paper](https://doi.org/10.1145/3459637.3481916)]

## KDD 2021
* [SSML] SSML: Self-Supervised Meta-Learner for En Route Travel Time Estimation at Baidu Maps [[paper](https://doi.org/10.1145/3447548.3467060)]

## INS 2020
* [TP-SCF] Learning Heterogeneous Traffic Patterns for Travel Time Prediction of Bus Journeys [[paper](https://doi.org/10.1016/j.ins.2019.10.073)]

## TVT 2020
* [Hybrid] Freeway Travel Time Prediction Using Deep Hybrid Model – Taking Sun Yat-Sen Freeway as an Example [[paper](https://doi.org/10.1109/TVT.2020.2999358)]

## TII 2020
* [Nei-TTE] Nei-TTE: Intelligent Traffic Time Estimation Based on Fine-Grained Time Derivation of Road Segments for Smart City [[paper](https://doi.org/10.1109/TII.2019.2943906)]

## KDD 2020
* [HetETA] HetETA: Heterogeneous Information Network Embedding for Estimating Time of Arrival [[paper](https://doi.org/10.1145/3394486.3403294)] [[code](https://github.com/didi/heteta)]
* [CompactETA] CompactETA: A Fast Inference System for Travel Time Prediction [[paper](https://doi.org/10.1145/3394486.3403386)]
* [ConSTGAT] ConSTGAT: Contextual Spatial-Temporal Graph Attention Network for Travel Time Estimation at Baidu Maps [[paper](https://doi.org/10.1145/3394486.3403320)]

## WWW 2019
* [DeepGTT] Learning Travel Time Distributions with Deep Generative Model [[paper](https://doi.org/10.1145/3308558.3313418)] [[code](https://github.com/boathit/deepgtt)]

## CIKM 2019
* [DeepIST] DeepIST: Deep Image-based Spatio-Temporal Network for Travel Time Estimation [[paper](https://doi.org/10.1145/3357384.3357870)]

## IJCAI 2019
* [DeepI2T] Travel Time Estimation without Road Networks: An Urban Morphological Layout Representation Approach [[paper](https://doi.org/10.24963/ijcai.2019/245)]

## KDD 2018
* [WDR] Learning to Estimate the Travel Time [[paper](https://doi.org/10.1145/3219819.3219900)]

## IJCAI 2018
* [DeepTravel] DeepTRAVEL: A Neural Network Based Travel Time Estimation Model With Auxiliary Supervision [[paper](https://doi.org/10.24963/ijcai.2018/508)]

## AAAI 2018
* [DeepTTE] When will you arrive? Estimating Travel Time Based on Deep Neural Networks [[paper](https://www.microsoft.com/en-us/research/uploads/prod/2018/01/travel-time-estimation-dnn.pdf)] [[code](https://github.com/UrbComp/DeepTTE)]


# OD-based方向的期刊+顶会论文

## TKDE 2023
* [MWSL-TTE] Multi-Task Weakly Supervised Learning for Origin-Destination Travel Time Estimation [[paper](https://doi.org/10.1109/TKDE.2023.3236060)]

## JAT 2022
* [JSTC] JSTC: Travel Time Prediction With a Joint Spatial-Temporal Correlation Mechanism [[paper](https://doi.org/10.1155/2022/1213221)]

## ICASSP 2021
* [FMA-ETA] FMA-ETA: Estimating Travel Time Entirely Based on FFN with Attention [[paper](https://doi.org/10.1109/ICASSP39728.2021.9414054)]

## IJCNN 2021
* [ZED-TTE] ZED-TTE: Zone Embedding and Deep neural network based Travel Time Estimation Approach [[paper](https://doi.org/10.1109/IJCNN52387.2021.9533456)]

## SIGMOD 2020
* [DeepOD] Effective Travel Time Estimation: When Historical Trajectories over Road Networks Matter [[paper](https://doi.org/10.1145/3318464.3389771)]

## ACM-TIST 2019
* [TEMP] A Simple Baseline for Travel Time Estimation using Large-scale Trip Data [[paper](https://doi.org/10.1145/3293317)]

## KDD 2018
* [MURAT] Multi-task Representation Learning for Travel Time Estimation [[paper](https://doi.org/10.1145/3219819.3220033)]

## Summary Table of Open Source Models
|NO. | Year  |  Model  |  Paper  |  Code  | 
|:---|:------|:-------:|--------:|--------:|
|1| TITS 2024 | [MulT-TTE] | [[paper](https://doi.org/10.1109/TITS.2024.3371071)] | [[code](https://github.com/TXLiao/MulT-TTE)]|
|2| WWW 2024  | [JGRM] | [[paper](https://doi.org/10.1145/3589334.3645644)] | [[code](https://github.com/mamazi0131/JGRM)] |
|3| TITS 2023 | [MT-STAN] | [[paper](https://doi.org/10.1109/TITS.2023.3276916)] | [[code](https://github.com/zouguojian/Travel-time-prediction)] |
|4| ICDE 2023 | [START] | [[paper](https://doi.org/10.1109/ICDE55515.2023.00070)] | [[code](https://github.com/aptx1231/START)] |
|5| TITS 2022 | [MetaTTE] | [[paper](https://doi.org/10.1109/TITS.2022.3145382)] | [[code](https://github.com/morningstarwang/MetaTTE)] |
|6| TKDE 2022 | [TTPNet] | [[paper](https://doi.org/10.1109/TKDE.2020.3038259)] | [[code](https://github.com/YibinShen/TTPNet)] |
|7| KDD 2022  | [HierETA] |[[paper](https://doi.org/10.1145/3534678.3539051)]   |[[code](https://github.com/YuejiaoGong/HierETA)] |
|8| KDD 2020  | [HetETA] | [[paper](https://doi.org/10.1145/3394486.3403294)] | [[code](https://github.com/didi/heteta)]|
|9| WWW 2019  | [DeepGTT] | [[paper](https://doi.org/10.1145/3308558.3313418)] | [[code](https://github.com/boathit/deepgtt)] |
|10| AAAI 2018 | [DeepTTE] | [[paper](https://www.microsoft.com/en-us/research/uploads/prod/2018/01/travel-time-estimation-dnn.pdf)] | [[code](https://github.com/UrbComp/DeepTTE)] |

## Proposed TTE-models by [DiDi AI Labs] & [Baidu Inc.]
<p align="center">
<img align="middle" src="https://github.com/JKZuo/Awesome-Travel-Time-Estimation-TTE-ETA/blob/main/fig2.png"/>
</p>

# Updating~ 持续更新中! 












