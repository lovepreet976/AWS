# AWS
What is AWS?

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

S3-101
S3 is one of the first services that has been produced by aws.
S3 stands for Simple Storage Service.
S3 provides developers and IT teams with secure, durable, highly scalable object storage.
It is easy to use with a simple web services interface to store and retrieve any amount of data from anywhere on the web.

What is S3?
S3 is a safe place to store the files.
It is Object-based storage, i.e., you can store the images, word files, pdf files, etc.
The files which are stored in S3 can be from 0 Bytes to 5 TB.
It has unlimited storage means that you can store the data as much you want.
Files are stored in Bucket. A bucket is like a folder available in S3 that stores the files.
S3 is a universal namespace, i.e., the names must be unique globally. Bucket contains a DNS address. Therefore, the bucket must contain a unique name to generate a unique DNS address.
If you create a bucket, URL look like:

AWS S3
If you upload a file to S3 bucket, then you will receive an HTTP 200 code means that the uploading of a file is successful.
Advantages of Amazon S3
AWS S3
Create Buckets: Firstly, we create a bucket and provide a name to the bucket. Buckets are the containers in S3 that stores the data. Buckets must have a unique name to generate a unique DNS address.
Storing data in buckets: Bucket can be used to store an infinite amount of data. You can upload the files as much you want into an Amazon S3 bucket, i.e., there is no maximum limit to store the files. Each object can contain upto 5 TB of data. Each object can be stored and retrieved by using a unique developer assigned-key.
Download data: You can also download your data from a bucket and can also give permission to others to download the same data. You can download the data at any time whenever you want.
Permissions: You can also grant or deny access to others who want to download or upload the data from your Amazon S3 bucket. Authentication mechanism keeps the data secure from unauthorized access.
Standard interfaces: S3 is used with the standard interfaces REST and SOAP interfaces which are designed in such a way that they can work with any development toolkit.
Security: Amazon S3 offers security features by protecting unauthorized users from accessing your data.
S3 is a simple key-value store
S3 is object-based. Objects consist of the following:

Key: It is simply the name of the object. For example, hello.txt, spreadsheet.xlsx, etc. You can use the key to retrieve the object.
Value: It is simply the data which is made up of a sequence of bytes. It is actually a data inside the file.
Version ID: Version ID uniquely identifies the object. It is a string generated by S3 when you add an object to the S3 bucket.
Metadata: It is the data about data that you are storing. A set of a name-value pair with which you can store the information regarding an object. Metadata can be assigned to the objects in Amazon S3 bucket.
Subresources: Subresource mechanism is used to store object-specific information.
Access control information: You can put the permissions individually on your files.

EC2
EC2 stands for Amazon Elastic Compute Cloud.
Amazon EC2 is a web service that provides resizable compute capacity in the cloud.
Amazon EC2 reduces the time required to obtain and boot new user instances to minutes rather than in older days, if you need a server then you had to put a purchase order, and cabling is done to get a new server which is a very time-consuming process. Now, Amazon has provided an EC2 which is a virtual machine in the cloud that completely changes the industry.
You can scale the compute capacity up and down as per the computing requirement changes.
Amazon EC2 changes the economics of computing by allowing you to pay only for the resources that you actually use. Rather than you previously buy physical servers, you would look for a server that has more CPU capacity, RAM capacity and you buy a server over 5 year term, so you have to plan for 5 years in advance. People spend a lot of capital in such investments. EC2 allows you to pay for the capacity that you actually use.
Amazon EC2 provides the developers with the tools to build resilient applications that isolate themselves from some common scenarios.
EC2 Pricing Options
AWS EC2
On Demand

