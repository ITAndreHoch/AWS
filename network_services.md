**Elastic Load Balancing**

Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. Elastic Load Balancing offers three types of load balancers that all feature the ***high availability, automatic scaling, and robust security*** necessary to make your applications fault tolerant.

* ***Application Load Balancer*** is best suited for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers. Operating at the individual request level (Layer 7), Application Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) based on the content of the request.

* ***Network Load Balancer*** is best suited for load balancing of TCP traffic where extreme performance is required. Operating at the connection level (Layer 4), Network Load Balancer routes traffic to targets within Amazon Virtual Private Cloud (Amazon VPC) and is capable of handling millions of requests per second while maintaining ultra-low latencies. Network Load Balancer is also optimized to handle sudden and volatile traffic patterns.

* ***Classic Load Balancer*** provides basic load balancing across multiple Amazon EC2 instances and operates at both the request level and connection level. Classic Load Balancer is intended for applications that were built within the EC2-Classic network.

**Network Load Balancer (NLB)** – layer 4 load balancer that routes connections based on IP protocol data 

**Application Load Balancer - (ALB**)layer 7 load balancer that routes connections based on the content of the request.

Two of the components you need to connect to your VPC with a VPN connection are:

* a virtual private gateway on the VPC side
* customer gateway on the on-premise network side


***


**CloudFront**

CloudFront is ***Content Delivery Network (CDN)*** that allows you to store (cache) your content at "edge location" located all around the world. This allows your customers to access your content more quickly - and also provides additionall security - especially against DDOS attacts).

Benefits include:

* Cache content at Edge Location for fast distribution to customers
* Built-in Distributed Denial of Service (DDoS) attack protection
* Integrates with many AWS services (S3, EC2, ELB, Route 53, Lambda)

***

**AWS Direct Connect**

AWS Direct Connect makes it easy to establish a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you can establish private connectivity between AWS and your data center, office, or co-location environment, which in many cases can reduce your network costs, increase bandwidth throughput, and provide a more consistent network experience than Internet-based connections.

***

**AWS Global Accelerator**

AWS Global Accelerator is a networking service that improves the availability and performance of the applications that you offer to your global users.

AWS Global Accelerator improves application availability by continuously monitoring the health of your application endpoints and routing traffic to the closest healthy endpoints.

***

**Amazon Route 53**

Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating human readable names, such as www.example.com, into the numeric IP addresses, such as 192.0.2.1, that computers use to connect to each other. Amazon Route 53 is fully compliant with IPv6 as well.


***

**AWS PrivateLink**

AWS PrivateLink simplifies the security of data shared with cloud-based applications by eliminating the exposure of data to the public Internet. AWS PrivateLink provides private connectivity between VPCs, AWS services, and on-premises applications, securely on the Amazon network.

***

**Amazon API Gateway**

Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. With a few clicks in the AWS Management Console, you can create an API that acts as a “front door” for applications to access data, business logic, or functionality from your back-end services, such as workloads running on Amazon EC2, code running on AWS Lambda, or any web application.

***

**AWS Transit Gateway**

AWS Transit Gateway is a service that enables customers to connect their Amazon Virtual Private Clouds (VPCs) and their on-premises networks to a single gateway.

***

**AWS App Mesh**

AWS App Mesh makes it easy to monitor and control microservices running on AWS. App Mesh standardizes how your microservices communicate, giving you end-to-end visibility and helping to ensure high-availability for your applications.

***

**AWS Cloud Map**

AWS Cloud Map is a cloud resource discovery service. With Cloud Map, you can define custom names for your application resources, and it maintains the updated location of these dynamically changing resources. This increases your application availability because your web service always discovers the most up-to-date locations of its resources.

***






















































