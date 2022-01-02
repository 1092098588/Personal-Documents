# SIGCOMM 调研

### Introduction

研究SIGCOMM2020、2021论文，总结云网络/数据中心/SDN领域研究方向。



### SIGCOMM2020

1. ##### 可编程交换机的构建 （SDN）

2. ##### 网络遥测（telemetry）

   遥测技术包含：业务类型识别，关键业务保障、业务质量感知（QoS），故障发现和分析，流量预测，故障预测。

   主流：带内遥测

   > 介绍：
   >
   > https://baijiahao.baidu.com/s?id=1644843282895862530&wfr=spider&for=pc

3. ##### 路由

4. ##### 验证（Verification）

   网络配置的验证（P4，DNS……）

5. ##### 视频

   视频采集、视频流……

6. ##### 拥塞控制

7. ##### 可编程交换机的应用

8. ##### 数据中心故障诊断

   > [1]. Aeolus: A Building Block for Proactive Transport in Datacenters
   >
   > [2]. MasQ: RDMA for Virtual Private Cloud
   >
   > [3]. VTrace: Automatic Diagnostic System for Persistent Packet Loss in Cloud-Scale Overlay Network
   >
   > [4]. Scouts: Improving the Diagnosis Process Through Domain-customized Incident Routing

9. ##### 散射通信（无线通信）

10. #####  NFV

11. ##### 数据中心架构

    > [1]. Sirius: A Flat Datacenter Network with Nanosecond Optical Switching
    >
    > [2]. 1RMA: Re-envisioning Remote Memory Access for Multi-tenant Datacenters
    >
    > [3]. SmartNIC Performance Isolation with FairNIC: Programmable Networking for the Cloud
    >
    > [4]. Beyond the mega-data center: networking multi-data center regions

12. ##### 无线通信

13. ##### 大规模应用类论文

##### 总结：

SIGCOMM会议的特点：工程类占绝大多数，基于SDN的网络占主流。有多篇论文用到深度学习技术和P4开源SDN架构。



### SIGCOMM2021

1. ##### verification

2. ##### 分布式系统和网络支持

   网络堆栈开销，数据中心网络通信；分布式缓存、多租户存储

3. ##### 可编程数据平面

   可编程包（packet）

   基于可编程交换机的云端 多租户+多服务 网关

   > https://dl.acm.org/doi/10.1145/3452296.3472889

4. ##### ML for Networking

   机器学习 + 网络规划/协议消歧和代码自动生成/数据中心网络性能评估/验证

5. ##### 数据中心网络

   - 基于理论的网络优化：Designing data center networks using bottleneck structures

   > 使用QTBS理论构建数据中心的数学模型，优化网络
   >
   > https://dl.acm.org/doi/10.1145/3452296.3472898

   - 数据中心拓扑性能视图
   - 网络拥塞检测/优化

6. ##### 服务（Service）

7. ##### Networking for ML

   - 优化分布式机器学习的通信（构建efficent and fault-tolerant collective communication layer)
   - 将光通信网络用语ML

8. ##### 网络管理

   - 将NFV应用到实际

     > Bento: safely bringing network function virtualization to Tor
     >
     > https://dl.acm.org/doi/10.1145/3452296.3472919

##### 总结

与无线通信（物联网、5G、蜂窝网络）相关的内容更多了，将ML用于网络、以及将网络用于分布式ML也更多了。



### 引用

###### SIGCOMM 2020

> https://www.zhihu.com/question/396721973 

###### SIGCOMM 2021

> https://dl.acm.org/doi/proceedings/10.1145/3452296#heading4

###### Typora Guide

> https://blog.csdn.net/mus123/article/details/104294246

###### Push the file to Github

> https://blog.csdn.net/FindHuni/article/details/106374506