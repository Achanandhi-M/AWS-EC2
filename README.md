# AWS-EC2
<br>
<br>
<br>

## Struggling to create an EC2 instance? In this repository, I will guide you to create an EC2 instance within 4 seconds. The only prerequisite is to have an AWS account. If you don't have one, create an account using the AWS Free Tier: https://docs.aws.amazon.com/SetUp/latest/UserGuide/setup-AWSsignup.html.
<br>
<br>
<br>


## Remember, EC2 instances are region-specific. This means that when you launch an EC2 instance, you need to select the AWS region in which it will be created. Each AWS region is a separate geographic area, and resources, including EC2 instances, are confined to the region where they are launched.
<br>
<br>
<br>

## In the Search Box Type "EC2" 
<br>
<br>
<br>

![Screenshot from 2024-01-13 09-53-09](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/170c6f41-a764-4bf5-a0fb-784f89a1d8e2)

<br>
<br>
<br>

## With the Centralized EC2 Dashboard, we can obtain details of the EC2 Service
<br>
<br>
<br>

![Screenshot from 2024-01-13 09-53-28](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/a4e90ea2-2479-4078-bced-a8b50785dae8)

## Click the Launch Instance Icon to Launch an instance

<br>
<br>
<br>

![Screenshot from 2024-01-13 09-53-49](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/8a1cf355-59e5-4c0d-812b-436f2214da7e)
<br>
<br>
<br>


## Name your instance and choose the operating system that you want your instance to use. The best part when using an EC2 instance is you don't need to install the operating system, instead manually, it is already pre-configured by AWS in the form of AMI(Amazon Machine Image), you can also create your own AMI.

<br>
<br>
<br>

![Screenshot from 2024-01-13 09-54-27](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/1baf12dc-5146-422a-96c6-bf31a8946c77)
<br>
<br>
<br>


## When you Use AWS free-tier there is a restriction in choosing AMI, for free-tier you have the option to use Amazon Linux from AWS
<br>
<br>
<br>


![Screenshot from 2024-01-13 09-54-39](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/0dc4e435-8f19-436a-9b98-f5f1087207a9)
<br>
<br>
<br>


## The network is the backbone of everything. We can create our own Virtual network for our resources in AWS by using the AWS VPC (Virtual Private Cloud) service. There is no VPC currently running in this region, so it is showing a '-' value.
<br>
<br>
<br>


![Screenshot from 2024-01-13 09-55-15](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/ad6925e0-6917-4a84-8049-4adec932cd5d)
<br>
<br>
<br>


## In the Search Box Type "VPC"

![Screenshot from 2024-01-13 09-55-31](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/cd742588-d632-431b-bde3-a9dcb2faaf39)
<br>
<br>
<br>


## You can create your VPC based on your use case and requirements. For simplicity, I have created a default VPC.
<br>
<br>
<br>


![Screenshot from 2024-01-13 09-55-50](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/7479e25b-6c49-4f83-8c82-c20d50d878f9)

<br>
<br>
<br>

## Click Create default VPC
<br>
<br>
<br>


![Screenshot from 2024-01-13 09-56-14](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/8421004d-9b48-4be1-a9c9-1f2e3d00632e)
<br>
<br>
<br>


## We have successfully created a VPC. Below, there is an option to view the setup in graphical form.
<br>
<br>
<br>


![Screenshot from 2024-01-13 09-56-45](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/435f346c-cb45-426b-ab4c-a65d1a913aad)
<br>
<br>
<br>


## Security Groups are a security feature in EC2. We can set rules to define permissions for accessing our instance.
<br>
<br>
<br>


![Screenshot from 2024-01-13 09-58-13](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/c4742c39-caa2-4683-a567-3b68652a7126)
<br>
<br>
<br>


## If you want to set up additional configurations, you can click on Advanced setup options; otherwise, click on Launch Instance.
<br>
<br>
<br>


![Screenshot from 2024-01-13 09-58-52](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/59ffa62d-f15c-4517-8a6d-22d9bc5160d8)
<br>
<br>
<br>


## Within 3 seconds, we have a brand new server up and running. This is the real power of the cloud. Check the instance state to verify the status of your instance.
<br>
<br>
<br>


![Screenshot from 2024-01-13 10-00-09](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/e3394dc3-b4b8-4690-9c68-dc0cac830bb1)
<br>
<br>
<br>


## If you want to create another EC2 instance, follow the same instructions mentioned above.
<br>
<br>
<br>


![Screenshot from 2024-01-13 10-00-41](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/d3c69d75-bcff-4e5d-8e63-6c2850075013)
<br>
<br>
<br>

## 2 instances are running and the instance type is "t2.micro".
<br>
<br>
<br>


![Screenshot from 2024-01-13 10-02-10](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/7ecff5cc-9fcb-4ace-bd76-05eb15ca64bc)
<br>
<br>
<br>


## Always follow best practices to delete cloud resources when they are not needed; it also helps to reduce your cloud bills
<br>
<br>
<br>


![Screenshot from 2024-01-13 10-02-49](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/b6b24bbb-7226-4963-9d98-06af33607d8d)
<br>
<br>
<br>


## I also want to mention here the new update from the AWS EC2 team. They introduced a new feature to monitor resource usage, which is an awesome addition. In the AWS Free Tier, we have the option to use EC2 for 750 hours monthly. This feature helps us track both resource usage of EBS and instances.
<br>
<br>
<br>


![Screenshot from 2024-01-13 10-03-17](https://github.com/Achanandhi-M/AWS-EC2/assets/110651321/8e7b9466-c1db-4705-afac-c8346479d974)

<br>
<br>
<br>

## For any AWS or EC2-related doubts, reach out to me via email at achanandhi.m@gmail.com










