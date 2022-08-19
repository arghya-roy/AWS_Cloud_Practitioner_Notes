## 6 pillar of aws well-architected framework -  ( aws dependability piller is same as aws reliability piller )
https://aws.amazon.com/blogs/apn/the-6-pillars-of-the-aws-well-architected-framework/

## Support plans 
https://github.com/arghya-roy/AWS_Certified_Solutions_Architect_Associate_notes/blob/main/aws_support_plans/Readme.MD

## Difference between elasticity and scalability -
- In sample way we can say that elasticity is a manual process means when you need more you increased service and when you dont need you decrease that. But Scalability is automated process means depending on load your services will be created or deleted automatically.
- https://stackoverflow.com/questions/9587919/what-is-the-difference-between-scalability-and-elasticity


### Trusted advisor suggests us about 
- Cost optimization  (unassociated Elastic IP addresses)
- Performance (Examples include analyzing EBS throughput and latency, compute usage of EC2 instances, and configurations on CloudFront. )
- Security  ( s3 buvket public or not )
- Fault tolerance ( auto scaling is multi az or not )
- Service limits ( saving plan or reserve instances all are used or still some available )

## Trusted Advisor – Support Plans

### 7 CORE CHECKS
- **Basic & Developer Support plan**
- S3 Bucket Permissions
- Security Groups – Specific Ports Unrestricted
- IAM Use (one IAM user minimum)
- MFA on Root Account
- EBS Public Snapshots
- RDS Public Snapshots
- Service Limits

### FULL CHECKS
- **Business & Enterprise Support plan**
- Full Checks available on the 5 categories
- Ability to set CloudWatch alarms when reaching limits
- Programmatic Access using AWS Support API


## AWS Abuse team or Trust & Safety team

 The AWS Trust & Safety team can assist you when AWS resources are used to engage in the following types of abusive behavior:

### Spam: 
You are receiving unwanted emails from an AWS-owned IP address, or AWS resources are used to spam websites or forums.
### Port scanning:
Your logs show that one or more AWS-owned IP addresses are sending packets to multiple ports on your server. You also believe this is an attempt to discover unsecured ports.
### Denial-of-service (DoS) attacks: 
Your logs show that one or more AWS-owned IP addresses are used to flood ports on your resources with packets. You also believe that this is an attempt to overwhelm or crash your server or the software running on your server.
### Intrusion attempts:
Your logs show that one or more AWS-owned IP addresses are used to attempt to log in to your resources.
### Hosting prohibited content:
You have evidence that AWS resources are used to host or distribute prohibited content, such as illegal content or copyrighted content without the consent of the copyright holder.
### Distributing malware: 
You have evidence that AWS resources are used to distribute software that was knowingly created to compromise or cause harm to computers or machines that it's installed on.

- If you suspect that AWS resources are used for abusive purposes, contact the AWS Trust & Safety team using the Report Amazon AWS abuse form, or by contacting abuse@amazonaws.com. Provide all the necessary information, including logs in plaintext, email headers, and so on, when you submit your request.

- The AWS Trust & Safety team will use the information that you provide in this form to investigate and attempt to resolve the incident you have reported. We might share your information, if it is necessary for the investigation of your report.
Note: AWS Support can't assist with reports of abuse or questions about notifications from the AWS Trust & Safety team. If you have questions for the AWS Trust & Safety team, reply directly to their email.


## AWS local zone
- Places AWS compute, storage, database, and other selected AWS services closer to end users to run latency-sensitive applications
- Extend your VPC to more locations – “Extension of an AWS Region”
- Compatible with EC2, RDS, ECS, EBS, ElastiCache, Direct Connect … 
- Example:
    - AWS Region: N. Virginia (us-east-1)
    - AWS Local Zones: Boston, Chicago, Dallas, Houston, Miami, …

