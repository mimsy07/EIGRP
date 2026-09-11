# EIGRP
This project demonstrates the implementation of EIGRP routing protocol (Enhanced Interior Gateway Protocol) in a local area network environment. Enhanced Interior Gateway Routing Protocol is a Hybrid type of routing protocol that used DUAL (Diffuse Upgrade Algorithm) as its algorithm used to dynamically exchange routing information and determine the best and reliable path between network. EIGRP is by default has a faster convergence time than the other routing protocol.

This network is configured with the EIGRP routing protocol and an autonomous system number 200, allowing routers to learn and maintain remote networks automatically. This project also demonstrates the implementation of passive-interface disabling interface that doesn't need to send out hello messages, preventing unauthorized neighbor discovery.

Also implement  EIGRP security by configuring passive-interface and authentication to prevent unauthorized neighbor adjacency and securing each EIGRP port by implementing a key chain

# Main Objectives
To create a local network that used a dynamic routing protocol to automatically advertise its remote network to its neighbor router, faster convergence time in the way that it quickly finds an alternative path when the main path fails, and securing active EIGRP interfaces.


<h2>Skills Demonstrate</h2>

1. Configuration of EIGRP routing protocol
2. Implementation of passive interface and EIGRP authentication
3. Troubleshoot network problem and  authentication problem
4. Assigning IP addresses in the router interfaces
5. General routing configuration

# Project Walk through
<p align="center">
Network Diagram: <br/>
<img src="https://github.com/mimsy07/EIGRP/blob/main/Images/EIGRP%20Topo.png" height="80%" width="80%"/>
<br />
<br />
  
<h3>Routing table from R1 and R10's perspective</h3>

<p align="left">
R1's routing protocol
<img src="https://github.com/mimsy07/EIGRP/blob/main/Images/R1%20routing%20table.png" height="60%" width="60%"/>
<br />
<br />
  
<p align="left">
R10's routing protocol
<img src="https://github.com/mimsy07/EIGRP/blob/main/Images/R10%20routing%20table.png" height="60%" width="60%"/>
<br />