It allows you to pay a fixed rate by the hour or even by the second with no commitment.
Linux instance is by the second and windows instance is by the hour.
On Demand is perfect for the users who want low cost and flexibility of Amazon EC2 without any up-front investment or long-term commitment.
It is suitable for the applications with short term, spiky or unpredictable workloads that cannot be interrupted.
It is useful for the applications that have been developed or tested on Amazon EC2 for the first time.
On Demand instance is recommended when you are not sure which instance type is required for your performance needs.
Reserved
It is a way of making a reservation with Amazon or we can say that we make a contract with Amazon. The contract can be for 1 or 3 years in length.
In a Reserved instance, you are making a contract means you are paying some upfront, so it gives you a significant discount on the hourly charge for an instance.
It is useful for applications with steady state or predictable usage.
It is used for those applications that require reserved capacity.
Users can make up-front payments to reduce their total computing costs. For example, if you pay all your upfronts and you do 3 years contract, then only you can get a maximum discount, and if you do not pay all upfronts and do one year contract then you will not be able to get as much discount as you can get If you do 3 year contract and pay all the upfronts.

Types of Reserved Instances:
Standard Reserved Instances
Convertible Reserved Instances
Scheduled Reserved Instances

AWS EC2
Standard Reserved Instances
It provides a discount of up to 75% off on demand. For example, you are paying all up-fronts for 3 year contract.
It is useful when your Application is at the steady-state.
Convertible Reserved Instances
It provides a discount of up to 54% off on demand.
It provides the feature that has the capability to change the attributes of RI as long as the exchange results in the creation of Reserved Instances of equal or greater value.
Like Standard Reserved Instances, it is also useful for the steady state applications.
Scheduled Reserved Instances
Scheduled Reserved Instances are available to launch within the specified time window you reserve.
It allows you to match your capacity reservation to a predictable recurring schedule that only requires a fraction of a day, a week, or a month.
Spot Instances
It allows you to bid for a price whatever price that you want for instance capacity, and providing better savings if your applications have flexible start and end times.
Spot Instances are useful for those applications that have flexible start and end times.
It is useful for those applications that are feasible at very low compute prices.
It is useful for those users who have an urgent need for large amounts of additional computing capacity.
EC2 Spot Instances provide less discounts as compared to On Demand prices.
Spot Instances are used to optimize your costs on the AWS cloud and scale your application's throughput up to 10X.
EC2 Spot Instances will continue to exist until you terminate these instances.
Dedicated Hosts
A dedicated host is a physical server with EC2 instance capacity which is fully dedicated to your use.
The physical EC2 server is the dedicated host that can help you to reduce costs by allowing you to use your existing server-bound software licenses. For example, Vmware, Oracle, SQL Server depending on the licenses that you can bring over to AWS and then they can use the Dedicated host.
Dedicated hosts are used to address compliance requirements and reduces host by allowing to use your existing server-bound server licenses.
It can be purchased as a Reservation for up to 70% off On-Demand price.

What is EBS?
EBS stands for Elastic Block Store.
EC2 is a virtual server in a cloud while EBS is a virtual disk in a cloud.
Amazon EBS allows you to create storage volumes and attach them to the EC2 instances.
Once the storage volume is created, you can create a file system on the top of these volumes, and then you can run a database, store the files, applications or you can even use them as a block device in some other way.
Amazon EBS volumes are placed in a specific availability zone, and they are automatically replicated to protect you from the failure of a single component.
EBS volume does not exist on one disk, it spreads across the Availability Zone. EBS volume is a disk which is attached to an EC2 instance.
EBS volume attached to the EC2 instance where windows or Linux is installed known as Root device of volume.
EBS Volume Types
AWS EBS

Amazon EBS provides two types of volume that differ in performance characteristics and price. EBS Volume types fall into two parts:
SSD-backed volumes
HDD-backed volumes
SSD
SSD stands for solid-state Drives.
In June 2014, SSD storage was introduced.
It is a general purpose storage.
It supports up to 4000 IOPS which is quite very high.
SSD storage is very high performing, but it is quite expensive as compared to HDD (Hard Disk Drive) storage.
SSD volume types are optimized for transactional workloads such as frequent read/write operations with small I/O size, where the performance attribute is IOPS.
AWS EBS