## AWS WaveLength
- WaveLength Zones are infrastructure deployments embedded within the telecommunications providers’ datacenters at the edge of the 5G networks
- Brings AWS services to the edge of the 5G networks
- Example: EC2, EBS, VPC…
- Ultra-low latency applications through 5G networks
- Traffic doesn’t leave the Communication Service Provider’s (CSP) network
- High-bandwidth and secure connection to the parent AWS Region
- No additional charges or service agreements
- Use cases: Smart Cities, ML-assisted diagnostics, Connected Vehicles, Interactive Live Video Streams, AR/VR, Real-time Gaming, 


## What is an outpost in AWS?
- An Outpost is a pool of AWS compute and storage capacity deployed at a customer site. AWS operates, monitors, and manages this capacity as part of an AWS Region. You can create subnets on your Outpost and specify them when you create AWS resources such as EC2 instances, EBS volumes, ECS clusters, and RDS instances.

- Hybrid Cloud: businesses that keep an on premises infrastructure alongside a cloud 
infrastructure
- Therefore, two ways of dealing with IT systems: 
     -  One for the AWS cloud (using the AWS console, CLI, and AWS APIs)
     -  One for their on premises infrastructure 
     -  
- AWS Outposts are “server racks” that offers the same AWS infrastructure, services, APIs & tools to build your own applications on premises just as in the cloud
- AWS will setup and manage “Outposts Racks” within your on premises infrastructure and you can start leveraging AWS services on-premises
- You are responsible for the Outposts Rack physical security.

- Benefits:
     - Low-latency access to on-premises systems
     - Local data processing
     - Data residency
     - Easier migration from on-premises to the cloud
     - Fully managed service


## What is AWS Artifact?

AWS Artifact provides on-demand downloads of AWS security and compliance documents, such as AWS ISO certifications, **Payment Card Industry (PCI), and Service Organization Control (SOC) reports.** You can submit the security and compliance documents (also known as audit artifacts) to your auditors or regulators to demonstrate the security and compliance of the AWS infrastructure and services that you use. You can also use these documents as guidelines to evaluate your own cloud architecture and assess the effectiveness of your company's internal controls. AWS Artifact provides documents about AWS only. AWS customers are responsible for developing or obtaining documents that demonstrate the security and compliance of their companies. For more information, see Shared Responsibility Model.


## what is AWS quickstart?

Quick Starts are built by AWS solutions architects and partners to help you deploy popular technologies on AWS, based on AWS best practices for security and high availability. These accelerators reduce hundreds of manual procedures into just a few steps, so you can build your production environment quickly and start using it immediately.

## What is aws pinpoint? ( like sns )

Amazon Pinpoint is a flexible and scalable outbound and inbound marketing communications service. You can connect with customers over channels like email, SMS, push, voice or in-app messaging. Amazon Pinpoint is easy to set up, easy to use, and is flexible for all marketing communication scenarios.

## What is aws worklink?

Amazon WorkLink is a fully managed service that lets you provide your employees secure, one-click access to your internal corporate websites and web apps using their mobile phones.

## What is aws APPSync?

AWS AppSync is a serverless GraphQL and Pub/Sub API service that simplifies building modern web and mobile applications. AWS AppSync GraphQL APIs simplify application development by providing a single endpoint to securely query or update data from multiple databases, microservices, and APIs.

## What is a AWS Partner Network?

The AWS Partner Network (APN) is the global partner program for technology and consulting businesses who leverage Amazon Web Services (AWS) to build solutions and services for customers. The APN helps companies build, market, and sell their AWS offerings by providing valuable business, technical, and marketing support.

## Who are AWS Technology Partners?

APN Technology Partners provide software solutions that are either hosted on, or integrated with, the AWS platform. Technology Partners include Independent Software Vendors (ISVs), SaaS, PaaS, Developer Tools, Management, and Security Vendors.


## Who are APN Consulting Partners?

APN Consulting Partners are professional services firms that help customers design, architect, build, migrate, and manage their workloads and applications on AWS. Consulting Partners include System Integrators, Strategic Consultancies, Agencies, Managed Service Providers, and Value-Added Resellers.

