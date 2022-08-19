## 6 pillar of aws well-architected framework -  ( aws dependability piller is same as aws reliability piller )
https://aws.amazon.com/blogs/apn/the-6-pillars-of-the-aws-well-architected-framework/

## Support plans 
https://github.com/arghya-roy/AWS_Certified_Solutions_Architect_Associate_notes/blob/main/aws_support_plans/Readme.MD

## Difference between elasticity and scalability -
- In sample way we can say that elasticity is a manual process means when you need more you increased service and when you dont need you decrease that. But Scalability is automated process means depending on load your services will be created or deleted automatically.
- https://stackoverflow.com/questions/9587919/what-is-the-difference-between-scalability-and-elasticity
- **trick** When the question is about scaling then if there is option called elasticity then select elasticity. if there is option called scalability then select scalability. If there are both option elasticity and scalability then choose scalability.

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

## AWS Device farm

AWS Device Farm is an application testing service that lets you improve the quality of your web and mobile apps by testing them across an extensive range of desktop browsers and real mobile devices; without having to provision and manage any testing infrastructure.

## AWS ground station?

AWS Ground Station is a fully managed service that lets you control satellite communications, process data, and scale your operations without having to worry about building or managing your own ground station infrastructure. Satellites are used for a wide variety of use cases, including weather forecasting, surface imaging, communications, and video broadcasts. Ground stations form the core of global satellite networks. 


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

- AWS Control Tower is a service that enables you to enforce and manage governance rules for security, operations, and compliance at scale across all your organizations and accounts in the AWS Cloud.
- It automatically sets up AWS Organizations to organize accounts and implement 
SCPs (Service Control Policies)


## Amazon appstream

Amazon AppStream 2.0 is a fully managed application streaming service that provides users with instant access to their desktop applications from anywhere.

## Stateful vs stateless application

In contrast, a stateful application saves data about each client session and uses that data the next time the client makes a request. When an application is stateless, the server does not store any state about the client session. Instead, the session data is stored on the client and passed to the server as needed.

## AWS Knowledge Center

- advised to customer about frequently asked billing questions.
- Contains the most frequent & common questions and request


## aws personal health dashboard

- gives information about planned events that are now occuring or may occur in future  and may impact an AWS account.
- AWS Personal Health Dashboard provides alerts and guidance for AWS events that might affect your environment.


## aws service health dashboard

- shows the general status of aws services
