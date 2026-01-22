# Summer-2025-ESMI-Research-Project---Queueing-Theory-x-Autonomous-Vehicles

Cornell University Engineering Summer Math Institute (ESMI) | 2025

TITLE
Stochastic Queue Jockeying and Deterministic Platoon Optimization Enhancements for Autonomous Vehicle Bottleneck Flow

ABSTRACT
We simulate bottleneck cases through a queueing-theoretic model of autonomous vehicle traffic flow that utilizes jockeying and platooning strategies. 
Our model optimizes for the average speed in mph of vehicles as a measure of service rate. We measurably improve traffic flow compared to existing bottleneck case studies in the US, specifically the intersection of I-95 at SR 4 in Fort Lee, New Jersey and I-285 at I-85 (North) in Atlanta, Georgia. 

Our preliminary model structures an intersection as two parallel M/M/1 queues under a single shared traffic light “server” defined by exponentially distributed service times and non-deterministic (Poisson-derived) arrival rates for customers. At the light, vehicles may, with varying probability, choose to jockey between lanes based on estimates of the queue lengths before eventually leaving the queue to merge into a single-lane bottleneck. 

Pivoting towards tangible comparisons against real-world bottlenecks, we additionally developed a deterministic model where average arrival rates across case studies were known. In this variant, we converted 24-hour speed profiles into hourly demand fractions and generated fixed arrival streams by spacing each site’s known daily traffic volume evenly through every hour (carrying any leftover vehicles forward). We applied our bulk-service jockeying framework under a 60 mph speed limit with a fixed intra-platoon gap, forming platoons at regular comfort-time intervals. By sweeping comfort times from 1 to 90 seconds at each study site, we computed platoon-level throughput in mph. 

We optimized our platoon parameters and analyzed them in comparison with known, real-world arrival patterns and identified the comfort-time/platoon-size combinations that deliver the highest sustained flow. Preliminary results indicate a scalable tool for traffic efficiency as we approach a future of increased AV presence, outperforming current metrics on congestion across two major bottlenecks into major US cities. Optimal jockeying parameters and platoon logic for optimizing traffic flow through bottlenecks provide a snapshot into possible algorithmic decision-making in the future, reducing dependency on outdated human driving data. 


Done with Siena Claudio and Mamadou Barry - mentored by Laurel Newman under the ESMI program
