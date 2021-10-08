# Notes 02:
## Cloud Economics Billing & Support
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


