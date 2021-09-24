# Notes 02:
## Cloud Economics Billing & Support
_**AWS Pricing:Payment Models**_
1. Pay-as-you-go (on demand):Pay-as-you-go pricing allows you to easily adapt to changing business needs without over committing budgets and improving your responsiveness to changes. With a pay as you go model, you can adapt your business depending on need and not on forecasts, reducing the risk or over provisioning or missing capacity.
2. Reservation-Based:available in 3 options: When you buy Reserved Instances, the larger the upfront payment, the greater the discount. To maximize your savings, you can pay all up-front and receive the largest discount. Partial up-front RI's offer lower discounts but give you the option to spend less up front. Lastly, you can choose to spend nothing up front and receive a smaller discount, but allowing you to free up capital to spend in other projects.
   * All Upfront Reserved Instance (AURI)
   * Partial Upfront Reserved Instance (PURI)
   * No Upfront Reserved Instance (NURI)
3. Bulk-Use (pay less when you use more): With AWS, you can get volume based discounts and realize important savings as your usage increases. For services such as S3 and data transfer OUT from EC2, pricing is tiered, meaning the more you use, the less you pay per GB. In addition, data transfer IN is always free of charge. As a result, as your AWS usage needs increase, you benefit from the economies of scale that allow you to increase adoption and keep costs under control.

_**Key Principles of Pricing (3 Major somputing reasources):**_
   1. Compute
   2. Storage
   3. Outbound data transfer
   * These characteristics vary somewhat, depending on the AWS product and pricing model you choose.
   * Why are these important?
      * Start early with cost optimization:Adopting cloud services is not just a technical evolution. It also requires changes to how organizations operate. As you move from IT being treated as a capital investment that happens periodically to a world where pricing is closely tied to efficient use of resources, it pays to understand what drives cloud pricing so you can build a strategy for optimizing it.
      * Maximize the power of flexibility: No minimum commitments or long-term contracts are required unless you choose to save money through a reservation model. By paying for services on an as-needed basis, you can redirect your focus to innovation and invention, reducing procurement complexity and enabling your business to be fully elastic.
      * Use the right pricing model for the job: AWS offers several pricing models depending on product. 

_**Free Tier of Service:**_
   * The AWS Free Tier enables you to gain free, hands-on experience with the AWS platform, products, and services.
   * AWS Credits: $25 in credits for your normal AWS account, if requested
   * AWS Educate: $100 in credits for a starter account and access to classrooms with additional credits.
   * AWS Training: Access to AWS Technical Essentials Training Course and free access to labs
   * Content:
     * Ability to select personalized learning pathway with 30+ hours of content per path
     * Earn digital badges that showcase cloud skills
     * Free access to AWS content for homework, labs, or self-study
   * Collaboration: 
      * Student Portal access
      * Student Portfolio to store developed projects in one place
      * Access to the AWS Job Board and job postings
   * Free Services:
      * 750 hours of Amazon EC2 Linux or RHEL or SLES t2.micro instance usage (1 GiB of memory and 32-bit and 64-bit platform support) – enough hours to run continuously each month
      * 750 hours of an Elastic Load Balancer plus 15 GB data processing
      * 750 hours of Amazon RDS Single-AZ Micro DB Instances, running MySQL, PostgreSQL, Oracle BYOL or SQL Server Express Edition – enough hours to run a DB Instance continuously each month. You also get 20 GB of database storage, 10 million I/Os and 20 GB of backup storage
      * 750 hours of Amazon ElastiCache Micro Cache Node usage – enough hours to run continuously each month
      * 30 GB of Amazon Elastic Block Storage in any combination of General Purpose (SSD) or Magnetic, plus 2 million I/Os (with EBS Magnetic) and 1 GB of snapshot storage
      * 5 GB of Amazon S3 standard storage, 20,000 Get Requests, and 2,000 Put Requests
      * 25 GB of Storage, 25 Units of Read Capacity and 25 Units of Write Capacity, enough to handle up to 200M requests per month with Amazon DynamoDB
      * 25 Amazon SimpleDB Machine Hours and 1 GB of Storage
      * 1,000 Amazon SWF workflow executions can be initiated for free. A total of 10,000 activity tasks, signals, timers and markers, and 30,000 workflow-days can also be used for free
      * 100,000 Requests of Amazon Simple Queue Service
      * 100,000 Requests, 100,000 HTTP notifications and 1,000 email notifications for Amazon Simple Notification Service
      * 10 Amazon Cloudwatch metrics, 10 alarms, and 1,000,000 API requests
      * 50 GB Data Transfer Out, 2,000,000 HTTP and HTTPS Requests for Amazon CloudFront
      * Virtual Private Cloud (VPC)
      * Auto-Scaling
      * Elastic Beanstalk
      * CloudFormation
      * Consolidated Billing
      * Identity and Access Management (IAM)
      * AWS OpsWorks

_**TCO: Total Cost of Owership**_
* **Definition**: a formula that assesses direct and indirect costs and benefits related to the purchase of any IT component. The goal is a final figure that will reflect the true purchase price, all things considered.
* **Is it simple? NOP!** There are more moving parts that need to be assessed, as well as benefits that are there, but hard to define and determine. I propose we think differently about cloud computing and TCO, and indeed this is a core requirement as we move businesses to the cloud.
* **Defining our own TCO Model:** We must consider the following.
   * Existing infrastructure in place
   * Existing skills and humans.
   * difference in costs from pre-cloud to post-cloud
   * Cost of cloud services when in operations.
   * Value of agility (including time-to-market).
   * Value of avoiding future capital expenditures.
   * Cost of risk around compliance issues. 
* **How is Total Cost of Ownership Calculated?** 
   * _Cloud Economics Center._ TCO is a financial estimate that helps enterprise managers determine both direct and indirect costs of a product or system, such as AWS. This management accounting concept can be used to understand the big, long-term picture of exactly how much AWS will cost (or more accurately, save) your organization.
   * Hardware acquisition
   * Software acquisition
   * Infrastructure
   * Downtime
   * Installation
   * Maintenance
   * Training
   * Support
   * Space
   * Electricity
 
 
_**IT Infrastructure**_
   * **What is it?** 
      * Information technology (IT) infrastructure are the components required to operate and manage enterprise IT environments. IT infrastructure can be deployed within a cloud computing system, or within an organization's own facilities.
   * **What are the componenets?**
      * Software: The OS is responsible for managing system resources and hardware, and makes the connections between all of your software and the physical resources that do the work.
      * Networking: Interconnected network components enable network operations, management, and communication between internal and external systems. The network consists of internet connectivity, network enablement, firewalls and security, as well as hardware like routers, switches, and cables.
      * Hardware: Hardware includes servers, datacenters, personal computers, routers, switches, and other equipment. The facilities that house, cool, and power a datacenter could also be included as part of the infrastructure.
   * **Types:**
      * Traditional: the components—like datacenters, data storage, and other equipment—are all managed and owned by the business within their own facilities. 
      * Cloud: You can create a private cloud by building it yourself using resources dedicated solely to you. And by incorporating some degree of workload portability, orchestration, and management across multiple clouds you can create a hybrid cloud.


_**AWS Organizations**_






