# congestion-control-algorithm
A algorithm demo is made up to accomplish the congestion-controlling for the data center. 😆
Developed by the graduating students from Xidian University, Shaanxi ,Xi'an, China, Sept, 2023.

## Introduction
A data center is a supporting platform for applications such as cloud computing, big data, and deep learning. On the one hand, a wide range of online applications, including web search, online transactions, advertising systems, and recommendation systems, have promoted the development of cloud computing and data centers. Therefore, the data center network needs to meet three conditions at the same time: first, to ensure the delay of small flows; second, to quickly absorb burst traffic; third, to ensure the bandwidth utilization of large flows. The traditional congestion control mechanism applied to the Internet cannot meet the above requirements at the same time, so it is necessary to design a congestion control algorithm with high responsiveness and sufficient bandwidth utilization.

This project is based on the data center network, and requires the use of the ns3 network simulator to simulate the network environment and build the basic network topology (such as fat-tree, spine-leaf and other data center topologies). Then, the existing congestion control algorithms in the current data center network are researched, classified and compared, and novel congestion control strategies are proposed. Finally, a novel congestion control algorithm is deployed on the network topology built by ns3 to realize flexible scheduling and control of traffic.
