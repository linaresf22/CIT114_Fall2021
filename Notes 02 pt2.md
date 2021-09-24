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


