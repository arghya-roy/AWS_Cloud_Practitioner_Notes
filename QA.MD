- TCO is deprecated but still can appear
- simple monthly calculator is now pricing calculator

## What charges are included in the comparison of aws and on premiese Total cost of ownership (TCO)?

- Data center security
- 
## What costs must be addressed in the comparison of aws and on premiese Total cost of ownership (TCO)?

- Storage hardware
- physical server
- Network infasturecture of data center
- The cost of purchasing and installing server hardware in the on-premises data.
- The cost of administering the infrastructure, including operating system and software installations, patches, backups, and recovering from failures.
- Power consumption of the data center
- Labor costs to replace old servers
- **SERVER COST**
- **STORAGE COST**
- **NETWORK COST**
- **IT LABOR COST**
- **Compute costs**



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
- ability to focus on revenue generating activities

### economical advantage of using aws?
- reduced total cost of ownership ( TCO )
- reduced operational expenditure ( opex )
- ( credit line for startup is not currect )

### A business must keep its data near to its core consumers. which cloud advantage satisfies the requirements?
- global footprint ( The AWS Global Cloud Infrastructure is the most secure, extensive, and reliable cloud platform, offering over 200 fully featured services from data centers globally. )

### A client wants to develop and construct a new workload on AWS Cloud but lacks the necessary technical skills in AWS-related technologies. Which of the following AWS programs may a client use to accomplish that goal?
- AWS Partner Network Consulting Partners

### A customer would like to design and build a new workload on AWS Cloud but does not have the AWS-related software technical expertise in-house. Which of the following AWS programs can a customer take advantage of to achieve that outcome?
- AWS Partner Network Consulting Partners
- 
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
- patching database software

### Which AWS technologies aid in cost estimation? (Select three.)

- Cost allocation tags
- AWS Simple Monthly Calculator
- AWS Total Cost of Ownership (TCO) Calculator 
- ( no tool exists named cost estimator )
- ( Detailed billing report is not for estamating )

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

### Which principal are used while architecting apps for aws cloud reliability?
- design for automated failover recovery
- use multiple az

### Which AWS service or functionality allows customers to encrypt data stored in Amazon S3 during the storage process?

Server-side encryption
### aws provides which of the following security related service?

- data encryption
- aws trusted advisor security check
- ( not automted penetration testing and aws does not provide mfa with physical token, it provides with solf token )

### What is raised when a business deploys web server across several aws regions?
- availability ( not durability )

### Which of the following tasks may be used to improve Amazon EC2 costs? (Select two.)

- Implementing Auto Scaling groups to add and remove instances based on demand. Most Voted
- Purchasing Reserved Instances. 

### A firm wishes to develop a new line of business application. Which design concepts should be applied in accordance with the AWS Well-Architected Framework? (Select two.)
- Decouple the AWS Cloud architecture to break up monolithic deployments. 
- Design elasticity into the AWS Cloud design.

### How do Amazon's massive economies of scale help customers?
- Periodic price reductions as the result of Amazon's operational efficiencies

### Before transferring an environment to the AWS Cloud, a cloud practitioner must receive AWS compliance reports. How are these reports produced?
- Contact the AWS Compliance team or Download the reports from AWS Artifact ??

### in the case of an environmental disruption, a company needs to make sure its infrastructure is structured for fault tolerance and business continuity.Which parts of the AWS architecture should the organization replicate?

az 
### A corporation anticipates a brief increase in internet traffic for their application. The program cannot be interrupted during the traffic spike. In addition, the organization must reduce costs while increasing flexibility. To achieve these needs, which Amazon EC2 instance type should the organization use?

on demand instances 


### A business may be required to operate its workload exclusively in its on-premises data center due to performance and regulatory limitations. Which Amazon Web Services (AWS) services or resources should the business utilize? (Select two.)
- aws outpost
- aws snowball edge

### Which component of the AWS architecture permits global computing and storage deployment?
region or az ??

### Which service enables users to store data in the Amazon Web Services cloud?

- A. Amazon EFS **Most Voted**
- B. Amazon Redshift
- C. Amazon RDS
- D. Amazon VPC

### What is AWS Storage Gateway's purpose?
It connects on-premises data storage to the AWS Cloud. ( It transports petabytes of data to and from AWS.- is incorrect )


### what can most cost effectively cut a rising start-computing up's costs ?
It provides on demand respources for peak uses

### Best practice for root user

- MFA
- delete access keys

### Which AWS Support package is the LEAST costly and gives 24-hour access to AWS customer care and communities?
basic support plan

