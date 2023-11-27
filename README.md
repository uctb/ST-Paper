# Spatio-Temporal Prediction Paper

## 2023

### KDD 2023

#### 1. Pattern Expansion and Consolidation on Evolving Graphs for Continual Traffic Prediction

**Author**: Binwu Wang, Yudong Zhang, Xu Wang, Pengkun Wang, Zhengyang Zhou, Lei Bai, Yang Wang

**Summary**: This paper introduces PECPM, a Pattern Expansion and Consolidation based on Pattern Matching framework, addressing the challenge of predicting traffic flow on expanding networks by continually updating and expanding a pattern bank through pattern matching, enabling efficient and effective traffic flow prediction without historical graph data access.

**Abstract**: Recently, spatiotemporal graph convolutional networks are becoming popular in the field of traffic flow prediction and significantly improve prediction accuracy. However, the majority of existing traffic flow prediction models are tailored to static traffic networks and fail to model the continuous evolution and expansion of traffic networks. In this work, we move to investigate the challenge of traffic flow prediction on an expanding traffic network. And we propose an efficient and effective continual learning framework to achieve continuous traffic flow prediction without the access to historical graph data, namely Pattern Expansion and Consolidation based on Pattern Matching based (PECPM). Specifically, we first design a pattern bank based on pattern matching to store representative patterns of the road network. With the expansion of the road network, the model configured with such a bank module can achieve continuous traffic prediction by effectively managing patterns stored in the bank. The core idea is to continuously update new patterns while consolidating learned ones. Specifically, we design a pattern expansion mechanism that can detect evolved and new patterns from the updated network, then these unknown patterns are expanded into the pattern bank to adapt to the updated road network. Additionally, we propose a pattern consolidation mechanism that includes both a bank preservation mechanism and a pattern traceability mechanism. This can effectively consolidate the learned patterns in the bank without requiring access to detailed historical graph data. We construct experiments on real-world traffic datasets to demonstrate the competitive performance, superior efficiency, and strong generalization ability of PECPM.



### WWW 2023





