# Final Reading Notes
## CIT 114

1. Cloud Concepts Overview
* Quote via TechRadar.com "Cloud compututing services also offer the advantage of being scalable, which means not only can you access additional resources exactly as you need them, but you are also charged only for the services you use so there's no need to buy in extra hardware for additional redundancy."

What is Information Tech (IT)?
* Computing Power (CPU, RAM)
* Storage (Files, Database)
* Networking (wire, wireless) Keeping things running
* Security and Identity Management 
* Management 1. Billing and cost management 2.Compliance and Governance
* Apps & Websites

Hardware and Software
* Software includes data, apps, code, configuration files that are stored digitally
* Hardware is all the physical aspect of an IT system: Computer, Monitors, Input and Output Devices, ETC.

Four Pillars of IT Framework:
* Infrastructure
* Development
* Security
* Data

Terminology to consider for Cloud Computing:
* CPU (Center Processing Unit): "The CPU is the primary component of a computer that processes instructions. It runs the operating system and applications, constantly receiving input from the user or active software programs. It processes the data and produces output, which may be stored by an application or displayed on a screen."
   * ARM Processor (in mobile phones): "The ARM(Advanced RISC Machines) processor is a 32-bit RISC processor, meaning it is built using the RISC (reduced instruction set computer) ISA (instruction set architecture)." PDA's (personal digital assistants): digital media and music layer, hand-hed gaming systems, calculators, tablets, and computer hard drives.
   * 32-bit and 64-bit Architecture Processors (in laptops, workstations (desktops), or servers): 
      * 32-bit: 4 GB of memory
      * 64-bit: theoretical maximum of 16.8 million TB (8 TB of addressable RAM) can come in dual-core, quad-core, six-core, and eight-core versions for home computing. Multiple cores allow for an increased number of calculations per second that can be performed, which can increase the processing power and help make a computer run faster.
       
