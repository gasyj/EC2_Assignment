# EC2_Assignment Documentation

## Overview
This repository contains the documentation for my AWS EC2 assignment, where I used the AWS Management Console to set up an EC2 instance and configure key AWS services such as security groups, Elastic IPs, and Auto Scaling.

---

## Tasks Completed

### 1. **Create an EC2 Key Pair**
- **Description**: Created a Key Pair to securely SSH into the EC2 instance. Key pairs ensure secure access by using a public-private key pair, where the public key is stored in AWS, and the private key remains on the client machine.
- **Steps**:
 
- **Screenshot**: 
![KeyPairs](https://github.com/user-attachments/assets/9c82458b-4cbe-4279-a69b-4251a0df4724)
![EC2_KeyPair_created](https://github.com/user-attachments/assets/51582ed6-aec5-4d21-a4b7-c28bbe9b552f)


---

### 2. **Choose an AMI (Amazon Machine Image)**
- **Description**: Selected an AMI to define the operating system and initial software setup for the EC2 instance. For this assignment, I used Windows OS.
-
- **Screenshot**: 
![Windows_AMI_selected](https://github.com/user-attachments/assets/4bc552f3-6970-486a-8923-a53bd4bbe22c)
![AMI_launchTemplate](https://github.com/user-attachments/assets/9c338801-ab09-404a-9697-7f2f37905139)


---

### 3. **Select an EC2 Instance Type**
- **Description**: Choose an EC2 instance type that matches the required workload. I selected **t2.micro** since it fits within the Free Tier and provides enough resources for testing.
  1. Selected `t2.micro` instance type in the **Instance Type** section during the instance launch process.

- **Screenshot**:
![AMI_and_Instance_type_Selected](https://github.com/user-attachments/assets/9a39f58e-703b-4bc5-a752-85a1d5fa4506)
![Navitagting_to_EC2](https://github.com/user-attachments/assets/eb5336e0-87a8-42d3-b448-076bd920b165)
![Launching_instance](https://github.com/user-attachments/assets/49a83f44-2ec1-4740-bf71-229fb53ddfa4)


---

### 4. **Configure Security Groups**
- **Description**: Configured a security group to control traffic to and from the EC2 instance. The security group acted as a virtual firewall.

- **Screenshot**: 
![Securitygrp_created](https://github.com/user-attachments/assets/727792f8-8e26-4d48-ad0e-b8f00137a711)


---

### 5. **Allocate Elastic IP**
- **Description**: Assigned a static, public Elastic IP to ensure that the EC2 instance retained the same public IP even after stopping and starting.
  
- **Screenshot**:
![Elastic_IP_allocated](https://github.com/user-attachments/assets/92409166-63bf-4233-b9e7-ab7f76daaf4f)
![Associate_ElasticIP](https://github.com/user-attachments/assets/fd2ebc46-7546-4995-923a-22c2d67cfadb)
![Allocating_ElasticIP](https://github.com/user-attachments/assets/0e3b64b4-d795-42e3-9aba-5ab7ec312687)
![ElasticIP_associated_to_instance](https://github.com/user-attachments/assets/775f3e6f-6ad2-40db-9de0-dacaba078fca)
![ElasticIP_Associated_successfully](https://github.com/user-attachments/assets/f18e114b-11c9-4037-bc8d-e34f8048000b)


---

### 6. **Configure EC2 Storage**
- **Description**: Configured EBS storage for persistent data storage on the EC2 instance. This included setting up the root volume during the instance launch.

- **Screenshot**:
![Creating_volume](https://github.com/user-attachments/assets/3047a035-d4d9-4bc1-91ca-093396fa44d5)
![EBSvolume_details](https://github.com/user-attachments/assets/056518ed-6322-4b63-8a52-b7a1b3e83554)
![EBSvolume_created](https://github.com/user-attachments/assets/6b27c596-7cad-478b-bd78-d683173a8dc7)
![EBSvolume_attached-instance](https://github.com/user-attachments/assets/058702c3-2264-4d65-9798-1e59b4fa710f)



---

### 7. **VPC Setup**
- **Description**: Set up a Virtual Private Cloud (VPC) with subnets and an internet gateway to manage networking for the EC2 instance.

- **Screenshot**:
![Navigating_to_VPC](https://github.com/user-attachments/assets/db91664e-32b2-41cc-8ed2-de58f2d737ba)
![Creating_VPC](https://github.com/user-attachments/assets/b376efd3-6590-4085-88b2-e56e82b5c255)
![VPC_subnet_created](https://github.com/user-attachments/assets/11947e03-4698-4fca-96af-d442514e9cdd)
![VPC_Public PrivateSubnet](https://github.com/user-attachments/assets/b84b14f2-ba3b-4369-8b2d-b2d8d70cf0dc)
![Public_subnet_routingtable](https://github.com/user-attachments/assets/0f26a58f-ac16-4590-8718-94ad40624caf)
![Private_IP_selected](https://github.com/user-attachments/assets/5264fe8e-953c-444c-bf8b-b7a4ed66b456)
![NAT_gateway_created](https://github.com/user-attachments/assets/96c7692d-b115-42b5-9cda-cc89a1557108)
![Internetgw_attached_to_vpc](https://github.com/user-attachments/assets/77d972f8-6e8b-4e88-a38c-ccbfef603fec)
![VPC_createdsuccessfully](https://github.com/user-attachments/assets/189b540c-f0c7-42ca-8476-f1683ba0365e)
![VPC_Dashboard](https://github.com/user-attachments/assets/94e7a12e-309b-4a23-8cb8-f537bfee0bec)

---

### 8. **Create Launch Template**
- **Description**: Created a launch template to streamline the process of launching EC2 instances with predefined settings.
  
- **Screenshot**:
![LaunchTemp_name](https://github.com/user-attachments/assets/9e97cdf0-9cd0-4800-a46f-3277880594b3)
![InstanceType_Template](https://github.com/user-attachments/assets/d0b6e209-890c-422f-ad26-4b57277aade7)
![EC2_LaunchTemp](https://github.com/user-attachments/assets/94dbf5e4-7829-4382-b5a2-f351e888bf2b)
![EC2_LaunchInstance_created](https://github.com/user-attachments/assets/1c493263-2324-4af5-ad30-add97ec601b6)
![EC2_launch_temp_created](https://github.com/user-attachments/assets/8a3c2320-7bc1-4afc-a76d-db1364d40a48)
![AMI_launchTemplate](https://github.com/user-attachments/assets/279b30a4-5d70-41fb-b468-0e4261b3dae9)


---

### 9. **Auto Scaling**
- **Description**: Configured Auto Scaling to automatically adjust the number of EC2 instances based on traffic demand.

- **Screenshot**:
![Creating_AutoScaling](https://github.com/user-attachments/assets/73895cf6-0047-4492-8940-4127f50b1e64)
![AutoScaling_NetworkSelected](https://github.com/user-attachments/assets/7a7626b0-8bdc-4226-8693-1fe468d04b85)
![AutoScaling_LaunchTemp](https://github.com/user-attachments/assets/bb024ff7-3680-4f62-b2fa-bc479ff3493f)
![AutoScaling_created](https://github.com/user-attachments/assets/661510e7-45e9-4638-a0a5-e9a4cb500f11)


---

### 10. **Monitoring and Logs**
- **Description**: Used Amazon CloudWatch to monitor EC2 instance performance and set up alerts.
  1. Enabled CloudWatch monitoring for the instance.
  2. Configured alarms to monitor CPU usage.

- **Screenshot**:
![Navigating_to_CloudWatch](https://github.com/user-attachments/assets/42822c76-8cbd-4313-ae93-e3d590e1ebd7)
![EC2_Cloudwatch_dashboard](https://github.com/user-attachments/assets/a731d950-ad93-40ac-b46c-952277c5fba1)


---

### 11. **Load Balancer**
- **Description**: Set up an Application Load Balancer to distribute incoming traffic across multiple EC2 instances.

  1. Created an Application Load Balancer.
  2. Configured a target group and registered EC2 instances to balance incoming traffic.
  
- **Screenshot**:
![LoadBalancer_NetworkSettings](https://github.com/user-attachments/assets/5b27796b-f51d-430c-aeb2-f685e1f84591)
![LB_securitygroup](https://github.com/user-attachments/assets/66357720-251b-4728-b8a7-8a7942d3437e)
![Creating_LoadBalancer](https://github.com/user-attachments/assets/14fba0fc-c960-472b-b752-ab9c05c660c2)


---
### 12. **Connection to RDP**
- **Description**: Successfully connected to the instance via RDP.
- **Screenshot**:
![RDP Page](https://github.com/user-attachments/assets/1da15a50-fdb2-4705-8c8b-de55a4a159ae)
![Accessing_the_internet_via_EC2Instance](https://github.com/user-attachments/assets/e815b51b-0c6c-49bd-8851-422a517b5ded)

---
## **Conclusion**
This documentation details the steps taken to complete the AWS EC2 assignment using key AWS services. Each task demonstrates essential cloud infrastructure management, including networking, security, and scaling, which are critical for building highly available and cost-efficient cloud applications.