- Benifit of this 
   - access to "go-to-market" resources
   - training and certification
   - market development funding ( MDF )
   - Innovation sandbox credit
   - Increased visibility to AWs customer and aws filed terms.

## What charges are included in the comparison of aws and on premiese Total cost of ownership (TCO)?

- Data center security
- 
## What costs must be addressed in the comparison of aws and on premiese Total cost of ownership (TCO)?

- Storage hardware
- physical server
- Network infasturecture of data center


## Tasks that require root user credentials

- **Change your account settings.** This includes the account name, email address, root user password, and root user access keys. Other account settings, such as contact information, payment currency preference, and AWS Regions, don't require root user credentials.

- **Restore IAM user permissions.** If the only IAM administrator accidentally revokes their own permissions, you can sign in as the root user to edit policies and restore those permissions.

- **Activate IAM access to the Billing and Cost Management console.**

- **View certain tax invoices.** An IAM user with the aws-portal:ViewBilling permission can view and download VAT invoices from AWS Europe, but not AWS Inc. or Amazon Internet Services Private Limited (AISPL).

- **Close your AWS account.**

- **Change your AWS Support plan or Cancel your AWS Support plan**. For more information, see IAM for AWS Support.

- **Register as a seller in the Reserved Instance Marketplace.**

- **Configure an Amazon S3 bucket to enable MFA (multi-factor authentication).**

- **Edit or delete an Amazon Simple Storage Service (Amazon S3) bucket policy that includes an invalid virtual private cloud (VPC) ID or VPC endpoint ID.**

- **Sign up for GovCloud.**

## AWS Control tower

AWS Control Tower is a service that enables you to enforce and manage governance rules for security, operations, and compliance at scale across all your organizations and accounts in the AWS Cloud.

## Amazon appstream

Amazon AppStream 2.0 is a fully managed application streaming service that provides users with instant access to their desktop applications from anywhere.

## Stateful vs stateless application

In contrast, a stateful application saves data about each client session and uses that data the next time the client makes a request. When an application is stateless, the server does not store any state about the client session. Instead, the session data is stored on the client and passed to the server as needed.

## AWS Knowledge Center

- advised to customer about frequently asked billing questions.
- Contains the most frequent & common questions and request






---

### Which of the following is a critical design concept for architecting cloud applications?
Implement elasticity

### Cloud services main proposition is to provide elasticity through horizontal scaling.

### Which of the following tasks is required to deploy a PCI-compliant workload on AWS? 
- **ans** Use an AWS service that is in scope for PCI compliance and apply PCI controls at the application layer
- PCI Compliance is an ongoing process that aids in preventing security breaches and payment card data theft in the present and in the future

### The AWS Value Proposition -
- (ans) no long term commitment is needed
- others are -
     - **Agility**	Speed, Experimentation, Innovation
     - **Elasticity**	Scale on demand, Eliminate wasted capacity
     - **Flexibility**	Broad set of products, **Low to no cost to entry**
     - **Security**	Amazon has acquired many compliance certifications, Shared responsibility model


### After sdudying the aws cost and usage report you detect a billing problem, which course of action should be done to rectify this?
- Opened a detailed case related to billing and submit it to aws support to help.

### Compute capacity availability defines amount of server and storage resources that are available to the databases in an instance. So it is the responsibility of aws in shared responsibility model.

### Configure network time protocol (NTP) server uses a fleet of satellite-connected and atomic reference clocks in each AWS Region to deliver accurate current time readings of the Coordinated Universal Time (UTC) global standard. So it is the responsibility of aws in shared responsibility model.

### data integrity authentication is a process of obtaining assurance that data has not been modified since an authentication code or digital signature was created for that data. So it is the responsibility of customer in shared responsibility model.

### Protecting againest IP spoofing and packet sniffing is the responsibility of aws in shared responsibility model.

