---
layout: post
section-type: post
title: Load Balancing
category: tech
tags: [ 'tutorial' ]
---

![Alt text](/img/load_balancing_1.png)

*Image reference from: https://www.cloudns.net/blog/load-balancing/*

# Load Balancing
Load balancing is the process of distributing network traffic across multiple servers. 
It helps to ensure that no single server is overloaded with too much demand.

## Benefits of Load Balancing
**Distributes incoming traffic across multiple targets:**
Load balancing helps distribute the workload across various servers, ensuring that no single server becomes
overwhelmed with traffic. This aids in optimizing resource utilization and preventing any particular server from
becoming a bottleneck.

**Maintains high fault tolerance and high availability to 99.99%:** Load balancers can detect if a server is not responding
or is experiencing issues and can divert traffic away from it, thus enhancing fault tolerance. By spreading the load
across multiple servers, it helps maintain high availability, often measured in terms of uptime (99.99% uptime, for
example).

**Enhances reliability:** Load balancing improves the overall reliability of a system by minimizing the risk of server
failure causing a service outage. If one server fails, others can still handle incoming requests, ensuring that the
service remains available.

**Facilitates scalability:** Load balancing facilitates scalability by allowing easy addition or removal of servers based on
traffic demands. This adaptability ensures that the system can handle increased traffic without compromising
performance.

**Offers flexibility in managing traffic:** Load balancing provides flexibility in managing traffic. It allows
administrators to set rules, prioritize certain types of traffic, and apply different load balancing algorithms based on
specific needs.

**Improves overall system availability:** By distributing traffic across multiple servers, load balancing enhances the
availability of the system. Even if one server goes down, the load balancer redirects traffic to other healthy servers,
minimizing service disruptions.

### Types of Load Balancers
* Application LB: HTTP and HTTPS traffic
* Network LB: TCP and TLS traffic
* Classic LB: Applications that were built with an EC2 classic network.


