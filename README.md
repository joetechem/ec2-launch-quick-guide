# Amazon EC2-Launch-Quick-Guide
## Basic Steps to Launch an EC2 Instance on AWS.  

There are plenty of guides out there to help you achive this. You can check out the official documentaion at https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html.  

This guide will attempt to quickly walkthrough the steps of launching an Amazon EC2 instance as well as convey concise concepts of the AWS service to help understand what is going on. This guide is more for myself, to help engrain important concepts and steps to reach the goal of being a certified AWS Solutions Architect - Associate.  

## Amazon Elastic Compute Cloud (Amazon EC2)  
### What is it?  

An AWS service that:  

* provides resizable compute capacity  
* allows organizations to obtain and confgure virtual servers in Amazon's data centers and to harness those resources to build and host software systems.  
* allows a user/organization can select from a variety of operating systems and resource configurations (memory, CPU, storage, etc).  
* presents a true virtual computing environment.  

### EC2 Options  

On Demand, Reserved, Spot, and Dedicated Host  

* **On Demand**    
  - allows user to pay a fixed rate by the hour (or second) with no commitment  
  - for applications with short-term, spikey, or **unpredictable workloads that cannot be interrupted**  
  - **Lowest cost/highest availability**

* **Reserved**  
  - For Applications with steady state or predictable usage  
  - Easily change up instances  
  - **Predictable usage/upfront costs**  
  
* **Spot**  
  - Used highly in genomics, insurance companies, or any with LARGE datasets  
  - Spot prices can be lower at certain times, so much much of the data is used/uploaded during this time  
  - **Flexible start & end times**  
  
* **Dedicated Hosts**  
  - On demand by the hour  
  - Useful for regulatory requirements that may not support multi-tenant virtualization  
  
### Instance Types  

The instance type defines the virtual hardware supporting an Amazon EC2 instance. There are several types available, varying in the following dimensions:  

* Virtual CPUs (vCPUS)  
* Memory  
* Storage (size & type)  
* Network Performance  


  
 
