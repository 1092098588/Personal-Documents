# NSDI 2021 论文总结

### Introduction

总结NSDI2021的论文所涉及的方向

### NSDI 2021

1. 在安全敏感环境（审计）中使用NFV

   > https://www.usenix.org/conference/nsdi21/presentation/liu-guyue

2. 广域网flow管理

   > https://www.usenix.org/conference/nsdi21/presentation/abuzaid

3. When Cloud Storage Meets RDMA （阿里巴巴云存储）

   > https://www.usenix.org/conference/nsdi21/presentation/gao

4. 云-边 流量工程框架（Microsoft）

   > 通过非线性定价方案优化云-边带宽资源分配，降低成本
   >
   > https://www.usenix.org/conference/nsdi21/presentation/singh

5. 边缘端 绕过网路故障处 重新选择路由路径 （故障检测与恢复）

   > The key intuition behind it is that **edge networks** need not rely on BGP to learn of path impairments: they can infer the status of a path by **monitoring transport-layer forward progress**, and then **reroute stalled flows onto healthy paths**. Unlike routing protocols such as BGP, CPR operates at the timescale of round-trip times, providing connection recovery in seconds rather than minutes. By delegating routing responsibilities to the edge hosts themselves, CPR achieves per-connection re-routing protection for all destination prefixes without incurring additional costs reconstructing transport protocol state within the network. Unlike previous multipath-aware transport protocols, CPR is unilaterally deployable and has been running in production at a large edge network for over two years.
   >
   > https://www.usenix.org/conference/nsdi21/presentation/landa

6. 通过DNN 将AI model从云端移植到边端（压缩模型）

   > Mistify: Automating DNN Model Porting for On-Device Inference at the Edge

7. Accessing Cloud with Disaggregated Software-Defined Router （腾讯云）

   在数据中心构建可编程的云网关（Disaggregated Software-defined Router）

8. 分布式机器学习 资源共享

   > https://www.usenix.org/conference/nsdi21/presentation/hwang

9. 通过network-wide packet history来诊断和分析数据中心网络故障

   > https://www.usenix.org/conference/nsdi21/presentation/kannan

10. 自适应调整云端中心与远程数据库的交互方式（key-value/RPC）

    > https://www.usenix.org/conference/nsdi21/presentation/you

11. 优化分布式深度学习训练的通信速度 (NSDI Best Paper)

    目前，云端分布式深度学习的瓶颈已经从硬件转移到了网络，本文采用programmable switch hardware来加速通信（ ATP uses emerging programmable switch hardware to support in-network aggregation at multiple rack switches in a cluster to speedup DT jobs.）

    > https://www.usenix.org/conference/nsdi21/presentation/lao

12. Orion: Google's Software-Defined Networking Control Plane

    > https://www.usenix.org/conference/nsdi21/presentation/ferguson

### 引用

###### NSDI 2021 Accepted Papers

> https://www.usenix.org/conference/nsdi21/accepted-papers

