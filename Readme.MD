## 6 pillar of aws well-architected framework -
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
