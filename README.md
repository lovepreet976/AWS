# AWS
What is AWS?
ADVERTISEMENT

ADVERTISEMENT

AWS stands for Amazon Web Services.
The AWS service is provided by the Amazon that uses distributed IT infrastructure to provide different IT resources available on demand. It provides different services such as infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS).
Amazon launched AWS, a cloud computing platform to allow the different organizations to take advantage of reliable IT infrastructure.
Uses of AWS
A small manufacturing organization uses their expertise to expand their business by leaving their IT management to the AWS.
A large enterprise spread across the globe can utilize the AWS to deliver the training to the distributed workforce.
An architecture consulting company can use AWS to get the high-compute rendering of construction prototype.
A media company can use the AWS to provide different types of content such as ebox or audio files to the worldwide files.
Pay-As-You-Go
Based on the concept of Pay-As-You-Go, AWS provides the services to the customers.
AWS provides services to customers when required without any prior commitment or upfront investment. Pay-As-You-Go enables the customers to procure services from AWS.
Computing
Programming models
Database storage
Networking
AWS

Advantages of AWS

1) Flexibility
We can get more time for core business tasks due to the instant availability of new features and services in AWS.
It provides effortless hosting of legacy applications. AWS does not require learning new technologies and migration of applications to the AWS provides the advanced computing and efficient storage.
AWS also offers a choice that whether we want to run the applications and services together or not. We can also choose to run a part of the IT infrastructure in AWS and the remaining part in data centres.

2) Cost-effectiveness
AWS requires no upfront investment, long-term commitment, and minimum expense when compared to traditional IT infrastructure that requires a huge investment.

3) Scalability/Elasticity
Through AWS, autoscaling and elastic load balancing techniques are automatically scaled up or down, when demand increases or decreases respectively. AWS techniques are ideal for handling unpredictable or very high loads. Due to this reason, organizations enjoy the benefits of reduced cost and increased user satisfaction.

4) Security
AWS provides end-to-end security and privacy to customers.
AWS has a virtual infrastructure that offers optimum availability while managing full privacy and isolation of their operations.
Customers can expect high-level of physical security because of Amazon's several years of experience in designing, developing and maintaining large-scale IT operation centers.
AWS ensures the three aspects of security, i.e., Confidentiality, integrity, and availability of user's data.

What is IAM?
IAM stands for Identity Access Management.
IAM allows you to manage users and their level of access to the aws console.
It is used to set users, permissions and roles. It allows you to grant access to the different parts of the aws platform.
AWS Identity and Access Management is a web service that enables Amazon Web Services (AWS) customers to manage users and user permissions in AWS.
With IAM, Organizations can centrally manage users, security credentials such as access keys, and permissions that control which AWS resources users can access.
Without IAM, Organizations with multiple users must either create multiple user accounts, each with its own billing and subscriptions to AWS products or share an account with a single security credential. Without IAM, you also don't have control about the tasks that the users can do.
IAM enables the organization to create multiple users, each with its own security credentials, controlled and billed to a single aws account. IAM allows the user to do only what they need to do as a part of the user's job.

Features of IAM
Centralised control of your AWS account: You can control creation, rotation, and cancellation of each user's security credentials. You can also control what data in the aws system users can access and how they can access.
Shared Access to your AWS account: Users can share the resources for the collaborative projects.
Granular permissions: It is used to set a permission that user can use a particular service but not other services.
Identity Federation: An Identity Federation means that we can use Facebook, Active Directory, LinkedIn, etc with IAM. Users can log in to the AWS Console with same username and password as we log in with the Active Directory, Facebook, etc.
Multifactor Authentication: An AWS provides multifactor authentication as we need to enter the username, password, and security check code to log in to the AWS Management Console.
Permissions based on Organizational groups: Users can be restricted to the AWS access based on their job duties, for example, admin, developer, etc.
Networking controls: IAM also ensures that the users can access the AWS resources within the organization's corporate network.
Provide temporary access for users/devices and services where necessary: If you are using a mobile app and storing the data in AWS account, you can do this only when you are using temporary access.
Integrates with many different aws services: IAM is integrated with many different aws services.
Supports PCI DSS Compliance: PCI DSS (Payment Card Industry Data Security Standard) is a compliance framework. If you are taking credit card information, then you need to pay for compliance with the framework.
Eventually Consistent: IAM service is eventually consistent as it achieves high availability by replicating the data across multiple servers within the Amazon's data center around the world.
Free to use: AWS IAM is a feature of AWS account which is offered at no additional charge. You will be charged only when you access other AWS services by using IAM user.

What is a Role?
A role is a set of permissions that grant access to actions and resources in AWS. These permissions are attached to the role, not to an IAM User or a group.
An IAM User can use a role in the same AWS account or a different account.
An IAM User is similar to an IAM User; role is also an AWS identity with permission policies that determine what the identity can and cannot do in AWS.
A role is not uniquely associated with a single person; it can be used by anyone who needs it.
A role does not have long term security credential, i.e., password or security key. Instead, if the user uses a role, temporarily security credentials are created and provided to the user.
You can use the roles to delegate access to users, applications or services that generally do not have access to your AWS resources.
Situations in which "IAM Roles" can be used:
Sometimes you want to grant the users to access the AWS resources in your AWS account.
Sometimes you want to grant the users to access the AWS resources in another AWS account.
It also allows the mobile app to access the AWS resources, but not want to store the keys in the app.
It can be used to grant access to the AWS resources which have identities outside of AWS.
It can also be used to grant access to the AWS resources to the third party so that they can perform an audit on AWS resources.

Following are the important terms associated with the "IAM Roles":
Delegation: Delegation is a process of granting the permissions to the user to allow the access to the AWS resources that you control. Delegation sets up the trust between a trusted account (an account that owns the resource) and a trusting account (an account that contains the users that need to access the resources).
The trusting and trusted account can be of three types:
Same account
Two different accounts under the same organization control
Two different accounts owned by different organizations.
To delegate permission to access the resources, an IAM role is to be created in the trusting account that has the two policies attached.

Permission Policy: It grants the user with a role the needed permissions to carry out the intended tasks.

Trust Policy: It specifies which trusted account members can use the role.

Federation: Federation is a process of creating the trust relationship between the external service provider and AWS. For example, Facebook allows the user to login to different websites by using their facebook accounts.
Trust policy: A document was written in JSON format to define who is allowed to use the role. This document is written based on the rules of the IAM Policy Language.
Permissions policy: A document written in JSON format to define the actions and resources that the role can use. This document is based on the rules of the IAM Policy Language.
Permissions boundary: It is an advanced feature of AWS in which you can limit the maximum permissions that the role can have. The permission boundaries can be applied to IAM User or IAM role but cannot be applied to the service-linked role.
Principal: A principal can be AWS root account user, an IAM User, or a role. The permissions that can be granted in one of the two ways:
Attach a permission policy to a role.
The services that support resource-based policies, you can identify the principal in the principal element of policy attached to the resource.
Cross-account access: Roles vs Resource-Based Policies: It allows you to grant access to the resources in one account to the trusted principal in another account is known as cross-account access. Some services allow you to attach the policy directly, known as Resource-Based policy. The services that support Resource-Based Policy are Amazon S3 buckets, Amazon SNS, Amazon SQS Queues.

