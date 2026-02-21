---
layout: exam
---

# Practice Exam 1

1. AWS allows users to manage their resources using a web based user interface. What is the name of this interface?
    - A. AWS CLI.
    - B. AWS API.
    - C. AWS SDK.
    - D. AWS Management Console.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

2. Which of the following is an example of horizontal scaling in the AWS Cloud?
    - A. Replacing an existing EC2 instance with a larger, more powerful one.
    - B. Increasing the compute capacity of a single EC2 instance to address the growing demands of an application.
    - C. Adding more RAM capacity to an EC2 instance.
    - D. Adding more EC2 instances of the same size to handle an increase in traffic.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

3. You have noticed that several critical Amazon EC2 instances have been terminated. Which of the following AWS services would help you determine who took this action?
    - A. Amazon Inspector.  [security assessment service] 
    - B. AWS CloudTrail.  [ CloudTrail records all API calls and actions taken by users, roles, or services in your AWS account]
    - C. AWS Trusted Advisor. [recommendations for cost optimization, performance, security, and fault tolerance.]
    - D. EC2 Instance Usage Report. [gives usage statistics]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

4. Which of the below options are related to the reliability of AWS? (Choose TWO)
    - A. Applying the principle of least privilege to all AWS resources. [realted to security]
    - B. Automatically provisioning new resources to meet demand. 
    - C. All AWS services are considered Global Services, and this design helps customers serve their international users.[about global reach and availability]
    - D. Providing compensation to customers if issues occur. [business policy (Service Level Agreements)]
    - E. Ability to recover quickly from failures.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, E
    </details>

5. Which statement is true regarding the AWS Shared Responsibility Model?
    - A. Responsibilities vary depending on the services used.
    - B. Security of the IaaS services is the responsibility of AWS.
    - C. Patching the guest OS is always the responsibility of AWS. [ Iaas- customer respobsible, Pass/Saas - AWS responsible ]
    - D. Security of the managed services is the responsibility of the customer. [AWS takes responsibility on service itself]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

6. You have set up consolidated billing for several AWS accounts. One of the accounts has purchased a number of reserved instances for 3 years. Which of the following is true regarding this scenario?
    - A. The Reserved Instance discounts can only be shared with the master account. [ applied across linked account in family]
    - B. All accounts can receive the hourly cost benefit of the Reserved Instances.
    - C. The purchased instances will have better performance than On-demand instances. [Ri dont change performance ]
    - D. There are no cost benefits from using consolidated billing; It is for informational purposes only. [ Consolidated provide savings]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

7. A company has developed an eCommerce web application in AWS. What should they do to ensure that the application has the highest level of availability?
    - A. Deploy the application across multiple Availability Zones and Edge locations. [ for content delivery improve performance cant ensure availability]
    - B. Deploy the application across multiple Availability Zones and subnets. [improve network multiple subnets ]
    - C. Deploy the application across multiple Regions and Availability Zones. 
    - D. Deploy the application across multiple VPC’s and subnets. [can help isolation or multi tenancy]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

8. What does AWS Snowball provide? (Choose TWO)
    - A. Built-in computing capabilities that allow customers to process data locally. [Snowcone also but snowmobile cant]
    - B. A catalog of third-party software solutions that customers need to build solutions and run their businesses. [AWS Marketplace]
    - C. A hybrid cloud storage between on-premises environments and the AWS Cloud. [AWS Storage Gateway]
    - D. An Exabyte-scale data transfer service that allows you to move extremely large amounts of data to AWS. [Snowmobile for exabytes transfer, TB to PB Snowmobile]
    - E. Secure transfer of large amounts of data into and out of the AWS. [Core physical purpose of AWS SNOW]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
    </details>

9. A company has an AWS Enterprise Support plan. They want quick and efficient guidance with their billing and account inquiries. Which of the following should the company use?
    - A. AWS Health Dashboard. [status of aws services/alerts]
    - B. AWS Support Concierge. [special team to provide account and billing assistance ]
    - C. AWS Customer Service. [General service ]
    - D. AWS Operations Support. [not an AWS Service]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

10. A Japanese company hosts their applications on Amazon EC2 instances in the Tokyo Region. The company has opened new branches in the United States, and the US users are complaining of high latency. What can the company do to reduce latency for the users in the US while minimizing costs?
    - A. Applying the Amazon Connect latency-based routing policy. [Amzon Connect = contanct center its Amzon route 53]
    - B. Registering a new US domain name to serve the users in the US. [domain name doest solve latency its just address]
    - C. Building a new data center in the US and implementing a hybrid model.[misleading use aws region]
    - D. Deploying new Amazon EC2 instances in a Region located in the US.[deploying instance brings compute resource closer to US users]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

