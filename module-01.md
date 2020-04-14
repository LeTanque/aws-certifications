# Module 01

## Topics

- Introduction to cloud computing
- Advantages of cloud computing
- Introduction to Amazon Web Services (AWS)
- AWS Cloud Adoption Framework (AWS CAF)

## Objectives

- Define different types of cloud computing models
- Describe six advantages of cloud computing
- Recognize the main AWS service categories and core services
- Review the AWS Cloud Adoption Framework (AWS CAF)

### Notes

#### Intro to Cloud Computing

Cloud computing describes the utlization of networked servers to provide services and content?

Cloud computing is the on-demand delivery of compute power, db, storage, apps, and other IT resources via the internet with pay as you go pricing.

3 models of cloud service:
IaaS = Infrastructure as a Service
PaaS = Platform as a Service
SaaS = Software as a Service

IaaS
Most control over IT resources. 

PaaS
Removes need to manage hardware solution.

SaaS
Provides complete product. End user applications. You do not have to think about how the service is maintained. SaaS is a web based email application.

3 Cloud Computing deployment models

Cloud
Hybrid
On-premises (private cloud)

Cloud

On Premises
Used to augment traditional IT infrastructures to increase resource utlization

AWS vs Trad IT
ACL = access control list
Security groups is like firewalls
Elastic Load Balancing and Amazon VPC (virt private cloud) is like router/network pipe/switch
AMI (amazon machine images) are used to initialize EC2 instances and are like on premise servers
Amazon EBS (elastic block store) is like a physical hard disk that attaches to your virtual machines
Amazon EFS (elastic file system) is like a trad storage area network (SAN)
Amazon S3 (Simple Storage System) is similar to a network attached storage solution (NAS)
Amazon RDS (Relational db system) is like your physical relational db mgmt system (MySQL)

#### Advantages of the Cloud

6 advantages
Trade cap expense for var expense

Benefit from massive economies of scale

No more need to guess capacity - Scaling on demand

Increase speed and agility

Stop spending money on data centers - focus on product/customers instead of infrastructure

Go global in minutes

#### Introduction to AWS

What is a web service? A services that is provisioned and used on the internet. A piece of software that makes itself avail over the internet.

Web services like to use XML or JSON.

The billing for AWS becomes an opera expense instead of a capi expense

If you want complete control over your computational power, use EC2.

AWS Lambda allows us to run code without having to manage or provision servers.

Elastic beanstalk will deploy and scale automatically.

Lightsail = web app.

AWS batch = 100's of 1000s of background things

Aws outposts = AWS infrastruct in your on premises data center

Containers = ECS, EKS, Fargate

VMWare cloud on AWS is used to migrate on premise virtualization to AWS

3 major ways to access and create

AWS mgmt console

AWS CLI

SDKs

#### Moving to the AWS cloud

Cloud adoption framework CAF

PEOPLE PROCESS TECH
must be in alignment

The AWS CAF provides guidance and recommendations for adopting processes to aws cloud.

6 areas of focus, called perspectives

Business Perspect
Stakeholders, business managers, finance managers, budget owners, strategy stakeholders

People Perspect
HR, staffing, people managers

Governance perspective
CIO, program managers, enterprise architects, business analysts, and portfolio managers.

Platform Perspect
CTO, IT managers, solutions architects - must be able to describe the architecture in detail

Sec Perspect
CISO, IT sec managers, IT sec Analysts

Operations Perspect
IT operations managers and IT support managers - day to day quarter to quarter business is conducted
