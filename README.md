# SyncWeek
# Project Scope #

##Azure Service Fabric On Windows Server and Beyond  ##

> Azure Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scale and reliable microservices and containers. Service Fabric also addresses the significant challenges in developing and managing cloud native applications. Developers and administrators can avoid complex infrastructure problems and focus on implementing mission-critical, demanding workloads that can scale are reliable, and manageable. Service Fabric represents the next-generation platform for building and managing these enterprise-class, tier-1, cloud-scale applications running in containers. 
 
Many customers (in remote locations) or locations with bandwidth and connectivity considerations may need to implement an on-prem Windows Server Service Fabric cluster as their main application end point but use Azure as a co-location to move the containers and or microservices to an Azure Service Fabric Cluster in the event of a disaster or scale scenario.  In this hack we will create both an on-prem local service fabric cluster and an Azure service fabric cluster, create and build Windows and Docker Containers and also create an on-prem to Azure co-location scenario.

![](https://i.imgur.com/s03u7OZ.jpg)


**Project Team:**

Brent Hawkinson, Renee Dothard, Alex Anikiiev, David White, Vikram Paramasivan, Mayur Shintre, Brian Jackson, Saquib Rashid, Eduardo Sanchez, Robin Cole, James Truitt (ATLANTA), Margaryta Ostapchuk 




**Key Deliverables**

	- On-prem Service Fabric installation Automation
	- Azure Service Fabric Cluster installation Automation
	- Container Creation (Windows or Docker)
	- Orchestration between Windows Server Service Fabric Cluster on-prem and Azure Service Fabric



**Challenge Statement**

Currently there is a massive demand to move from a multi-tier monolithic application design approach to a high density containerized and microservice architecture.  Azure Service Fabric can support all of these approaches both in the cloud and locally.  However, can we combine the two for co-location, scale and disaster recovery scenarios from an orchestration perspective.  This hack will explore the possibilities of these scenarios.

**Leverage**

After the creation and validation of this hack further architectures can be applied to all customers looking not only to move to a container/microservice but those looking for dynamics scale and co-location architectures.  The team will be able to discuss, design and build these architectural options.