11. An organization has a large number of technical employees who operate their AWS Cloud infrastructure. What does AWS provide to help organize them into teams and then assign the appropriate permissions for each team?
    - A. IAM roles. [Roles are temporray access not for grouping]
    - B. IAM users. [Represent individual entity]
    - C. IAM user groups. [group multiple IAM USERS together]
    - D. AWS Organizations. [manage multiple aws account]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

12. A company has decided to migrate its Oracle database to AWS. Which AWS service can help achieve this without negatively impacting the functionality of the source database?
    - A. AWS OpsWorks.[config managmenet service [Chef/Puppet] ]  [OPSHUB- desktop applcication for AWS SNOW [CLI Tool]]
    - B. AWS Database Migration Service. [migrate db to AWS] [oracle to oracle] [ oracle to aws] both supported
    - C. AWS Server Migration Service. [migrate virtual machine/servers]
    - D. AWS Application Discovery Service. [helps plan migration by discovering on premisses application and dependencies ]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

13. Adjusting compute capacity dynamically to reduce cost is an implementation of which AWS cloud best practice?
    - A. Build security in every layer. [related to security]
    - B. Parallelize tasks. [performance optimization ]
    - C. Implement elasticity. [Elasticity means the ability to scale resources up or down automatically based on demand, you avoid over provisioning leading to cost savings]
    - D. Adopt monolithic architecture. [opposite of best practice reduces flexibility and scalability ]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

14. What are the benefits of having infrastructure hosted in AWS? (Choose TWO)
    - A. Increasing speed and agility.
    - B. There is no need to worry about security. [Security is shared responsibility ]
    - C. Gaining complete control over the physical infrastructure.[AWS manages physical only customer manage virtual]
    - D. Operating applications on behalf of customers.[aws manages only platform and services but operations managed by customer only]
    - E. All of the physical security and most of the data/network security are taken care of for you.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
    </details>

15. What is the advantage of the AWS-recommended practice of "decoupling" applications?
    - A. Allows treating an application as a single, cohesive unit. [describles monolithic]
    - B. Reduces inter-dependencies so that failures do not impact other components of the application.
    - C. Allows updates of any monolithic application quickly and easily. [Harder to update because tightly bound]
    - D. Allows tracking of any API call made to any AWS service. [AWS Cloudtrail]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

16. Which of the following helps a customer view the Amazon EC2 billing activity for the past month?
    - A. AWS Budgets. [lets you set custom threshold]
    - B. AWS Pricing Calculator. [estimate future costs]
    - C. AWS Systems Manager [operational management for aws resources ]
    - D. AWS Cost & Usage Reports.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

17. What do you gain from setting up consolidated billing for five different AWS accounts under another master account?
    - A. AWS services’ costs will be reduced to half the original price.
    - B. The consolidated billing feature is just for organizational purpose. [provides real cost benefits like sharing Reserved Instance discounts and volume pricing across accounts]
    - C. Each AWS account gets volume discounts. [usage across all linked accounts is aggregated, accounts can collectively qualify for volume discounts]
    - D. Each AWS account gets five times the free-tier services capacity. [applied at account level not at linked accounts]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

18. What should you do in order to keep the data on EBS volumes safe? (Choose TWO)
    - A. Regularly update firmware on EBS devices. [AWS manages customer cant access]
    - B. Create EBS snapshots.
    - C. Ensure that EBS data is encrypted at rest. [using KMS]
    - D. Store a backup daily in an external drive.
    - E. Prevent any unauthorized access to AWS data centers. [physcial layer of data center is aws responsibility]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, C
    </details>

19. One of the most important AWS best-practices to follow is the cloud architecture principle of elasticity. How does this principle improve your architecture’s design?
    - A. By automatically scaling your on-premises resources based on changes in demand. [elasticity applies to cloud not on prem resources]
    - B. By automatically scaling your AWS resources using an Elastic Load Balancer. [distributes traffic ]
    - C. By reducing interdependencies between application components wherever possible. [describles decoupling]
    - D. By automatically provisioning the required AWS resources based on changes in demand.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