SSD is further classified into two parts:
General Purpose SSD
Provisioned IOPS SSD
General Purpose SSD
General Purpose SSD is also sometimes referred to as a GP2.
It is a General purpose SSD volume that balances both price and performance.
You can get a ratio of 3 IOPS per GB with up to 10,000 IOPS and the ability to burst up to 3000 IOPS for an extended period of time for volumes at 3334 GiB and above. For example, if you get less than 10,000 IOPS, then GP2 is preferable as it gives you the best performance and price.
Provisioned IOPS SSD
It is also referred to as IO1.
It is mainly used for high-performance applications such as intense applications, relational databases.
It is designed for I/O intensive applications such as large relational or NOSQL databases.
It is used when you require more than 10,000 IOPS.
HDD
It stands for Hard Disk Drive.
HDD based storage was introduced in 2008.
The size of the HDD based storage could be between 1 GB to 1TB.
It can support up to 100 IOPS which is very low.
AWS EBS
Throughput Optimized HDD (st1)
It is also referred to as ST1.
Throughput Optimized HDD is a low-cost HDD designed for those applications that require higher throughput up to 500 MB/s.
It is useful for those applications that require the data to be frequently accessed.
It is used for Big data, Data warehouses, Log processing, etc.
It cannot be a boot volume, so it contains some additional volume. For example, if we have Windows server installed in a C: drive, then C drive cannot be a Throughput Optimized Hard disk, D: drive or some other drive could be a Throughput Optimized Hard disk.
The size of the Throughput Hard disk can be 500 GiB to 16 TiB.
It supports up to 500 IOPS.
Cold HDD (sc1)
It is also known as SC1.
It is the lowest cost storage designed for the applications where the workloads are infrequently accessed.
It is useful when data is rarely accessed.
It is mainly used for a File server.
It cannot be a boot volume.
The size of the Cold Hard disk can be 500 GiB to 16 TiB.
It supports up to 250 IOPS.
Magnetic Volume
It is the lowest cost storage per gigabyte of all EBS volume types.
It is ideal for the applications where the data is accessed infrequently
It is useful for applications where the lowest storage cost is important.
Magnetic volume is the only hard disk which is bootable. Therefore, we can say that it can be used as a boot volume.

What is DynamoDB?

Amazon DynamoDB is a fast and flexible NoSQL database service for all applications that require consistent single-digit millisecond latency at any scale.
It is a fully managed database that supports both document and key-value data models.
Its flexible data model and performance makes it a great fit for mobile, web, gaming, ad-tech, IOT, and many other applications.
It is stored in SSD storage.
It is spread across three geographically data centres.
DynamoDB
Because of its availability in three geographically data centres, It consists of two different types of consistency models:

Eventual Consistent Reads
Strongly Consistent Reads
Eventual Consistent Reads

It maintains consistency across all the copies of data which is usually reached within a second. If you read a data from DynamoDB table, then the response would not reflect the most recently completed write operation, and if you repeat to read the data after a short period, then the response would be the lattest update. This is the best model for Read performance.

Strongly Consistent Reads

A strongly consistent read returns a result that reflects all writes that received a successful response prior to the read.

Note: If your application wants the data from DynamoDB table immediately, then choose the Strongly Consistent Read model. If you can wait for a second, then choose the Eventual Consistent Model.
AWS DynamoDB Throughput Capacity
DynamoDB throughput capacity depends on the read/write capacity modes for performing read/write operation on tables.

DynamoDB
There are two types of read/write capacity modes:

Provisioned mode
On-demand mode
Provisioned mode
It defines the maximum amount of capacity that an application can use from a specified table.
In a provisioned mode, you need to specify the number of reads and writes per second required by the application.
If the limit of Provisioned mode throughput capacity is exceeded, then this leads to the request throttling.
A provisioned mode is good for applications that have predictable and consistent traffic.
DynamoDB
The Provisioned mode consists of two capacity units:

Read Capacity unit
Write Capacity unit
Read Capacity Unit