### Before transferring an environment to the AWS Cloud, a cloud practitioner must receive AWS compliance reports. How are these reports produced?
- Download the reports from AWS Artifact ( The word "Before" makes sense )

### Which change management actions, according to the AWS Well-Architected Framework, should be followed to ensure AWS Cloud reliability? (Select two.)
- Use AWS Config to generate an inventory of AWS resources
-  Use AWS CloudTrail to record AWS API calls into an auditable log file.

### Enable failover accross several aws region 
- route 53
- Global Accelerator ( When you set up your accelerator with Global Accelerator, you associate the static IP addresses to regional endpoints in one or more AWS Regions )

### WHat we can do using aws market place?
- Sell solutions to other aws users
- Buy third party software that runs on aws

### Which aws service is natively supported by aws snowball edge?
- Snowball Edge devices have **Amazon S3 and Amazon EC2** compatible endpoints available

### Which responsibility are shared between aws and customer in shared responsibility mode?
- Patch management
- configuraration management
- Awareness and training

### In the case of an environmental disruption, a company needs to make sure its infrastructure is structured for fault tolerance and business continuity. Which parts of the AWS architecture should the organization replicate?
- Regions ( availability zone is not right answer because here the keyword is "environmental"

### On Amazon EC2, a business hosts a web application in a Docker container. Which of the following duties is AWS in charge of?
-  Performing hardware maintenance in the AWS facilities that run the AWS Cloud

### Which qualities make aws cloud computing advantageous?
- compute capacity that is adjusted on demand.
- enhanced security

### advantage of aws cloud to host infastructure
- no upfront commitment
- users have the ability to provision resource on demand.

### Which of the following are benefits of Amazon Web Services' cloud computing platform? (Select two.)
- AWS manages the maintenance of the cloud infrastructure
- AWS manages capacity planning for physical servers


### An administrator must fast install and begin utilizing a popular IT product. What resources are available to the administrator?
- AWS Quick Start reference deployments

### Which aspect of AWS infrastructure enables global deployment of compute and storage?
- region ( key - global )

### agility -
- agility provides the means of users to provision resources in a minutes.


### Which aws service is responsible for do health check of your application automatically?
beanstalk

### which aws product or service enables business to monitor and clisify their expenditure at a precise level?
- cost allocation tags

### What may aid the evaluation of a cloud based application?
- Aws professional services
- aws partner network ( APN )

### The term "fault tolerance" relates to the following:
the built-in redundancy of an application's components

### A business needs to guarantee that users of the AWS Management Console adhere to password complexity guidelines. How can a business customize the difficulty of its passwords?
Using an AWS IAM account password policy

### A organization with an AWS Support plan for developers established an Amazon RDS database but is unable to connect to it. To get this degree of help, who should the developer contact?
 AWS Support using a support case
 
### Which AWS service enables you to monitor and debug distributed applications end to end?

AWS X-Ray


### Which variables impact aws cloud cost?

- outbound data transfer without acceleration
- compute resources that are currently in use

### Tract confuguration changes
aws config

### track aws api
cloudtrail

### What does the AWS Cloud bring clients in terms of increased execution speed and agility? (Select two.)
- Readily available resources with low provisioning times 
- Scalable compute capacity

### Which AWS Cloud best practice makes advantage of cloud computing's flexibility and agility?
- Dynamically and predictively scale to meet usage demands

### advantage of aws computing 
- agility
- elasticity

### what are the immidiate advantage of aws cloud computing 
- increased agility
- capital expenses are replaced by variable cost

### economical advantage of using aws?
- reduced total cost of ownership ( TCO )
- reduced operational expenditure ( opex )
- ( credit line for startup is not currect )

### A business must keep its data near to its core consumers. which cloud advantage satisfies the requirements?
- global footprint ( The AWS Global Cloud Infrastructure is the most secure, extensive, and reliable cloud platform, offering over 200 fully featured services from data centers globally. )

### A client wants to develop and construct a new workload on AWS Cloud but lacks the necessary technical skills in AWS-related technologies. Which of the following AWS programs may a client use to accomplish that goal?
- AWS Partner Network Consulting Partners

### Which AWS solution enables rapid setup and management of a new multi-account AWS environment?

AWS Control Tower

### A business wishes to downsize its infrastructure in order to save money. At what stages should a business downsize? (Select two.)

- Rightsize before a migration occurs to the cloud. 
- Rightsize continuously after the cloud onboarding process.

### Which Amazon EC2 pricing model is dynamically adjusted in response to EC2 instance availability and demand?
- Spot instances
- In the new model, the Spot prices are more predictable, updated less frequently, and are determined by supply and demand for Amazon EC2 spare capacity, not bid prices.

### Which choices do users have when contacting AWS Support? (Select two.)

- Use live chat functionality. 
- Call the customer service phone number.

### A business must track and anticipate AWS expenditures and use. Additionally, the organization must configure event-driven alert alerts that are triggered when expenditure limitations are exceeded. Which Amazon Web Services (AWS) offering or technology should the business employ to achieve these requirements?

- aws cloudwatch ( not budget, key - event-driven alert ).

### IT functions which aws do -

- backing up databases
- installing operating system ( does not configure os firewall )

### Which AWS technologies aid in cost estimation? (Select three.)

- Cost allocation tags
- AWS Simple Monthly Calculator
- AWS Total Cost of Ownership (TCO) Calculator 
- ( no tool exists named cost estimator )

### Which services are available for application deployment?

- aws beanstalk
- aws opsworks ( managed chef and puppet )

### A business needs handle a huge volume of data from social network accounts using high-throughput graphical queries. Which AWS service will assist the business in developing a cloud architecture that satisfies these criteria?

- Amazon Neptune

### Graphical query - Neptune

### On an Amazon EC2 instance, a batch job takes 5 hours to complete. Monthly, the quantity of data to be processed doubles, and the time required to process it is proportionate. What is the optimal cloud architecture for meeting this escalating demand?

Distribute the application across multiple EC2 instances and run the workload in parallel.

### The continue lowering in aws cloud price is a result of the following -
economies of scale

### A business wishes to deliver managed Windows virtual desktops and programs through secure network connections to its distant workers. Which AWS services does the business have access to in order to achieve these requirements? (Select two.)
- Amazon AppStream 2.0
- Amazon WorkSpaces

### Which AWS services are globally specified rather than regionally defined? (Select two.)

- route53
- cloudfront

### A business has specified the Amazon Web Services (AWS) resources it requires for a new application. The business must determine the expenses associated with operating the application on AWS. What actions should the business take to comply with this stipulation?

Use the AWS Pricing Calculator to generate an approximate dollar amount.

### generate warning based on monthly bill estimate
cloudwatch.

### Which AWS service or functionality is by default highly available?

aurora

### Which resource is the MOST EFFECTIVE for keeping current on AWS security announcements?
AWS Security Bulletins

### anticipate of cost while application already running - aws cost explorer / aws cpst and usage report/
### anticipate of cost before deploing application - pricing calculator

### A big firm often has a single Amazon Web Services (AWS) account. What are the benefits of repurposing a single AWS account to create additional AWS accounts? (Select two.)
- It allows for administrative isolation between different workloads.
- Having multiple accounts reduces the risks associated with malicious activity targeted at a single account. 

### WAF can be associated with 
      - API  gateway
      - cloudfront
      - ALB
      
### Which AWS services are available for file storage? (Select two.)
- s3
- EBS
- ( Storage gateway is not a storage it is a path bw on prem to cloud )

### A business uses an Amazon EC2 Auto Scaling policy in conjunction with an Application Load Balancer to restore sick apps running on Amazon EC2 instances automatically. This activity pertains to which pillar of the AWS Well-Architected Framework?

reliability

### Global infasturecture = global footprint = global reach

### Steady state = a state or condition of a system or process that does not change in time = reserved instance

### AWS to lower its total cost of ownership by 
minimizing capital expenditure