20. A startup company is operating on limited funds and is extremely concerned about cost overruns. Which of the below options can be used to notify the company when their monthly AWS bill exceeds $2000? (Choose TWO)
    - A. Setup a CloudWatch billing alarm that triggers an SNS notification when the threshold is exceeded.
    - B. Configure the Amazon Simple Email Service to send billing alerts to their email address on a daily basis. [Amazon SES if for sending custom emails not for billing alets]
    - C. Configure the AWS Budgets Service to alert the company when the threshold is exceeded.
    - D. Configure AWS CloudTrail to automatically delete all AWS resources when the threshold is exceeded. [cloudtrail is for logging api]
    - E. Configure the Amazon Connect Service to alert the company when the threshold is exceeded.[connect is cloud contanct center unrelated to billing]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, C
    </details>

21. What does Amazon CloudFront use to distribute content to global users with low latency?
    - A. AWS Global Accelerator. [improves availability and performance by routing traffic through the AWS global network]
    - B. AWS Regions.
    - C. AWS Edge Locations. [CloudFront caches content at edge locations. This ensures content is delivered from the location closest to the user, reducing latency.]
    - D. AWS Availability Zones.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

22. What does the "Principle of Least Privilege" refer to?
    - A. You should grant your users only the permissions they need when they need them and nothing more.
    - B. All IAM users should have at least the necessary permissions to access the core AWS services.[Not all users need access to core services.] 
    - C. All trusted IAM users should have access to any AWS service in the respective AWS account. [Even trusted users shouldn’t have unrestricted access. ]
    - D. IAM users should not be granted any permissions; to keep your account safe.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

23. Which of the following does NOT belong to the AWS Cloud Computing models?
    - A. Platform as a Service (PaaS).
    - B. Infrastructure as a Service (IaaS).
    - C. Software as a Service (SaaS).
    - D. Networking as a Service (NaaS).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

24. The identification process of an online financial services company requires that new users must complete an online interview with their security team. The completed recorded interviews are only required in the event of a legal issue or a regulatory compliance breach. What is the most cost-effective service to store the recorded videos?
    - A. S3 Intelligent-Tiering. [designed for unkown pattern or chaning pattern]
    - B. AWS Marketplace. [digital catalog of third part servies]
    - C. Amazon S3 Glacier Deep Archive.
    - D. Amazon EBS. [block storage for ec2 for active workloads expensive than glacier not for rarely accessd criteria ]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

25. Which service provides DNS in the AWS cloud?
    - A. Route 53.
    - B. AWS Config. [configuration tracking and compliance auditing]
    - C. Amazon CloudFront.
    - D. Amazon EMR. [big data processing using frameworks like Hadoop and Spark, not DNS.]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

26. Hundreds of thousands of DDoS attacks are recorded every month worldwide. What service does AWS provide to help protect AWS Customers from these attacks? (Choose TWO)
    - A. AWS Shield.
    - B. AWS Config.
    - C. Amazon Cognito. [Cognito handles user authentication and identity management]
    - D. AWS WAF.
    - E. AWS KMS. [KMS is for encryption key management]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
    </details>

27. A company is deploying a new two-tier web application in AWS. Where should the most frequently accessed data be stored so that the application’s response time is optimal?
    - A. AWS OpsWorks.
    - B. AWS Storage Gateway.[Storage Gateway connects on-premises environments with AWS cloud storage. It’s not designed for high-speed, frequently accessed application data.]
    - C. Amazon EBS volume. [Fast but not the best choice for caching frequently accessed data because it still requires disk I/O]
    - D. Amazon ElastiCache. [specifically designed to store frequently accessed data in memory, providing sub-millisecond latency]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

28. You want to run a questionnaire application for only one day (without interruption), which Amazon EC2 purchase option should you use?
    - A. Reserved instances. [1-3 year commitment,cost-effective for long-term workloads, not short-term one-day use.]
    - B. Spot instances.[cheap but terminated anytime if aws needs it]
    - C. Dedicated instances.[expensive and  for hardware dedicated]
    - D. On-demand instances.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

29. You are working on a project that involves creating thumbnails of millions of images. Consistent uptime is not an issue, and continuous processing is not required. Which EC2 buying option would be the most cost-effective?
    - A. Reserved Instances. [1-3 year commitment,cost-effective for long-term workloads, not short-term one-day use.]
    - B. On-demand Instances. [flexible and reliable but expensive compared to workloads dont require guaranteed uptime ]
    - C. Dedicated Instances. [expensive and unecessary]
    - D. Spot Instances. [Spot Instances are the most cost-effective option for workloads that can tolerate interruptions and since thumbnail generation is a batch job doesnt require continnuous uptime]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

