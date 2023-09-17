### AWS EC2 (Cloud Compute)

EC2 stands for Elastic Cloud Compute and it is used in everything on the internet and if there was a competition of the most import web service then EC2 would be the winner.

Some of the uses - 

- **Web Hosting**
- **Application Hosting**
- **Development and Testing**
- **Data Processing**
- **Big Data and Analytics**
- **Machine Learning**
- **Content Delivery**

and much more.

#### Features - 

**Variety of Instance Types** - EC2 has a wide selection of insstance types optimized for different use cases which include compute optimized, memory optimized, storage-optimized and more that allows for specific workloads.

**Scalability** - EC2 can be scaled up or down according to requirements. This can be done mannually or automatically by Auto Scaling.

**Customization** - EC2 are highly customizable. You can choose operating system, assign elastic IP addresses and install any type of software.

**Elastic Load Balancing** - EC2 instances can be used with Elastic Load Balancing (ECB) for distribution of incoming traffic across multiple instances which improves fault tolerance and availability.

**Amazon Machine Images (AMI's)** - EC2 instances are launched for AMI which are pre-configured templates containing the necessary software and configuration.  

**Integration with other services** - EC2 can be integrated with other services like Lambda (serverless) , Object Storage, Databases.

and much much more.



#### Simple Setup

**Step 1: Sign in to AWS Console**

- Open your web browser and go to the [AWS Management Console](https://aws.amazon.com/).
- Sign in with your AWS account credentials.

**Step 2: Access EC2 Service**

- Once you're logged in, click on "Services" in the top left corner.
- Under "Compute," click on "EC2" to access the EC2 dashboard.

**Step 3: Launch an EC2 Instance**

- In the EC2 dashboard, click the "Instances" link on the left sidebar.

**Step 4: Choose an Amazon Machine Image (AMI)**

- In the "Choose an Amazon Machine Image (AMI)" step, you can select an AMI that suits your needs. AWS provides various pre-configured AMIs, including those with different operating systems and software pre-installed.

**Step 5: Choose an Instance Type**

- In the "Choose an Instance Type" step, you'll select the type of EC2 instance you want. The available options vary in terms of CPU, memory, and network performance.

**Step 6: Configure Instance Details (Optional)**

- In this step, you can configure additional settings for your instance, such as the number of instances to launch, network settings, and more. You can generally leave these settings at their defaults for a basic setup.

**Step 7: Add Storage (Optional)**

- You can specify the amount of storage (EBS volumes) you want for your instance. The default storage size should work for many use cases.

**Step 8: Add Tags (Optional)**

- Tags are key-value pairs that you can assign to your instances for easier management and organization. You can skip this step if you don't need tags.

**Step 9: Configure Security Group**

- A security group acts as a firewall for your instance, controlling inbound and outbound traffic. By default, a new security group is created.
- You can customize the rules to allow specific types of traffic (e.g., SSH, HTTP).

**Step 10: Review and Launch**

- Review the settings you've configured for your instance. Ensure everything looks correct.
- Click the "Launch" button.
- ![Creating an EC2 instance](https://static.javatpoint.com/tutorial/aws/images/aws-ec2-creating-an-instance2.png)

**Step 11: Create or Use an Existing Key Pair**

- If you don't have an existing key pair, you'll need to create one. Key pairs are used for secure access to your EC2 instance.
- Choose "Create a new key pair" and give it a name. Download the private key file (`.pem`) to your local machine.
- Click the "Launch Instances" button.

**Step 12: Launch Status**

- You'll see a confirmation message that your instances are launching. Click the "View Instances" button to see the status of your instance.

That's it! You've successfully launched an EC2 instance. You can now connect to it using SSH (for Linux instances) or RDP (for Windows instances) using the private key you downloaded. Remember to stop or terminate your instance when you're not using it to avoid incurring unnecessary charges. 