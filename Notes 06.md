# Notes 06: Compute
## AWS Compute Services
Four broad categories of compute services:
1. Virtual Machines
2. Containers
3. Serverless
4. Platform as a Service

Categories of Virtual Machines:
* Virtual Machines: Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. 
   * designed to make web-scale computing easier for developers.
   *  allows you to obtain and configure capacity with minimal friction. 
   *  provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.
   *  allows you to build Infrastructure as a Service (IaaS) applications for instance-based virtual machines.

* Serverless
   * AWS Lambda lets you run code without provisioning or managing servers.
   * a category of compute where you write and deploy code, but do not manage the underlying infrastructure.
   * a function based environment that is low cost where deployed code can be triggered on a schedule or events.
   * a newer concept for many IT professionals but is easy to learn and use. 
* Containers
   * Amazon Web Services has many different container services including Amazon Elastic Container Service, Amazon Elastic Kubernetes Service, AWS Fargate, and Amazon Elastic Container Registry.
   * These services are instance-based and enable you to run multiple workloads on a single operating system (OS). Containers spin up more quickly than virtual machines, thus offering responsiveness. Container-based solutions continue to grow in popularity.
   * AWS Fargate can be used to help reduce administrative overhead and give you options for additional control.
* Plateform as a Service
   * allows a company to focus on building code and applications rather than manage infrastructure.
   * AWS Elastic Beanstalk provides a platform as a service (PaaS).
   * facilitates the quick deployment of applications that you create by providing all the application services that you need.
   * AWS manages the OS, the application server, and the other infrastructure components so that you can focus on developing your application code.
   * For IT professionals, it is a fast and easy service to get started, however, you loose the ability to control the underlying infrastructure.
   
* Summary of AWS Compute Services:
   * Amazon Elastic Compute Cloud (Amazon EC2) provides resizable virtual machines.
   * Amazon EC2 Auto Scaling supports application availability by allowing you to define conditions that will automatically launch or terminate EC2 instances.
   * Amazon Elastic Container Registry (Amazon ECR) is used to store and retrieve Docker images.
   * Amazon Elastic Container Service (Amazon ECS) is a container orchestration service that supports Docker.
   * Amazon Elastic Kubernetes Service (Amazon EKS) enables you to run managed Kubernetes on AWS.
   * Amazon Lightsail provides a simple-to-use service for building an application or website.
   * AWS Batch provides a tool for running batch jobs at any scale
   * AWS Elastic Beanstalk provides a simple way to run and manage web applications.
   * AWS Fargate provides a way to run containers that reduce the need for you to manage servers or clusters.
   * AWS Lambda is a serverless compute solution. You pay only for the compute time that you use.
   * AWS Serverless Application Repository provides a way to discover, deploy, and publish serverless applications.
   * AWS Outposts provides a way to run select AWS services in your on-premises data center.
   * VMware Cloud on AWS enables you to provision a hybrid cloud without custom hardware.

Choosing the Right Services:
* Selecting Compute Resources
  * When evaluating compute options, be aware of your requirements for workload performance and cost requirements and use this to make informed decisions.
  * In AWS, compute is available in three forms: instances, containers, and functions:
    1. Instances are virtualized servers, allowing you to change their capabilities with a button or an API call. Because resource decisions in the cloud aren’t ﬁxed, you can experiment with different server types. At AWS, these virtual server instances come in different families and sizes, and they offer a wide variety of capabilities, includ- ing solid-state drives (SSDs) and graphics processing units (GPUs).
    2. Containers are a method of operating system virtualization that allow you to run an application and its dependencies in resource-isolated processes. AWS Fargate is serverless compute for containers or Amazon EC2 can be used if you need control over the installation, configuration, and management of your compute environment. You can also choose from multiple container orchestration platforms: Amazon Elastic Container Service (ECS) or Amazon Elastic Kubernetes Service (EKS).
    3. Functions abstract the execution environment from the code you want to execute. For example, AWS Lambda allows you to execute code without running an instance.
* Best Practices for Selecting Compute Resources
  * **Evaluate the available compute options:** Understand the performance characteristics of the compute-related options available to you. Know how instances, containers, and functions work, and what advantages, or disadvantages, they bring to your workload.
  * **Understand the available compute configuration options:** Understand how various options complement your workload, and which configuration options are best for your system. Examples of these options include instance family, sizes, features (GPU, I/O), function sizes, container instances, and single versus multi-tenancy.
  * **Collect compute-related metrics:** One of the best ways to understand how your compute systems are performing is to record and track the true utilization of various resources. This data can be used to make more accurate determinations about resource requirements.
  * **Determine the required configuration by right-sizing:** Analyze the various performance characteristics of your workload and how these characteristics relate to memory, network, and CPU usage. Use this data to choose resources that best match your workload's profile. For example, a memory-intensive workload, such as a database, could be served best by the r-family of instances. However, a bursting workload can benefit more from an elastic container system.
  * **Use the available elasticity of resources:** The cloud provides the flexibility to expand or reduce your resources dynamically through a variety of mechanisms to meet changes in demand. Combined with compute-related metrics, a workload can automatically respond to changes and utilize the optimal set of resources to achieve its goal.
  * **Re-evaluate compute needs based on metrics:** Use system-level metrics to identify the behavior and requirements of your workload over time. Evaluate your workload's needs by comparing the available resources with these requirements and make changes to your compute environment to best match your workload's profile. For example, over time a system might be observed to be more memory-intensive than initially thought, so moving to a different instance family or size could improve both performance and efficiency.