30. Which of the following can be described as a global content delivery network (CDN) service?
    - A. AWS VPN. [VPN provides secure connectivity between on-premises networks and AWS]
    - B. AWS Direct Connect. [Direct Connect establishes a dedicated network connection between your data center and AWS]
    - C. AWS Regions.
    - D. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

31. Which of the following services allows customers to manage their agreements with AWS?
    - A. AWS Artifact. [provides on-demand access to AWS’s compliance reports and agreements
]    - B. AWS Certificate Manager. [Manages SSL/TLS certificates]
    - C. AWS Systems Manager. [operational management of AWS resources ]
    - D. AWS Organizations. [manage multiple AWS accounts]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

32. Which of the following are examples of AWS-Managed Services, where AWS is responsible for the operational and maintenance burdens of running the service? (Choose TWO)
    - A. Amazon VPC. [customers are responsible for configuring, managing, and maintaining their own subnets, routing]
    - B. Amazon DynamoDB. [fully managed NoSQL database service , AWS handles scaling, replication, patching, and availability]
    - C. Amazon Elastic MapReduce. [EMR simplifies running big data frameworks like Hadoop and Spark, but customers still need to manage clusters, scaling and job configurations]
    - D. AWS IAM. [AWS handles the operational aspects (availability, scaling, security of the IAM system itself). Customers only configure policies and roles.]
    - E. Amazon Elastic Compute Cloud. [EC2 provides virtual servers, but customers are responsible for managing the OS, patches, scaling and availability of their instances.]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
    </details>

33. Your company has a data store application that requires access to a NoSQL database. Which AWS database offering would meet this requirement?
    - A. Amazon Aurora.
    - B. Amazon DynamoDB.
    - C. Amazon Elastic Block Store.
    - D. Amazon Redshift. [ Redshift is a data warehouse optimized for analytics and SQL queries]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

34. As part of the Enterprise support plan, who is the primary point of contact for ongoing support needs?
    - A. AWS Identity and Access Management (IAM) user.
    - B. Infrastructure Event Management (IEM) engineer. [service provdied but not point of contanct]
    - C. AWS Consulting Partners. [can provide guidance support but are external not part of AWS]
    - D. Technical Account Manager (TAM).

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

35. How can you view the distribution of AWS spending in one of your AWS accounts?
    - A. By using Amazon VPC console.
    - B. By contacting the AWS Support team.
    - C. By using AWS Cost Explorer.
    - D. By contacting the AWS Finance team.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

36. Which of the following must an IAM user provide to interact with AWS services using the AWS Command Line Interface (AWS CLI)?
    - A. Access keys.
    - B. Secret token.
    - C. UserID.
    - D. User name and password.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

37. You have AWS Basic support, and you have discovered that some AWS resources are being used maliciously, and those resources could potentially compromise your data. What should you do?
    - A. Contact the AWS Customer Service team. [deals wiht account and billing issues]
    - B. Contact the AWS Abuse team.
    - C. Contact the AWS Concierge team. [only for Enterprise ]
    - D. Contact the AWS Security team. [manages internal security but report malicious to Abuse]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

