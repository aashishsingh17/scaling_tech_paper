 # Abstract
 
## To overcome the issue in performance and scaling needs proper load balancing. We are looking to investigate the possibility of using *load balancers* and understand *horizontal scaling* and *vertical scaling*.

# Introduction

Let's understand load balancing, load balancing is the approach for efficient distribution of the set of tasks
over resources to avoid overloading and low performance and to make the server efficiently scalable.
Load balancing requires keeping productivity high, some reasons to use load balancing are given below.
     Increased traffic and causes overloading of the network server.
A load balancer is needed to handle the increased traffic by redirecting it to better-performing servers or to other servers that have capacity. It is required to improve the workload distribution among several computing resources like CPU, computer clusters, network links, etc.
Now coming to the load balancer, it is the device that acts across incoming servers and distributions. 
It may be a physical device, a virtual instance, or a software process that may support round-robin, 
server response time, and Least connection to distribute traffic with requirements. 

*Specifically, I am taking the examples of load balancers available in AWS(Amazon Web Services) 
as per convenience, we can use others as well.*

* Elastic Load Balancing that automatically distributes incoming application traffic across multiple targets. 

* Application Load Balancer for load balancing of HTTP and HTTPS traffic. 

* Network Load Balancer for load balancing of Transmission Control Protocol, User Datagram Protocol, and Transport Layer Security traffic where extreme performance is required.

* Gateway Load Balancer makes it easy to deploy, scale, and run third-party virtual networking appliances.

* Classic Load Balancer provides basics load balancing.

Let's understand the scaling of resources over traffic. There are horizontal scaling and vertical scaling solutions.

Horizontal scaling (Scale-Out) -
In this type of scaling, we add more machines into the resources that can extend capacity by 
adding different hardware or software resources. 
It required partitioning so that each node should contain part of the data.
Horizontal scaling is comparatively costly and needed a load balancer to distribute the load, 
it increases the power of an individual server with the existing server.

Vertical scaling (Scale-Up) - 
In this scaling, we make our existing resources more powerful up to the maximum extent for example adding more CPU, RAM to the existing machine. Data present on a single node is scaled through multicore, 
it is comparatively cost-effective and increases the power of the individual server.

                                                     
# Conclusion

We have come across the maximum possible ways to overcome performance and scaling issues 
and as per requirements, we can do load balancing and for distribution of resources over traffic we can 
use horizontal scaling and vertical scaling solutions.

                                                      
# References

1] *AWS load balancing* [see reference](https://aws.amazon.com/elasticloadbalancing/?whats-new-cards-elb.sort-by=item.additionalFields.postDateTime&whats-new-cards-elb.sort-order=desc).

2] [see reference](https://www.nginx.com/resources/glossary/load-balancing/). 

3] [see reference](https://www.redswitches.com/blog/difference-between-horizontal-vertical-scaling/).









