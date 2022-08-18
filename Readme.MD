## 6 pillar of aws well-architected framework -
https://aws.amazon.com/blogs/apn/the-6-pillars-of-the-aws-well-architected-framework/

## Support plans 
https://github.com/arghya-roy/AWS_Certified_Solutions_Architect_Associate_notes/blob/main/aws_support_plans/Readme.MD

## Difference between elasticity and scalability -
- In sample way we can say that elasticity is a manual process means when you need more you increased service and when you dont need you decrease that. But Scalability is automated process means depending on load your services will be created or deleted automatically.
- https://stackoverflow.com/questions/9587919/what-is-the-difference-between-scalability-and-elasticity

### Which of the following is a critical design concept for architecting cloud applications?
Implement elasticity

### Cloud services main proposition is to provide elasticity through horizontal scaling.

### Which of the following tasks is required to deploy a PCI-compliant workload on AWS? 
- **ans** Use an AWS service that is in scope for PCI compliance and apply PCI controls at the application layer
- PCI Compliance is an ongoing process that aids in preventing security breaches and payment card data theft in the present and in the future

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