38. Select TWO examples of the AWS shared controls.
    - A. Patch Management. [[Shared Responsibility]
    - B. IAM Management. [Customer Responsibility]
    - C. VPC Management. [Customer Responsibility]
    - D. Configuration Management.[Shared Responsibility]
    - E. Data Center operations. [AWS Responsibility]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, D
    </details>

39. In order to implement best practices when dealing with a “Single Point of Failure,” you should attempt to build as much automation as possible in both detecting and reacting to failure. Which of the following AWS services would help? (Choose TWO)
    - A. ELB.
    - B. Auto Scaling.
    - C. Amazon Athen. [query service for anayalizing data in s3]
    - D. ECR. [storing container images]
    - E. Amazon EC2. 

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, B
    </details>

40. A company is planning to host an educational website on AWS. Their video courses will be streamed all around the world. Which of the following AWS services will help achieve high transfer speeds?
    - A. Amazon SNS. [mssg and notifications]
    - B. Amazon Kinesis Video Streams. [processing video streams for analytics or machine learning]
    - C. AWS CloudFormation. [iac code]
    - D. Amazon CloudFront.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

41. A developer is planning to build a two-tier web application that has a MySQL database layer. Which of the following AWS database services would provide automated backups for the application?
    - A. A MySQL database installed on an EC2 instance. [no automated backups we are responsible for managing backups]
    - B. Amazon Aurora.
    - C. Amazon DynamoDB. [no-sql]
    - D. Amazon Neptune. [graph based databsase]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

42. What is the AWS service that enables AWS architects to manage infrastructure as code?
    - A. AWS CloudFormation.
    - B. AWS Config. [tracking resource configurations and compliance]
    - C. Amazon SES.
    - D. Amazon EMR.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A
    </details>

43. Under the shared responsibility model, which of the following is the responsibility of AWS?
    - A. Client-side encryption. [customer managed]
    - B. Configuring infrastructure devices. [AWS is responsible for configuring and maintaining the infrastructure devices (like routers, switches, and hypervisors) that run the AWS cloud.]
    - C. Server-side encryption. [AWS provides this but choosing it to enable is our responsiblity]
    - D. Filtering traffic with Security Groups. [customer manage sg to control taffice towards thier resources]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B
    </details>

44. What does the AWS Health Dashboard provide? (Choose TWO)
    - A. Detailed troubleshooting guidance to address AWS events impacting your resources.
    - B. Health checks for Auto Scaling instances.
    - C. Recommendations for Cost Optimization. [AWS Trusted Advisor]
    - D. A dashboard detailing vulnerabilities in your applications.
    - E. Personalized view of AWS service health.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: A, E
    </details>

45. You have deployed your application on multiple Amazon EC2 instances. Your customers complain that sometimes they can’t reach your application. Which AWS service allows you to monitor the performance of your EC2 instances to assist in troubleshooting these issues?
    - A. AWS Lambda.
    - B. AWS Config.
    - C. Amazon CloudWatch. [monitoring service that collects and tracks metrics, logs, and events for EC2 and other AWS resources]
    - D. AWS CloudTrail. [CloudTrail records API calls and user activity for auditing]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

46. Your company is developing a critical web application in AWS, and the security of the application is a top priority. Which of the following AWS services will provide infrastructure security optimization recommendations?
    - A. AWS Shield. [DDos]
    - B. AWS Management Console.
    - C. AWS Secrets Manager.[Secrets Manager securely stores and rotates secrets (like API keys, passwords)]
    - D. AWS Trusted Advisor. [Trusted Advisor provides real-time guidance to help you provision resources following AWS best practices]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>

47. Which of the following is not a benefit of Amazon S3? (Choose TWO)
    - A. Amazon S3 provides unlimited storage for any type of data.
    - B. Amazon S3 can run any type of application or backend system. [s3 is storage not compute cant run]
    - C. Amazon S3 stores any number of objects, but with object size limits.[max 5TB per object]
    - D. Amazon S3 can be scaled manually to store and retrieve any amount of data from anywhere.[scales automatically not manually]
    - E. Amazon S3 provides 99.999999999% (11 9’s) of data durability.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: B, D
    </details>

48. In the AWS Shared responsibility Model, which of the following are the responsibility of the customer? (Choose TWO)
    - A. Disk disposal.
    - B. Controlling physical access to compute resources.
    - C. Patching the Network infrastructure.
    - D. Setting password complexity rules.
    - E. Configuring network access rules.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D, E
    </details>

49. What does AWS provide to deploy popular technologies such as IBM MQ on AWS with the least amount of effort and time?
    - A. Amazon Aurora.
    - B. Amazon CloudWatch.
    - C. AWS Quick Start reference deployments. [uick Starts are automated reference deployments built by AWS and partners. They use CloudFormation templates to rapidly deploy popular technologies (like IBM MQ, SAP, Active Directory, etc.)]
    - D. AWS OpsWorks.

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: C
    </details>

50. An organization has decided to purchase an Amazon EC2 Reserved Instance (RI) for three years in order to reduce costs. It is possible that the application workloads could change during the reservation period. What is the EC2 Reserved Instance (RI) type that will allow the company to exchange the purchased reserved instance for another reserved instance with higher computing power if they need to?
    - A. Elastic RI. [nothing like this distractor]
    - B. Premium RI. [nothing like this distractor]
    - C. Standard RI. [provide biggest discount but not so flexible cannot be exachanged with different instance family and only modifications withing same family]
    - D. Convertible RI.[ exchange your Reserved Instance for another RI with different instance families, operating systems, or tenancies during the reservation period. ideal since worloads change with time ]

    <details markdown=1><summary markdown='span'>Answer</summary>
      Correct answer: D
    </details>
