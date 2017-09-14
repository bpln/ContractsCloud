---
layout: default
---

# Overview

![Contracts]({{ site.url }}/images/Intro-Contracts.png "System Illustration") 
{: .pull-right}

We propose a new contracts-based resource sharing model for federated geo-distributed clouds that allows cloud service providers to establish resource sharing contracts with individual datacenters apriori for defined time intervals during a 24 hour time period. Based on the established contracts, individual cloud service providers employ a cost-aware job scheduling and provisioning algorithm that enables tasks to complete and meet their response time requirements. The proposed techniques are evaluated through extensive experiments using realistic workloads and the results demonstrate the effectiveness, scalability and resource sharing efficiency of the proposed model.

## What is the challenge? 
 + How to Decide the Resource Sharing Contracts between Multiple Cloud Service Providers with Fairness and Efficiency?
 + How to Calculate the Utility of Each Cloud Service Provider?
 + How to Schedule the Jobs Among the Geo-distributed Data Centers?

## How the System Works?
 + Auction-based Contracts Establishment (Designed based on McAfee Mechanism)
    + Truthfulness: No Intuitive to Cheat Makes the Market with More Efficient and Fairness
    + Budget Balance: Keeps the Federation with Sustainable Development
    + Naturally Finds the Equilibrium Between the Supply and Demand
 + Fine-grained Utility Function Design Considers:
    + Operating Cost
    + Charges from Users
    + Penalty of Violating SLA
 + Resource Sharing Contracts
    + Relative Long Time Contracts Avoid Frequent Migrations
    + Predetermined: Do Not Disturb the Normal Operations of the Data Centers
 + Cost-aware Scheduling based on the Contracts
    + Optimize the Cost of Using the Contracts

**Publications**

 + Jinlai Xu, Balaji Palanisamy (2017). [Cost-aware Resource Management for Federated Clouds Using Resource Sharing Contracts](https://www.researchgate.net/publication/317097662_Cost-Aware_Resource_Management_for_Federated_Clouds_Using_Resource_Sharing_Contracts), IEEE Cloud 2017.
 
**Slides**

<iframe src="https://onedrive.live.com/embed?cid=E1DD6EDD2DA4DFBE&resid=E1DD6EDD2DA4DFBE%2121398&authkey=ANCwepdLkgdg-Xo&em=2" width="600" height="450" frameborder="0" scrolling="no"></iframe>
