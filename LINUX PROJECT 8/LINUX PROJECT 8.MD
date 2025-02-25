Step 1: Log into AWS Console
Go to the AWS Management Console: https://aws.amazon.com/console/

Click Sign in to AWS.

Step 2: Navigate to EC2 Dashboard
In the AWS Console, search for EC2 in the search bar.

Click EC2 under "Services".
In the left menu, click Instances.

Click Launch Instances.

Step 3: Configure EC2 Instance
Name and Tags

Enter a name for the instance (e.g., "MyEC2Instance").
Choose an Amazon Machine Image (AMI)

Select an OS for your instance. Common options:
Amazon Linux 2 (Recommended for most AWS workloads)
Ubuntu (Popular for development)
Windows Server (If you need a Windows environment)
Choose Instance Type

Select an instance type based on your needs.
Common choices:
t2.micro (Free Tier Eligible)
t3.medium (For better performance)
Key Pair (Login Credentials)

Click Create New Key Pair (if you don’t have one).
Name it (e.g., "MyKeyPair").
Download the .pem file and keep it safe (needed for SSH access).
Network Settings (Security Group)

Select Create security group.
Allow necessary inbound traffic:
SSH (port 22) → Your IP (or 0.0.0.0/0 for testing)
HTTP (port 80) → Anywhere (for web apps)
HTTPS (port 443) → Anywhere (if using SSL)
Configure Storage

Default: 8 GiB (Amazon Linux 2, Ubuntu)
Increase if necessary.
Advanced Details (Optional)

Select IAM Role (if using AWS services like S3, RDS).
Add startup scripts in User data (for auto-configurations).

Step 4: Launch the Instance
Review the settings.

Click Launch Instance.
Wait for the instance to initialize.
Step 5: Connect to the Instance
A. Using SSH (Linux/macOS/Windows PowerShell)
Open Terminal/PowerShell.
Navigate to the folder where the .pem file is saved.

LAUNCH EC2 INSTANCE 
![alt text](<LINUX PROJECT 8 IMAGES/LAUNCH  EC2 INSTANCE.png>)

![alt text](<LINUX PROJECT 8 IMAGES/LAUNCH  2.png>)

SSH INTO THE INSTANCE
![alt text](<LINUX PROJECT 8 IMAGES/Connect to the EC2 Instance     Copy the Public IP or Public DNS..png>)

SUCCESFULLY CONNECTED 
![alt text](<LINUX PROJECT 8 IMAGES/sucessfully coneced to EC2 INSTANCE.png>)

INSTALLING OTHER BACKEND DEPENDENCIES
![alt text](<LINUX PROJECT 8 IMAGES/. Install Other Dependencies.png>)

MongoDB
![alt text](<LINUX PROJECT 8 IMAGES/Install MongoDB .png>)

Nodejs
![alt text](<LINUX PROJECT 8 IMAGES/Install nodejs.png>)

![alt text](<LINUX PROJECT 8 IMAGES/MongoDB is installed correctly..png>)

![alt text](<LINUX PROJECT 8 IMAGES/update the system.png>)

SERVER IS RUNNUNG

![alt text](<LINUX PROJECT 8 IMAGES/Server is running .png>)