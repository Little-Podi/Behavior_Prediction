# Behavior Prediction

This repository is a paper digest of multi-agent behavior (motion / trajectory) prediction (forecasting / generation), especially in driving scenes. Papers are listed in alphabetical order of the first character. All links to the papers and codes are freely accessible.



## :star2:Recommendation

### Helpful Learning Resource:thumbsup::thumbsup::thumbsup:

- **MAIR2** ICCV 2021 workshop on Multi-Agent Interaction and Relational Reasoning [[video](https://www.youtube.com/playlist?list=PL6xm03jUOj8IA7OdWnjHXHCSfPWSZEIUS)]



## :bookmark:Benchmarks

### ICCV 2021:tada::tada::tada:

- **WOMD** (Large Scale Interactive Motion Forecasting for Autonomous Driving : The Waymo Open Motion Dataset) [[paper](https://arxiv.org/abs/2104.10133)] [[code](https://github.com/waymo-research/waymo-open-dataset)] [[data](https://waymo.com/open/data/motion/)] [[challenge](https://waymo.com/open/challenges/2023/motion-prediction/)]
  - Scott Ettinger, Shuyang Cheng, Benjamin Caine, Chenxi Liu, Hang Zhao, Sabeek Pradhan, Yuning Chai, Ben Sapp, Charles Qi, Yin Zhou, Zoey Yang, Aurelien Chouard, Pei Sun, Jiquan Ngiam, Vijay Vasudevan, Alexander McCauley, Jonathon Shlens, Dragomir Anguelov



## :bookmark:Approaches

### Preprints

- **CU-aware** (Collaborative Uncertainty Benefits Multi-Agent Multi-Modal Trajectory Forecasting) [[paper](https://arxiv.org/abs/2207.05195)] [[code](https://github.com/MediaBrain-SJTU/Collaborative-Uncertainty)] [~~video~~]
  - Bohan Tang, Yiqi Zhong, Chenxin Xu, Wei-Tao Wu, Ulrich Neumann, Yanfeng Wang, Ya Zhang, Siheng Chen
- **DyGroupNet** (Dynamic-Group-Aware Networks for Multi-Agent Trajectory Prediction with Relational Reasoning) [[paper](https://arxiv.org/abs/2206.13114)] [[code](https://github.com/MediaBrain-SJTU/GroupNet)] [~~video~~]
  - Chenxin Xu, Yuxi Wei, Bohan Tang, Sheng Yin, Ya Zhang, Siheng Chen
- **HDGT** (HDGT: Heterogeneous Driving Graph Transformer for Multi-Agent Trajectory Prediction via Scene Encoding) [[paper](https://arxiv.org/abs/2205.09753)] [[code](https://github.com/OpenPerceptionX/HDGT)] [~~video~~]
  - Xiaosong Jia, Penghao Wu, Li Chen, Hongyang Li, Yu Liu, Junchi Yan
- **MTR++** (MTR++: Multi-Agent Motion Prediction with Symmetric Scene Modeling and Guided Intention Querying) [[paper](https://arxiv.org/abs/2306.17770)] [[code](https://github.com/sshaoshuai/MTR)] [~~video~~]
  - Shaoshuai Shi, Li Jiang, Dengxin Dai, Bernt Schiele

### CVPR 2023:tada::tada::tada:
- **EqMotion** (EqMotion: Equivariant Multi-agent Motion Prediction with Invariant Interaction Reasoning) [[paper](https://arxiv.org/abs/2303.10876)] [[code](https://github.com/MediaBrain-SJTU/EqMotion)] [[video](https://www.youtube.com/watch?v=ROactuGU1YA)]
  - Chenxin Xu, Robby T. Tan, Yuhong Tan, Siheng Chen, Yu Guang Wang, Xinchao Wang, Yanfeng Wang
- **FJMP** (FJMP: Factorized Joint Multi-Agent Motion Prediction over Learned Directed Acyclic Interaction Graphs) [[paper](https://arxiv.org/abs/2211.16197)] [[code](https://github.com/RLuke22/FJMP)] [[video](https://www.youtube.com/watch?v=asmCOhPQuNw)]
  - Luke Rowe, Martin Ethier, Eli-Henry Dykhne, Krzysztof Czarnecki
- **MotionDiffuser** (MotionDiffuser: Controllable Multi-Agent Motion Prediction using Diffusion) [[paper](https://arxiv.org/abs/2306.03083)] [~~code~~] [[video](https://www.youtube.com/watch?v=IfGTZwm1abg)]
  - Chiyu Max Jiang, Andre Cornman, Cheolho Park, Ben Sapp, Yin Zhou, Dragomir Anguelov

### CoRL 2023:tada::tada::tada:
- **JFP** (JFP: Joint Future Prediction with Interactive Multi-Agent Modeling for Autonomous Driving) [[paper&review](https://openreview.net/forum?id=Y42uoIekm5b)] [~~code~~] [~~video~~]
  - Wenjie Luo, Cheolho Park, Andre Cornman, Benjamin Sapp, Dragomir Anguelov

### CVPR 2022:tada::tada::tada:
- **GroupNet** (GroupNet: Multiscale Hypergraph Neural Networks for Trajectory Prediction with Relational Reasoning) [[paper](https://arxiv.org/abs/2204.08770)] [[code](https://github.com/MediaBrain-SJTU/GroupNet)] [~~video~~]
  - Chenxin Xu, Maosen Li, Zhenyang Ni, Ya Zhang, Siheng Chen
- **HiVT** (HiVT: Hierarchical Vector Transformer for Multi-Agent Motion Prediction) [[paper](https://openaccess.thecvf.com/content/CVPR2022/html/Zhou_HiVT_Hierarchical_Vector_Transformer_for_Multi-Agent_Motion_Prediction_CVPR_2022_paper.html)] [[code](https://github.com/ZikangZhou/HiVT)] [~~video~~]
  - Zikang Zhou, Luyao Ye, Jianping Wang, Kui Wu, Kejie Lu
- **M2I** (M2I: From Factored Marginal Trajectory Prediction to Interactive Prediction) [[paper](https://arxiv.org/abs/2202.11884)] [[code](https://github.com/Tsinghua-MARS-Lab/M2I)] [~~video~~]
  - Qiao Sun, Xin Huang, Junru Gu, Brian C. Williams, Hang Zhao

### NeurIPS 2022:tada::tada::tada:
- **IMMA** (Interaction Modeling with Multiplex Attention) [[paper&review](https://openreview.net/forum?id=SeHslYhFx5-)] [[code](https://github.com/sunfanyunn/IMMA)] [~~video~~]
  - Fan-Yun Sun, Isaac Kauvar, Ruohan Zhang, Jiachen Li, Mykel Kochenderfer, Jiajun Wu, Nick Haber
- **MTR** (Motion Transformer with Global Intention Localization and Local Movement Refinement) [[paper&review](https://openreview.net/forum?id=9t-j3xDm7_Q)] [[code](https://github.com/sshaoshuai/MTR)] [~~video~~]
  - Shaoshuai Shi, Li Jiang, Dengxin Dai, Bernt Schiele

### ICLR 2022:tada::tada::tada:
- **Scene Transformer** (Scene Transformer: A Unified Architecture for Predicting Multiple Agent Trajectories) [[paper&review](https://openreview.net/forum?id=Wm3EA5OlHsG)] [[code](https://github.com/Chen-Albert-FENG/SceneTransformer)] [~~video~~]
  - Jiquan Ngiam, Benjamin Caine, Vijay Vasudevan, Zhengdong Zhang, Hao-Tien Lewis Chiang, Jeffrey Ling, Rebecca Roelofs, Alex Bewley, Chenxi Liu, Ashish Venugopal, David Weiss, Ben Sapp, Zhifeng Chen, Jonathon Shlens

### ICRA 2022
- **MultiPath++** (MultiPath++: Efficient Information Fusion and Trajectory Aggregation for Behavior Prediction) [[paper](https://arxiv.org/abs/2111.14973)] [[code](https://github.com/stepankonev/waymo-motion-prediction-challenge-2022-multipath-plus-plus)] [~~video~~]
  - Balakrishnan Varadarajan, Ahmed Hefny, Avikalp Srivastava, Khaled S. Refaat, Nigamaa Nayakanti, Andre Cornman, Kan Chen, Bertrand Douillard, Chi Pang Lam, Dragomir Anguelov, Benjamin Sapp

### CVPR 2021:tada::tada::tada:

- **TrafficSim** (TrafficSim: Learning to Simulate Realistic Multi-Agent Behaviors) [[paper](https://arxiv.org/abs/2101.06557)] [~~code~~] [~~video~~]
  - Simon Suo, Sebastian Regalado, Sergio Casas, Raquel Urtasun

### NeurIPS 2021:tada::tada::tada:

- **CU-based** (Collaborative Uncertainty in Multi-Agent Trajectory Forecasting) [[paper&review](https://openreview.net/forum?id=sO4tOk2lg9I)] [[code](https://github.com/MediaBrain-SJTU/Collaborative-Uncertainty)] [[video](https://www.youtube.com/watch?v=udlu7C0nX8o)]
  - Bohan Tang, Yiqi Zhong, Ulrich Neumann, Gang Wang, Ya Zhang, Siheng Chen

### ICCV 2021:tada::tada::tada:

- **DenseTNT** (DenseTNT: End-to-end Trajectory Prediction from Dense Goal Sets) [[paper](https://arxiv.org/abs/2108.09640)] [[code](https://github.com/Tsinghua-MARS-Lab/DenseTNT)] [~~video~~]
  - Junru Gu, Chen Sun, Hang Zhao

### WACV 2021

- **GraphTCN** (GraphTCN: Spatio-Temporal Interaction Modeling for Human Trajectory Prediction) [[paper](https://arxiv.org/abs/2003.07167)] [~~code~~] [[video](https://www.youtube.com/watch?v=Kq0K5DeBL9g)]
  - Chengxin Wang, Shaofeng Cai, Gary Tan

### CVPR 2020:tada::tada::tada:

- **VectorNet** (VectorNet: Encoding HD Maps and Agent Dynamics from Vectorized Representation) [[paper](https://arxiv.org/abs/2005.04259)] [[code](https://github.com/DQSSSSS/VectorNet)] [~~video~~]
  - Jiyang Gao, Chen Sun, Hang Zhao, Yi Shen, Dragomir Anguelov, Congcong Li, Cordelia Schmid

### NeurIPS 2020:tada::tada::tada:

- **EvolveGraph** (EvolveGraph: Multi-Agent Trajectory Prediction with Dynamic Relational Reasoning) [[paper&review](https://proceedings.neurips.cc/paper/2020/hash/e4d8163c7a068b65a64c89bd745ec360-Abstract.html)] [[code](https://github.com/huanshayun/EvolveGraph_realize)] [[video](https://slideslive.com/38941510/evolvegraph-multiagent-trajectory-prediction-with-dynamic-relational-reasoning)]
  - Jiachen Li, Fan Yang, Masayoshi Tomizuka, Chiho Choi

### ECCV 2020:tada::tada::tada:

- **LaneGCN** (Learning Lane Graph Representations for Motion Forecasting) [[paper](https://arxiv.org/abs/2007.13732)] [[code](https://github.com/uber-research/LaneGCN)] [[video](https://www.youtube.com/watch?v=nxRSZ7t5OW4)]
  - Ming Liang, Bin Yang, Rui Hu, Yun Chen, Renjie Liao, Song Feng, Raquel Urtasun
- **Trajectron++** (Trajectron++: Dynamically-Feasible Trajectory Forecasting With Heterogeneous Data) [[paper](https://arxiv.org/abs/2001.03093)] [[code](https://github.com/StanfordASL/Trajectron-plus-plus)] [~~video~~]
  - Tim Salzmann, Boris Ivanovic, Punarjay Chakravarty, Marco Pavone

### ICCV 2019:tada::tada::tada:

- **Trajectron** (The Trajectron: Probabilistic Multi-Agent Trajectory Modeling With Dynamic Spatiotemporal Graphs) [[paper](https://arxiv.org/abs/1810.05993)] [[code](https://github.com/StanfordASL/Trajectron)] [~~video~~]
  - Boris Ivanovic, Marco Pavone

### CoRL 2019:tada::tada::tada:

- **MultiPath** (MultiPath: Multiple Probabilistic Anchor Trajectory Hypotheses for Behavior Prediction) [[paper](https://arxiv.org/abs/1910.05449)] [~~code~~] [~~video~~]
  - Yuning Chai, Benjamin Sapp, Mayank Bansal, Dragomir Anguelov