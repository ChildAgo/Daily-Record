# SDIoT- a software defined based internet of things framework  
## 手记
1.Key Words  
- Internet of things (IoT)物联网  
- Software defined network (SDN)   
- Software defined systems (SDSys)  
- Software defined storage (SDStore)  
- Software defined security (SDSec)  
* forwarding elements转发单元  
- IBM 美国国际商用机器公司  
- interface protocols接口协议  
- Software defined perimeter (SDP)  
- WSN(Wireless Sensor Network)无线传感器网  
- API(Application Program Interface) 应用程序接口  
2.Main Ideas  
  
>In this paper,a software defined based framework for Internet
of Things (SDIoT) is proposed. At the first, we highlighted
how the software defined system handle the challenges of
traditional system architecture as it provides a centralized,
programmable, flexible, simple and scalable solution to con-
trol the systems. Then, different forms of SDSys (SDN,
SDStore, and SDSec) presented and explained, which are
considered the main known ones from the SDSys.  

>After discussing existing SDN, SDStore and SDSec
solutions, we talked about our proposed SDIoT architec-
tural model and showed how we exploit the ideas from
SDN, SDStore, and SDSec to build it. Later, we presented
its main elements and showed how these elements interact
with each other to provide a comprehensive framework to
control the IoT network.  

>The proposed model was built to provide a proof of
concept, and we explained how the systems can be built to
accommodate large data which produced from the wide-
spread of the IoT. We plan to develop an experimental
framework for SDIoT to test different forms and types of
the IoT topologies.  

- 基于软件定义的框架提出了SDIoT，然后提到了SDN、SDStore、SDSec，并用实例讲述了解决方案，最后提出如何构建适应大数据产生和蔓延的物联网框架。  


#A System Architecture for Software-Defined Industrial Internet of Things  
##手记  
1.Key Words  
- IIoT(Industrial Internet of Things)  
- IETF是Internet工程任务组（Internet Engineering Task Force）的简写  
- broad spectrum 广谱  
- QoS(quality of service)  
- FDs(field devices)现场设备  
- GW(gateways)网关  
- CORBA(Common Object Request Broker Architecture)通用对象请求代理体系结构  
- CoAP(constrained application protocol)  
- SC(sender cloud)  
- channel hopping 信道跳跃    
- time division 划分时间  
- bandwidth 带宽  
- (HPCC)是High Performance Computing and Communications(高性能计算与通信)的缩写  
- processing delay,queuing delay,transmission delay,propagation delay  
- 处理时延，排队时延，传输时延，传播时延  
- SD-IIoT system consists of IIoT FD,IIoT GW and IIoT SC

2.Main Ideas  
- In this paper, a new software-defined IIoT (SD-IIoT)
architecture with its key components based on the low-power
industrial WSNs will be proposed and the software-defined
functions for FDs, GWs, and SC based on WebSocket, CoAP,
and SDN technologies will be discussed.  
- I can not figure section3 and section4 out clearly.  
- An SD-IIoT architecture is proposed to
address the essential requirements of generic IIoT applications,
which can lead to an effective IIoT system design. 


#Pre-emptive Flow Installation for Internet of Things Devices within Software Defined Networks  
#手记  
>This paper proposes a Pre-emptive Flow Installation Mecha-
nism (PFIM) that dynamically learns the transmission intervals
of periodic network flows and installs the corresponding rules
within a switch, prior to the arrival of a packet.  
- Section2 presents a brief background review of IoT devices and their
data characteristics.  IoT Example Scenario:The Smart Care Spaces project/Emergency Services 
- Section 3 provides further detail of the SDN concept and how it relates to the IoT.  
- Section 4 presents a proposed Pre-emptive Flow Installation Mechanism (PFIM). 
- Section 5 evaluates the proposed mechanism in terms of performance characteristics.  
-  Section 6 concludes and discusses potential future work.  

1.Key Words  

- Idle timeout 空闲超时时间  
- Hard timeout 硬超时  
- Pre-emptive Flow Installation Mechanism(PFIM)  
- three main principles/components of SDN  
-- Decoupling of controller and data planes 控制平面和数据平面的去耦  
-- Logically centralised control 从逻辑上集中控制  
-- Exposure of abstract network resources and state to external applications 抽象的网络资源和状态，以曝光外部应用程序  
- SDN(A. SDN Standards/B. SDN Controllers/C. SDN Switch Devices)  
- PFIM's three main components:flow monitoring,flow periodicity checking,and flow installation  

2.Main Ideas  

- 文章第一部分介绍，第二部分介绍背景和物联网装置，第三部分详细介绍SDN组成和关联，第四部分通过图表展现OpenFlow1.0/1.5流规则和安装的不同，第五部分介绍提出的PFIM，第六部分总结。  
>This paper has presented a discussion of potential per-
formance issues that may arise from the combination of
IoT device traffic patterns and current SDN implementations.
Through the introduction of a proposed Pre-emptive Flow
Installation Mechanism it has been shown that the patterns
of periodic data transfers can be observed by a controller and
flow rules installed prior to the arrival of packets at a switch,
thus negating the added delay that comes from querying a
controller. This has been demonstrated through a proof of
concept implementation within the POX controller framework.  

>Future work will focus on testing within larger topologies,
across multiple switches, and within a hardware-based test-
bed. This will include the mixing of IoT device traffic with
other real network traffic as a means of observing the resulting
behaviour and adapting the proposed mechanism accordingly.