### Which AWS feature enables a business to use consumption levels across different member accounts?
Consolidated billing ( not SCP )

### which oppourtunites does aws provide for clients interested in learning about cloud security in an instruction led settings?

- AWS Online Tech Talks
- AWS Classroom Training

### A business wishes to launch a worldwide commercial application using Amazon Elastic Compute Cloud (Amazon EC2). The deployment solution should be constructed with the `greatest degree` of redundancy and fault tolerance possible. According to this scenario, the following Amazon EC2 instances should be deployed:

- across multiple Availability Zones in two AWS Regions

### Which tool is most suited for integrating the billing of previously distinct AWS accounts?
Consolidated billing

### enables aws customers to control billing expense allocation
tagging resources

### The application of a business has a variable start and finish time. what pricing option is most cost effective?

spot instance

### AWS's pay-as-you-go pricing model:
reduces operational expenditures. ( because cap ex does not exist in cloud )

### A business has optimized its workload by using certain AWS services in order to increase efficiency and minimize costs. Which cost management best practice does this case demonstrate?

Architecture optimization

### Which of the following procedures should a client perform while doing penetration testing on Amazon Web Services (AWS)?
Request and wait for approval from the customer's internal security team, and then conduct testing.

### A business has chosen to shift its production workloads to the Amazon Web Services (AWS) Cloud. Which activities may assist in lowering operating expenses associated with the migration? (Select two.)
- Reduce overprovisioned instances.
- Use managed services.

### What AWS feature relates to a customer's flexibility to scale up and down applications to meet changeable demand?
elasticity

### Which feature of cloud computing can AWS exhibit via its capacity to provide reduced variable prices as a consequence of big purchase volumes?
Economies of scale

### unauthorised purposes = Intrusion attempts: = aws abuse team / aws trust and safety team

### Which AWS service should a business use to check the compliance of AWS resource settings on a `continual basis`?
AWS config

### Which AWS service or feature enables a business to track, monitor, and control its AWS expenses and consumption over time?
cost explorer ( not budget )

### A business has a 500 TB image repository that has to be moved to Amazon Web Services (AWS) for processing. Which AWS service is the most cost-effective way to import this data?
snowball ( s3 will be used to store not import )

### email - developer support
### phone - business support

### Which AWS Support package includes access to architectural and operational assessments, as well as 24/7 email, online chat, and phone support from Senior Cloud Support Engineers?
Enterprise ( because - architectural and operational assessments )

### Which is the minimum AWS Support plan that includes Infrastructure Event Management without additional costs?
Enterprise

### A major corporation has a workload that demands on-premises hardware. The organization want to continue using the same management and control plane services as it does on AWS. Which Amazon Web Services (AWS) offering should the business employ to achieve these requirements?

AWS outpost

### Which of the following is not a recommended approach for IAM user management? (Select two.)
- Require IAM users to store their passwords in raw text
- Disable multi-factor authentication (MFA) for IAM users

### identify illegal and harmfl activities - 
guardduty

### How can an AWS customer with an AWS Basic Support package get AWS technical support?
aws discussion forum ( trusted advisor is not right )

### What can be utilized to automate and manage AWS setups that are safe, well-architected, and multi-account?
AWS control tower

### GIve 1 hour goal response time - business

### Which of the following are characteristics of Amazon S3? (Choose two.)
- An object store
- An object store
- s3 is not a global file system.it's a global namespace with DNS compliant names for buckets


### Which of the following security-related actions are available at no cost?
- Accessing forums, blogs, and whitepapers

### Which of the Reserved Instance (RI) pricing models can change the attributes of the RI as long as the exchange results in the creation of RIs of equal or greater value?
- Convertible RIs

### Which AWS feature will reduce the customer’s total cost of ownership (TCO)?

- Elastic computing

### Which of the following services will automatically scale with an expected increase in web traffic?

- Elastic Load Balancing

### Which AWS services should be used for read/write of constantly changing data? (Choose two.)
- RDS
- EFS

### AWS Personal Health Dashboard provides alerts and remediation guidance when AWS is experiencing events that may impact you. While the Service Health Dashboard displays the general status of AWS services, Personal Health Dashboard gives you a personalized view into the performance and availability of the AWS services underlying your AWS resources.

### Which AWS service provides a customized view of the health of specific AWS services that power a customer’s workloads running on AWS?

- AWS Personal Health Dashboard

### Which AWS Cost Management tool allows you to view the most granular data about your AWS bill?
- cost explorer ( not AWS Cost and Usage report )

### What can users access from AWS Artifact?

- AWS security and compliance documents