The total number of read capacity units depends on the item size, and read consistency model.
Read Capacity unit represents two types of consistency models:
Strongly Consistent model: Read Capacity Unit represents one strong consistent read per second for an item up to 4KB in size.
Eventually Consistent model: Read Capacity Unit represents two eventually consistent reads per second for an item up to 4KB in size.
DynamoDB will require additional read capacity units when an item size is greater than 4KB. For example, if the size of an item is 8KB, 2 read capacity units are required for strongly consistent read while 1 read capacity unit is required for eventually consistent read.
Write Capacity Unit

The total number of write capacity unit depends on the item size.
Only 1 write capacity unit is required for an item up to size 1KB.
DynamoDB will require additional write capacity units when size is greater than 1KB. For example, if an item size is 2KB, two write capacity units are required to perform 1 write per second.
For example, if you create a table with 20 write capacity units, then you can perform 20 writes per second for an item up to 1KB in size.
On-Demand mode
DynamoDB on-demand mode has a flexible new billing option which is capable of serving thousands of requests per second without any capacity planning.
On-Demand mode offers pay-per-request pricing for read and write requests so that you need to pay only for what you use, thus, making it easy to balance costs and performance.
In On-Demand mode, DynamoDb accommodates the customer's workload instantly as the traffic level increases or decreases.
On-Demand mode supports all the DynamoDB features such as encryption, point-in-time recovery, etc except auto-scaling
If you do not perform any read/write, then you just need to pay for data storage only.
On-Demand mode is useful for those applications that have unpredictable traffic and database is very complex to forecast.

What is VPC
VPC stands for Virtual Private Cloud.
Amazon Virtual Private Cloud (Amazon VPC) provides a logically isolated area of the AWS cloud where you can launch AWS resources in a virtual network that you define.
You have complete control over your virtual networking environment, including a selection of your IP address range, the creation of subnets, and configuration of route tables and network gateways.
You can easily customize the network configuration for your Amazon Virtual Private Cloud. For example, you can create a public-facing subnet for web servers that can access to the internet and can also place your backend system such as databases or application servers to a private-facing subnet.
You can provide multiple layers of security, including security groups and network access control lists, to help control access to Amazon EC2 instances in each subnet.

Architecture of VPC
The outer line represents the region, and the region is us-east-1. Inside the region, we have VPC, and outside the VPC, we have internet gateway and virtual private gateway. Internet Gateway and Virtual Private Gateway are the ways of connecting to the VPC. Both these connections go to the router in a VPC and then router directs the traffic to the route table. Route table will then direct the traffic to Network ACL. Network ACL is the firewall or much like security groups. Network ACL are statelist which allows as well as deny the roles. You can also block the IP address on your Network ACL. Now, move over to the security group that accesses another line against the EC2 instance. It has two subnets, i.e., Public and Private subnet. In public subnet, the internet is accessible by an EC2 instance, but in private subnet, an EC2 instance cannot access the internet on their own. We can connect the instances. To connect an instance, move over to the public subnet and then it SSH to the private subnet. This is known as jump boxes. In this way, we can connect an instance in public subnet to an instance in private subnet.

Some ranges are reserved for private subnet:

10.0.0.0 - 10.255.255.255 (10/8 prefix)
172.16.0.0 - 172.31.255.255 (172.16/12 prefix)
192.168.0.0 - 192.168.255.255 (192.108/16 prefix)
What can we do with a VPC?
Launch instances in a subnet of your choosing. We can choose our own subnet addressing.
We can assign custom IP address ranges in each subnet.
We can configure route tables between subnets.
We can create an internet gateway and attach it to our VPC.
It provides much better security control over your AWS resources.
We can assign security groups to individual instances.
We also have subnet network access control lists (ACLS).
VPC Peering
VPC Peering is a networking connection that allows you to connect one VPC with another VPC through a direct network route using private IP addresses.
Instances behave as if they were on the same private network.
You can peer VPC's with other AWS accounts as well as other VPCs in the same account.
Peering is in a star configuration, i.e., 1 VPC peers other 4 VPCs.
It has no Transitive Peering!!.
Note: Non-Transitive Peering means the networks that you want to connect are directly linked.
You can peer between regions. Suppose you have one VPC in one region and other VPC in another region, then you can peer the VPCs between different regions.



