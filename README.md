# 5G-Network-Optimization-using-Intent-Based-Networking
Network Automation using Intent-Based Networking

Table of Content
1. [introduction](#anchors-in-markdown)
2. [intent-based network](#anchors-in-markdown)
3. Intent-Based Network tools
4. Network Slice
5. End-to-End Network Slice


## Introduction.
The automatic control over the network platform is an admired requirement of the network operators. The Fifth generation network provides a wide range of services with high bandwidth, greater reliability, excellent performance, and latency. The 5G technology can be optimized by Intent-Based networking, IBN supports network orchestration, automatic provision, the configuration of the servers, allocations of the resources, rerouting the path. I tend to propose the Intent-Based networking model with its flow according to the stages. Additionally, I  will also talk about how IBN tools are the key factor for network slicing to provide higher-level network configuration. Secondly, I have proposed the GAN algorithm for network optimization and predicting dynamic traffic and resource allocation. To verify the model’s effectiveness I will conduct the evaluation from the datasets to check network systems and applications scenarios adding that I will employ LTSM to classify new evolving features of a dynamic network.  
## Intent-Based Network
An intent-based network (IBN)  bridges the gap between business and IT. It captures business intent and continuously aligns the end-to-end network with that intent. Intent can be applied to application service levels, security policies, compliance, operational processes, and other business needs[3]. Cisco introduced the IBN in 2017.
IBN works on a loop called building blocks including various stages. The IBN works on a closed-loop system consisting of four modules intent of the user: translation, activation, assurance, and feedback. The first stage is Translation where the system gets the input in natural language and it automatically translates those configurations in the system into an understandable format for the network. Human is prone to make mistakes and can also feed the wrong input. Thus, this first stage validates that the input given is correct and achievable and the necessary communications can be made before it gets a green signal. The network then automatically implements the intent without any interventions of the user and any manual monitoring. The system will ensure that all the policies and protocols are followed and obeyed. IBN protects the network from any type of invasion and malicious activities. Security is very important as various nodes are increasing with the dynamic demand of the network. The system recurrently runs the program to check the status of the network and in case of a failure, the administrator will be notified and will correct the course of action. A network can also be optimized using machine learning algorithms and can handle the dynamic demands of the network which will execute the intent of the user[4]. In the real-world scenario, while communicating in meetings over the network, while the present network has the limited capability to send the data packets over the network in a timeframe, it also has a lower bandwidth. If the network doesn’t get the proper bandwidth then the data packet can be lost in the network which results in disturbance in the live meeting or sometimes results in disconnections. For the network operator, it would be difficult to backhaul, and finding the type of error in real-time would be impossible. But with the machine learning algorithms, it is possible to find the error in real-time execution. The network itself would reroute the data to another path and would also avoid the path where there is not much traffic so that there would be no loss of connection of the data packets. In the activation step, it takes the intent from the previous step and then it frames into the network infrastructure. It activates policies all over the network infrastructure to optimize performance, security, and reliability. Apostolopoulos [5] Cisco Enterprise's, Activation step determines the Quality of service (QoS)  at each infrastructure all around the globe. Activation also can use Machine learning algorithms to predict whether the employee would be connected throughout the video conferencing. The algorithm can also predict any downtime at the location of the employee in advance before the meeting  
The third stage is Assurance, stated by Apostolopoulos  [5], assurance using machine learning can expect where the error will occur. It can also identify the saturated path and reroute itself. It can dynamically adapt according to the network congestion to provide the desired outcome. By using a feedback loop that gathers the data to determine if the network is working according to the intent given and can improve the things if not. 
   After the IBN, Huawei[2] introduced Intent – driven network (IDN) which is a similar kind of system to IBN. The IDN has the layer of Network Cloud Engine (NCE) that controls intelligent network control and management. Additionally, the software-defined network (SDN) controllers are integrated into the NCE platform for better efficiency. The operations of translations of intents and the activation stage are dynamically driven. It is also intelligent as it contains the modules of Artificial intelligence and big data analytics. The IDN network system has aimed to develop a future generation network with lifecycle management support, intelligent operation and management, closed-loop, multi-service support, E2E slicing support, and automatic failure and recovery.

