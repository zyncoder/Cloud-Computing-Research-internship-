# Cloud-Computing-Research-internship-
Internship task

### 1. Describe basic aspects of AWS Elastic Compute Cloud.
Global Infrastructure
Cost and Capacity Optimization
Networking
Operating Systems and Software
Storage

### 2. How to create a virtual machine instance in AWS EC2.
**Step 1.** Log in to “AWS Management Console”.

**Step 2.** Under the Build Solution group, click on the “Launch a virtual machine” link. AWS will open a wizard to allow us to create a Virtual Machine instance (EC2 instance).

**Step 3.** Choose an Amazon Machine Image (AMI) that contains the software configuration required to launch the EC2 instance. Select the AMI which is suitable for your need by clicking on the Select button next to the displayed AMI template. Once selected, the Console will take us to the next step to select an instance from the “Choose an Instance Type” wizard page.

**Step 4.** Select the instance type which suits our requirement, and click on “Next: Configure Instance Details” to go to the next wizard step.

**Step 5.** “Configure Instance Details” allows you to configure the instance to suit your requirements. Keep the default values, if you do not want to modify anything.

**Step 6.** The “Add Storage” wizard page, allows you to update the storage device settings. You can also add new volumes depending on your requirements. Once the values are given, click on the “Next: Add Tags” button.

**Step 7.** After adding the Tags, click on the “Next: Configure Security Group” button.

**Step 8.** “Configure Security Group” wizard allows to add rules to control the traffic for the EC2 instance.

**Step 9.** Before launching the instance, AWS Management Console will prompt a message, to create a key pair entry to attach to the instance. You can create a new key pair or you can use the already created one. This key pair is important to connect to the EC2 instance. Key pair contains both public & private keys. You need to download the Key Pair and store it in a secured location from where you can access it whenever you want to connect to the EC2 instance.


### 3. How to install an Apache webserver on AWS EC2 Instance.

1)Launch an AWS EC2 instance 
2)Installing Apache Web Server 
- First update local package index to reflect the latest upstream changes.
- sudo apt update
- Install Apache2 package
- sudo apt install apache2
3)After the Apache installation process, the web server service should be started automatically, you can check if it is up and running with the following command.
- sudo systemctl status apache2
4)You can check is your Apache server is working fine or not. Open a web browser and enter the following URL to access default page of server.
- http://server-public-ip

### 4. How we can connect an AWS EC2 instance to a MySQL server database.
1. Open MySQL Workbench.
2. Select MySQL New Connection and enter a connection name.
3. Choose the Connection Method, and select Standard TCP/IP over SSH.
4. For SSH Hostname, enter the public IP address of your EC2 instance.
5. For SSH Username, enter the default SSH user name to connect to your EC2 instance.
ics

### 5. How to connect a domain to your website using Route 53.
Step 1: Register a custom domain with Route 53
Step 2: Create two buckets
Step 3: Configure your root domain bucket for website hosting
Step 4: Configure your subdomain bucket for website redirect
Step 5: Configure logging for website traffic
Step 6: Upload index and website content
Step 7: Upload an error document
Step 8: Edit S3 Block Public Access settings
Step 9: Attach a bucket policy
Step 10: Test your domain endpoint
Step 11: Add alias records for your domain and subdomain
Step 12: Test the website