* RAM (Random Access Memory): RAM is made up of small memory chips that form a memory module. These modules are installed in the RAM slots on the motherboard of your computer
* Storage:
   * Hard Disk Drive (HDD): A hard disk drive (sometimes abbreviated as hard drive, HD, or HDD) is a non-volatile memory hardware device that permanently stores and retrieves data on a computer. A hard drive is a secondary storage device that consists of one or more platters to which data is written using a magnetic head, all inside of an air-sealed casing. Internal hard disks reside in a drive bay, connect to the motherboard, and are powered by a connection to the PSU (power supply unit).
   * Solid State Drive (SSD): Short for solid-state drive (or solid-state disk, although it doesn't use a disk mechanism), an SSD is a storage medium that uses non-volatile memory as a means of holding and accessing data. Unlike a hard drive, an SSD has no moving parts which gives it advantages such as faster access time, noiseless operation, higher reliability, and lower power consumption. 

* Case: The computer case encloses and holds most of the components of the system. It provides support and protection for internal elements such as the motherboard, disk drives, and power supplies, and controls and directs the flow of cooling air over internal components.
* Cooling: 
   * Fan: a hardware device that keeps the overall computer or a computer device cool by circulating air to or from the computer or component
   * Heat Sink: a device that incorporates either a fan or some other means to keep a hot component, such as a processor, cooled down. There are two heat sink types: active and passive. The picture is an example of a passive heat sink.
      * Active heat sinks utilize the computer's power supply and may include a fan. Sometimes these types of heat sinks are referred to as an HSF, which is short for heat sink and fan.
      * Passive heat sinks are those that have no mechanical components. Consequently, they are 100% reliable. Passive heat sinks are made of an aluminum finned radiator that dissipates heat through convection. For passive heat sinks to work to their full capacity, there should be a steady airflow moving across the fins.
   * Liquid Cooling: used to reduce the temperature of its hardware, specifically the CPU and GPU. Liquid is more efficient than gas at conducting thermal energy
* Power Supply: The power supply unit (PSU) converts alternating current (AC) electric power to low-voltage direct current (DC) power for the internal components of the computer.
* Input / Output Devices: 
   * Input Devices: llow the user to enter data into a system, or control its operation. Most computers have a mouse and keyboard, but laptop systems typically use a touchpad instead of a mouse. Other input devices include webcams, microphones, joysticks, and image scanners.
   * Output Device: are designed around the senses of human beings which include vision, hearing, or touch. For example, monitors display images that can be seen or read, speakers produce audio that can be heard. Such devices also include printers, speakers, monitors or a Braille embosser.
2. Cloud Economics, Billing & Support
_**AWS Pricing:Payment Models**_
1. Pay-as-you-go (on demand):Pay-as-you-go pricing allows you to easily adapt to changing business needs without over committing budgets and improving your responsiveness to changes. With a pay as you go model, you can adapt your business depending on need and not on forecasts, reducing the risk or over provisioning or missing capacity.
2. Reservation-Based:available in 3 options: When you buy Reserved Instances, the larger the upfront payment, the greater the discount. To maximize your savings, you can pay all up-front and receive the largest discount. Partial up-front RI's offer lower discounts but give you the option to spend less up front. Lastly, you can choose to spend nothing up front and receive a smaller discount, but allowing you to free up capital to spend in other projects.
   * All Upfront Reserved Instance (AURI)
   * Partial Upfront Reserved Instance (PURI)
   * No Upfront Reserved Instance (NURI)
3. Bulk-Use (pay less when you use more): With AWS, you can get volume based discounts and realize important savings as your usage increases. For services such as S3 and data transfer OUT from EC2, pricing is tiered, meaning the more you use, the less you pay per GB. In addition, data transfer IN is always free of charge. As a result, as your AWS usage needs increase, you benefit from the economies of scale that allow you to increase adoption and keep costs under control.


_**Billing and Cost Management:**_
   * AWS Billing and Cost Management is the service that you use to pay your AWS bill, monitor your usage, and analyze and control your costs.
   * On the dashboard you can view the following graphs:
      * Spend Summary:  shows you how much you spent last month, the estimated costs of your AWS usage for the month-to-date, and a forecast for how much you are likely to spend this month. The forecast is an estimate based on your past AWS costs, so your actual monthly costs might not match the forecast.
      * Month-to-Date Spend by Service: The Month-to-Date Spend by Service graph shows the top services that you use most and the proportion of your costs that that service contributed to. The Month-to-Date Spend by Service graph doesn't include forecasting.
      * Month-to-Date Top Services by Spend: The Month-to-Date Top Services by Spend graph shows the services that you use most, along with the costs incurred for the month to date. The Month-to-Date Top Services by Spend graph doesn't include forecasting.
   * Features in Billing and Cost Management: 
      * The Billing and Cost Management service provides features that you can use to do the following:
         * Estimate and plan your AWS costs
         * Receive alerts if your costs exceed a threshold that you set
         * Assess your biggest investments in AWS resources
         * Simplify your accounting if you work with multiple AWS accounts
      * Important tools built into the Billing and Cost Management include:
         * AWS Cost Explorer
         * AWS Budgets
         * AWS Cost and Usage Reports
   * Manage Your Payments: 
      * You can view your estimated bills and pay your AWS invoices in your preferred currency by setting a payment currency. The AWS Bills page lists the costs that you incurred over the past month for each AWS service, with a further breakdown by AWS Region and linked account.
      * This tool gives you access to the most up-to-date information on your costs and usage, including your monthly bill and the detailed breakdown of the AWS services that you use.

**Cost Explorer**
   * AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. 
   * Get started quickly by creating custom reports that analyze cost and usage data. 
   * Analyze your data at a high level (for example, total costs and usage across all accounts) or dive deeper into your cost and usage data to identify trends, pinpoint cost drivers, and detect anomalies.
   * The Cost Explorer is a free tool that enables you to:
      * View charts of your costs.
      * View cost data for the past 13 months.
      * Forecast how much you are likely to spend over the next 3 months.
      * Discover patterns in how much you spend on AWS resources over time and identify cost problem areas.
      * Identify the services that you use the most
      * View metrics, like which Availability Zones have the most traffic or which linked AWS account is used the most.
** AWS Budgets:**
   * Use AWS Budgets to track your AWS usage and costs. 
   * Budgets use the cost visualization provided by Cost Explorer to show you the status of your budgets. This provides forecasts of your estimated costs and tracks your AWS usage, including your free tier usage. 
   * You can also use budgets to create Amazon Simple Notification Service (Amazon SNS) notifications that tell you when you go over your budgeted amounts, or when your estimated costs exceed your budgets.

**Cost and Usage Report:**
   * You can choose to have AWS publish billing reports to an Amazon Simple Storage Service (Amazon S3) bucket that you own. 
   * You can receive reports that break down your costs by the hour or month, by product or product resource, or by tags that you define yourself.



3. Cloud Global Infrastructure
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
   * As a student:
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
   * AWS Organizations is an account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage.
   * AWS Organizations includes account management and consolidated billing capabilities that enable you to better meet the budgetary, security, and compliance needs of your business.
   * As an administrator of an organization, you can create accounts in your organization and invite existing accounts to join the organization.
   * AWS Organizations is offered at **no additional charge**. You are charged only for AWS resources that users and roles in your member accounts use.
   * **Features offered by AWS Organization:**
      * Centralized management of all of your AWS accounts: Combine existing acct into an organization that enables you to manage the acct centreally
      * Consolidated billing for all member : You can use the master account of your organization to consolidate and pay for all member accounts.
      * Hierarchical grouping of your accounts to meet your budgetary, security, or compliance needs
      * Control over the AWS services and API actions that each account can access
      * Help for standardizing tags across resources in your organization's accounts
      * Integration and support for AWS Identity and Access Management (IAM)
      * Integration with other AWS services
      * Data replication that is eventually consistent
      

* **Key Concepts**
![4-17-BasicOrganization](https://user-images.githubusercontent.com/90662294/134721600-a63ec473-bf59-4fc8-ba99-4130cc776222.png)
   * **Organization**
      * An organization has one master account along with zero or more member accounts. You can organize the accounts in a hierarchical, tree-like structure with a root (Links to an external site.) at the top and organizational units (Links to an external site.) nested under the root.
   * **Root**
      * If you apply a policy to the root, it applies to all organizational units (OUs) (Links to an external site.) and accounts (Links to an external site.) in the organization.
      *  you can have only one root. 
      *  AWS Organizations automatically creates it for you when you create an organization.
   * **Organizatoin Unit (OU)**
      * An OU also can contain other OUs, enabling you to create a hierarchy that resembles an upside-down tree, with a root at the top and branches of OUs that reach down, ending in accounts that are the leaves of the tree. 
      * When you attach a policy to one of the nodes in the hierarchy, it flows down and affects all the branches (OUs) and leaves (accounts) **beneath** it.
      * An OU can have exactly one parent, and currently each account can be a member of exactly one OU.
   * **Account:** 2 Types
      1. The _**master account**_ is the account that creates the organization. 
         * From the organization's master account, you can do the following:
            * Create accounts in the organization
            * Invite other existing accounts to the organization
            * Remove accounts from the organization
            * Manage invitations
            * Apply policies to entities (roots, OUs, or accounts) within the organization
         * The master account has the responsibilities of a payer account and is responsible for paying all charges that are accrued by the member accounts. You can't change an organization's master account.
      2.  The rest of the accounts that belong to an organization are called _**member accounts**_. An account can be a member of _only one organization at a time_.
   * **Invitation**
      * The process of asking another account (Links to an external site.) to join your organization (Links to an external site.). 
      * An invitation can be issued only by the organization's master account. 
      * The invitation is extended to either the account ID or the email address that is associated with the invited account. 
      * After the invited account accepts an invitation, it becomes a member account in the organization.
      * Invitations work by accounts exchanging handshakes (Links to an external site.).
   * **HandShake**
      * A multi-step process of exchanging information between two parties. 
      * One of its primary uses in AWS Organizations is to serve as the underlying implementation for invitations (Links to an external site.). 
      * Handshake messages are passed between and responded to by the handshake initiator and the recipient. 
      * The messages are passed in a way that ensures that both parties always know what the current status is. 
      * Handshakes also are used when changing the organization from supporting only consolidated billing (Links to an external site.) features to supporting all features (Links to an external site.) that AWS Organizations offers.
   * **Available Feature Sets**
      * _All features_ – The default feature set that is available to AWS Organizations. It includes all the functionality of consolidated billing, plus advanced features that give you more control over accounts in your organization.
      * _Consolidated billing_ – This feature set provides shared billing functionality, but does not include the more advanced features of AWS Organizations. 
   * **Service Control Policy (SCP)**
      * A policy that specifies the services and actions that users and roles can use in the accounts that the SCP (Links to an external site.) affects. 
      * SCPs are similar to IAM permissions policies except that they don't grant any permissions.
   * **Tag Policy**
      * A type of policy that can help you standardize tags across resources in your organization's accounts. 
      * In a tag policy (Links to an external site.), you can specify tagging rules for specific resources.
   * **Allow Lists vs. Deny Lists**
      * Allow list strategy – You explicitly specify the access that _**is**_ allowed.
      * Deny list strategy – You explicitly specify the access that is  _**not**_ allowed.

**Steps to Create an Organization**
![4-18-tutorialorgs](https://user-images.githubusercontent.com/90662294/134723543-e5719f20-86b4-440a-ab3b-970564b3b2cd.png)
   * Step 1: Create your organization (Links to an external site.): In this step, you create an organization with your current AWS account as the master account. You also invite one AWS account to join your organization, and you create a second account as a member account.
   * Step 2: Create the organizational units (Links to an external site.) Next, you create two organizational units (OUs) in your new organization and place the member accounts in those OUs.
   * Step 3: Create the service control policies  (Links to an external site.)You can apply restrictions to what actions can be delegated to users and roles in the member accounts by using service control policies (SCPs) (Links to an external site.). In this step, you create two SCPs and attach them to the OUs in your organization.
   * Step 4: Testing your organization's policies (Links to an external site.) You can sign in as users from each of the test accounts and see the effects that the SCPs have on the accounts.
* Limits of AWS:
   * Naming Guidelines
      * They must be composed of Unicode characters
      * They must not exceed 250 characters in length
   * Maximum and Minimum Values:
      * ![Limits of AWS](https://user-images.githubusercontent.com/90662294/134723960-a8257aed-6c01-4bcb-a365-4673474ebc8f.PNG)
* Accessing AWS Organization:
   * AWS Management Console: The AWS Organizations console  (Links to an external site.) is a browser-based interface that you can use to manage your organization and your AWS resources. You can perform any task in your organization by using the console.
   * AWS Command Line Tools: With the AWS command line tools, you can issue commands at your system's command line to perform AWS Organizations and AWS tasks. Working with the command line can be faster and more convenient than using the console. The command line tools also are useful if you want to build scripts that perform AWS tasks.
      * AWS provides two sets of command line tools:
         * AWS Command Line Interface  (Links to an external site.) (AWS CLI). For information about installing and using the AWS CLI, see the AWS Command Line Interface User Guide (Links to an external site.).
         * AWS Tools for Windows PowerShell  (Links to an external site.). For information about installing and using the Tools for Windows PowerShell, see the AWS Tools for Windows PowerShell User Guide (Links to an external site.).
   * AWS SDKs: The AWS SDKs consist of libraries and sample code for various programming languages and platforms (for example, Java, Python, Ruby, .NET, iOS, and Android). The SDKs take care of tasks such as cryptographically signing requests, managing errors, and retrying requests automatically. For more information about the AWS SDKs, including how to download and install them, see Tools for Amazon Web Services  (Links to an external site.).
   * AWS Organizations HTTPS Query API: The AWS Organizations HTTPS Query API gives you programmatic access to AWS Organizations and AWS. The HTTPS Query API lets you issue HTTPS requests directly to the service. When you use the HTTPS API, you must include code to digitally sign requests using your credentials. For more information, see Calling the API by Making HTTP Query Requests (Links to an external site.) and the AWS Organizations API Reference (Links to an external site.).


4. Cloud Security
What is Cyber Security?
* the art of protecting networks, devices, and data from unauthorized access or criminal use and the practice of ensuring confidentiality, integrity, and availability of information.

What are the risks to having poor cybersecurity?
* malware erasing your entire system
* an attacker breaking into your system and altering files
* an attacker using your computer to attack others
* an attacker stealing your credit card information and making unauthorized purchases.

How can you improve your cybersecurity?
1. Fimiliarize yourself with thefollowing terms:
  * *_Hacker, attacker, or intruder_* – These terms are applied to the people who seek to exploit weaknesses in software and computer systems for their own gain.
  * _*Malicious code – Malicious code*_ (also called malware) is unwanted files or programs that can cause harm to a computer or compromise data stored on a computer. Various classifications of malicious code include viruses, worms, and Trojan horses.
    * It might require you to actually do something before it infects your computer. This action could be opening an email attachment or going to a particular webpage.
    * Some forms of malware propagate without user intervention and typically start by exploiting a software vulnerability. Once the victim computer has been infected, the malware will attempt to find and infect other computers. This malware can also propagate via email, websites, or network-based software.
    * Some malware claims to be one thing, while in fact doing something different behind the scenes. For example, a program that claims it will speed up your computer may actually be sending confidential information to a remote intruder.
  * *_Vulnerabilities_* – Vulnerabilities are flaws in software, firmware, or hardware that can be exploited by an attacker to perform unauthorized actions in a system. They can be caused by software programming errors. Attackers take advantage of these errors to infect computers with malware or perform other malicious activity.

2. Minimize the risks of cyberattacks by following the basic practices:
  * _*Keep software up to date.*_ Install software patches so that attackers cannot take advantage of known problems or vulnerabilities. Many operating systems offer automatic updates.
  * *_Run up-to-date antivirus software._* A reputable antivirus software application is an important protective measure against known malicious threats. It can automatically detect, quarantine, and remove various types of malware. Be sure to enable automatic virus definition updates to ensure maximum protection against the latest threats.
  * *_Use strong passwords._* Select passwords that will be difficult for attackers to guess, and use different passwords for different programs and devices. It is best to use long, strong passphrases or passwords that consist of at least 16 characters.
  * _*Change default usernames and passwords.*_ Default usernames and passwords are readily available to malicious actors. Change default passwords, as soon as possible, to a sufficiently strong and unique password.
  * _*Implement multi-factor authentication (MFA).*_ Authentication is a process used to validate a user’s identity. Attackers commonly exploit weak authentication processes. MFA uses at least two identity components to authenticate a user’s identity, minimizing the risk of a cyberattacker gaining access to an account if they know the username and password.
  * _*Install a firewall.*_ Firewalls may be able to prevent some types of attack vectors by blocking malicious traffic before it can enter a computer system, and by restricting unnecessary outbound communications. Some device operating systems include a firewall. Enable and properly configure the firewall as specified in the device or system owner’s manual.
  * _*Be suspicious of unexpected emails.*_ Phishing emails are currently one of the most prevalent risks to the average user. The goal of a phishing email is to gain information about you, steal money from you, or install malware on your device. Be suspicious of all unexpected emails.
  
  **THE AIC Triad:** The fundamentals of security (Combination of principles)
  * _Availability_: Systems and networkds must be up and running
    * Information is accessible to authorized user: Alwyas are your fingertips
    * Redundancy: Build services that will always be available
    * Fault tolerance: System will continue to run even when a failute occurs
    * Patching: stability and close security holes
  * _Integrity_: Messages can't be modified without detection
    * Data is stored and trasferred as intended 
    * Hashing: Map data of an arbitrary length to data of a fixed length
    * Digital signatures: Mathermatical scheme to verify the integrity of data. Other end checks and maintains integrity of data to match with signature
    * Certificates: combine with a digital signature to verify an individual or resources 
    * Non-repudiation: provinding proof of integrity 
  * _Confidentiality_: Prevent disclosure of information to unauthorized individuals or systems 
    * Encryption of information 
    * Access controls: rights and permission to resources
    * Steganography : Conceling info within another piece of information (through pictures)
  * _Safety_
    * Excape plants and routes:
      * Best way out of a building or an area
    * Drills 
      * Test and adjust: to analyze how quickly people reacted and can be motified. 
    * Testing Controls: 
      * Run periodic test against physical and digital security
5. Networking & Content Delivery
What is a Network?
* A computer network is just two or more client machines that are connected together, using a network device, to share resources. A network can be logically partitioned to create subnets. A router or switch are used to connect the clients together and enable communications.

Definitions for Computer Networking: 
* Computer Network: It is the interconnection of multiple devices, generally termed as Hosts connected using multiple paths for the purpose of sending/receiving data or media.
![Note 05](https://user-images.githubusercontent.com/90662294/142615466-a972945f-a00a-4cf3-961b-6af3e20e84df.png)
  * The layout pattern using which devices are interconnected is called as network topology. Such as Bus, Star, Mesh, Ring, Daisy chain.
  ![network-topology](https://user-images.githubusercontent.com/90662294/142615593-d4bd8694-93ca-4d90-b3e9-c3bff0e454df.png)

* OSI (Open Systems Interconnection)Model Layers: 
  * Layer 7 - Application: 
    * The application layer is the OSI layer closest to the end user, which means both the OSI application layer and the user interact directly with the software application.
  * Layer 6 - Presentation: 
    * The presentation layer establishes context between application-layer entities, in which the application-layer entities may use different syntax and semantics if the presentation service provides a mapping between them.
  * Layer 5 - Session
    * The session layer controls the dialogues (connections) between computers. It establishes, manages and terminates the connections between the local and remote application.
  * Layer 4 - Transport
    * The transport layer provides the functional and procedural means of transferring variable-length data sequences from a source to a destination host, while maintaining the quality of service functions.
  * Layer 3 - Network
    * The network layer provides the functional and procedural means of transferring variable length data sequences (called packets) from one node to another connected in "different networks".
  * Layer 2 - Data Link
    * The data link layer provides node-to-node data transfer—a link between two directly connected nodes
  * Layer 1 - Physical
    * Responsible for the transmission and reception of unstructured raw data between a device and a physical transmission medium.
* Protocol: the set of rules or algorithms which define the way how two entities can communicate across the network and there exists different protocol defined at each layer of OSI model. Few of such protocols are TCP, IP, UDP, ARP, DHCP, FTP and so on.
* Unique Indentifiers of Network: Host Name: Each device in the network is associated with a unique device name known as Hostname.
* IP Address (Internet Protocol Address): To identify each device in the world-wide-web, Internet Assigned Numbers Authority (IANA) assigns IPv4 (Version 4) address as a unique identifier for each device on the Internet. However there is also an IPv6 (Version 6) scheme available that has more addresses available. _ipconfig_
* Classless Inter-Domain Routing (CIDR): A common method to describe networks is Classless Inter-Domain Routing (CIDR). The CIDR address is expressed as follows:
  * An IP address (which is the first address of the network)
  * Next, a slash character (/)
  * Finally, a number that tells you how many bits of the routing prefix must be fixed or allocated for the network identifier
  * For example, the CIDR address is 192.0.2.0/24. The last number (24) tells you that the first 24 bits must be fixed. The last 8 bits are flexible, which means that 28 (or 256) IP addresses are available for the network, which range from 192.0.2.0 to 192.0.2.255. The fourth decimal digit is allowed to change from 0 to 255.
  * There are two special cases:
    * Fixed IP addresses, in which every bit is fixed, represent a single IP address (for example, 192.0.2.0/32). This type of address is helpful when you want to set up a firewall rule and give access to a specific host.
    * The internet, in which every bit is flexible, is represented as 0.0.0.0/0
* MAC Address (Media Access Control Address): Also known as physical address, is the unique identifier of each host and is associated with the NIC (Network Interface Card).
  * MAC address is assigned to the NIC at the time of manufacturing.
  * Length of the MAC address is : 12-digit/ 6 bytes/ 48 bits
* Port: Port number is a 16-bit integer, hence we have 216 ports available which are categorized as shown below:
  * Well known Ports 0–1023
  * Registered Ports 1024–49151
  * Ephemeral Ports 49152–65535
  * Number of ports: 65,536
  * Range: 0–65535
* Socket: The unique combination of IP address and Port number together are termed as Socket.
* DNS Server (Domain Name System Server): DNS is basically a server which translates web addresses or URL (ex: www.google.com) (Links to an external site.) into their corresponding IP addresses. We don’t have to remember all the IP addresses of each and every website.
* ARP (Address Resolution Protocol): It is used to convert the IP address to its corresponding Physical Address(i.e.MAC Address).
  * used by the Data Link Layer to identify the MAC address of the Receiver’s machine.
* RARP ( Reverse Address Resolution Protocol): As the name suggests, it provides the IP address of the device given a physical address as input. But RARP has become obsolete since the time DHCP has come into the picture.
* The Internet: a global network of smaller networks interconnected using communication protocols that are standardized. The Internet standards describe a framework known as the Internet protocol suite. This model divides methods into a layered system of protocols.
  * These layers are as follows:
    1. Application layer (highest) — concerned with the data(URL, type, etc), where HTTP, HTTPS, etc comes in.
    2. Transport layer — responsible for end-to-end communication over a network.
    3. Network layer — provides a data route.
* The World Wide Web:  a system of Internet servers that support specially formatted documents. The documents are formatted in a markup language called HTML(that supports links, multimedia, etc). These documents are interlinked using hypertext links and are accessible via the Internet.
  * To link hypertext to the Internet, we need:
    1. The markup language, i.e., HTML.
    2. The transfer protocol, e.g., HTTP.
    3. Uniform Resource Locator (URL), the address of the resource.
* URI (Uniform Rosource Identifier): like an address providing a unique global identifier to a resource on the Web. Uniform Resource Locator (URL) is the most commonly used form of a URI.
  * The URL consists mainly of two parts:
    1. The protocol used in the transfer, e.g., HTTP.
    2. The domain name.


6. Compute
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

7. Storage
What is Storage?
* Storage is basically a technology that allows a user to retain digital data onto a medium. It is one of the core components of a computer and in cloud computing, something that you need to understand the differences.

Volatile vs. Non-Volatile
* **Volatile Memory:** Volatile memory is a type of storage whose contents are erased when the system's power is turned off or interrupted. 
  * For example, RAM is volatile. When you are working on a document, it is kept in RAM, and if the computer loses power, your work will be lost. For this reason, you should save your document to a file on a non-volatile storage medium, such as your hard drive.
* **Non-Volatile Memory:** NV or Non-volatile memory is a term used to describe any memory or storage that is saved regardless of the power to the computer is on or off. It is also called persistent storage or permanent storage. 
  * An example of non-volatile memory and storage is a computer hard drive, flash memory, and ROM. If data is stored on a hard drive, it will remain on that drive regardless if the power is interrupted, which is why it is the best place to store your data and documents. Non-volatile memory also stores your computer's time and system settings even when the power is off.
Local Storage Types:
* Read Only Memory (RAM): temporary storage that allows data and programs to be stored in memory in order the operating system to use them. After the operating system has booted up, each program you open, such as the browser you're using to view this page, is loaded into memory while it is running. If too many programs are open, the computer will swap the data in the memory between the RAM and the hard disk drive.
* Hard Drives: can be used to store any data, including pictures, music, videos, text documents, and any files created or downloaded. Also, hard drives store files for the operating system and software programs that run on the computer. The two main types of hard drive are HDD (hard disk drive) and SSD (solid state drive). Below is a table comparing them.
* Optical Drive: uses lasers and lights as its method of reading and writing data. The three standards of optical media are CD (compact disk), DVD (digital versatile disk or digital video disk), and Blu-ray. All standards use the same size disc, but the data is read differently for each. Below is a table of data capacity for each standard.
* Flash Drive: Alternatively referred to as a USB flash drive, data stick, pen drive, memory unit, keychain drive, and thumb drive, a jump drive is a portable storage device. It is often the size of a human thumb (hence the name) and connects to a computer via a USB port. Flash drives are an easy way to store and transfer information between computers and range in sizes from 2 GB to 1 TB.

Storage in the Enterprise:
1. Redundant Array of Independent Disks (RAID): The simplest way to replicate data is to use a Redundant Array of Independent Disks or RAID for short. Depending on the level you use, you can lose a drive and still keep all your data safe. Computers and servers can use a RAID to replicate data across multiple redundant drives in order to ensure data is available
    ![Notes 07](https://user-images.githubusercontent.com/90662294/142610268-ec4f4157-10a2-4635-a0cc-bb457bebc91e.png)
2. File Servers:
3. Network Attached Storage (NAS):A file server is a type of server on a network that is used to provide authorized users with access to files. It has all of the same components that a computer or server has including a CPU, RAM and storage, but the storage used for serving files is generally larger and optimized for serving files. Normally file servers are kept off of the public internet for security reasons, but are available on an internal enterprise network.
4. Storage Area Network (SAN):A Storage Area Network, SAN for short, is a specialized high-speed network that provides access at a raw block-address level. Systems can attach it to servers using technologies like Fiber Channel (FC) or Internet Small Computing System Interface (iSCSI) so that the storage appears to be attached locally rather than connected via a network.

Storage in the Cloud: Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. It’s delivered on demand with just-in-time capacity and costs, and eliminates buying and managing your own data storage infrastructure. This gives you agility, global scale and durability, with “anytime, anywhere” data access.
* Examples: Google Drive, Dropbox, Box.com, Microsoft Onedrive
* How does Cloud Storage work?
  * Cloud storage is purchased from a third party cloud vendor who owns and operates data storage capacity and delivers it over the Internet in a pay-as-you-go model. These cloud storage vendors manage capacity, security and durability to make data accessible to your applications all around the world.
* Benefits of Cloud Storage:
  * Total Cost of Ownership
    * With cloud storage, there is no hardware to purchase, storage to provision, or capital being used for "someday" scenarios. You can add or remove capacity on demand, quickly change performance and retention characteristics, and only pay for storage that you actually use. Less frequently accessed data can even be automatically moved to lower cost tiers in accordance with audit-able rules, driving economies of scale.
  * Time to Deployment
    * When development teams are ready to execute, infrastructure should never slow them down. Cloud storage allows IT to quickly deliver the exact amount of storage needed, right when it's needed. This allows IT to focus on solving complex application problems instead of having to manage storage systems.
  * Information Management
    * Centralizing storage in the cloud creates a tremendous leverage point for new use cases. By using cloud storage lifecycle management policies, you can perform powerful information management tasks including automated tiering or locking down data in support of compliance requirements.

8. Databases
What is a Database? 
* A database is a shared collection of related data used to support the activities of a particular organization.

Properties:
* It is a representation of some aspect of the real world or a collection of data elements (facts) representing real-world information.
* A database is logical, coherent and internally consistent.
* A database is designed, built and populated with data for a specific purpose.
* Each data item is stored in a field.
* A combination of fields makes up a table. For example, each field in an employee table contains data about an individual employee.

Database Management System: A database management system (DBMS) is a collection of programs that enables users to create and maintain databases and control all access to them. The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information.

**Characteristics and Benefits of a Database:**
* The processing power of a database allows it to manipulate the data it houses, so it can:
  * Sort
  * Match
  * Link
  * Aggregate
  * Skip fields
  * Calculate
  * Arrange
* A database can be linked to:
  * A website that is capturing registered users
  * A client-tracking application for social service organizations
  * A medical record system for a health care facility
  * Your personal address book in your email client
  * A collection of word-processed documents
  * A system that issues airline reservations

* Self-describing nature of a database system: A database system is referred to as self-describing because it not only contains the database itself, but also metadata which defines and describes the data and relationships between tables in the database. This information is used by the DBMS software or database users if needed.
* Insulation between program and data: In the file-based system, the structure of the data files is defined in the application programs so if a user wants to change the structure of a file, all the programs that access that file might need to be changed as well.
* Support for multiple views of data: A view is a subset of the database, which is defined and dedicated for particular users of the system. Multiple users in the system might have different views of the system. Each view might contain only the data of interest to a user or group of users.
* Sharing of data and multiuser system: This access is achieved through features called concurrency control strategies. These strategies ensure that the data accessed are always correct and that data integrity is maintained. 
* Control of data redundancy: In some cases, data redundancy still exists to improve system performance, but such redundancy is controlled by application programming and kept to minimum by introducing as little redudancy as possible when designing the database.
* Data Sharing: First, it allows for data sharing among employees and others who have access to the system. Second, it gives users the ability to generate more information from a given amount of data than would be possible without the integration.
* Enforcement of integrity constraints: A database constraint is a restriction or rule that dictates what can be entered or edited in a table such as a postal code using a certain format or adding a valid city in the City field.
* Restriction of unauthorized access: For example, one user might have read-only access (i.e., the ability to read a file but not make changes), while another might have read and write privileges, which is the ability to both read and modify a file. For this reason, a database management system should provide a security subsystem to create and control different types of user accounts and restrict unauthorized access.
* Data Independence:  the system data descriptions or data describing data (metadata) are separated from the application programs.
* Transaction Processing: ensures that data remains consistent and valid during transaction processing even if several users update the same information.
* Provision for multiple views of data: DBMS permits many users to have access to its database either individually or simultaneously. It is not important for users to be aware of how and where the data they access is stored
* Backup and recovery facilities:DBMS permits many users to have access to its database either individually or simultaneously. It is not important for users to be aware of how and where the data they access is stored




