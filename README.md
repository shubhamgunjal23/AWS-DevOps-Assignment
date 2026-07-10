# AWS DevOps Assignment

## AWS EC2 setup steps
Step 1: Launch the Instance

Open the AWS Console and navigate to EC2.

Step 2: Choose an AMI

Select Ubuntu Server.

Step 3: Select an Instance Type

Choose t3.micro.

Step 4: Create a Key Pair

Create and download the `.pem` key pair.

Step 5: Configure Network Settings

Allow SSH (22) and HTTP (80).

Step 6: Configure Storage

Keep the default 8 GB storage.

Step 7: Launch and Connect

Launch the instance and connect using SSH.

## AWS Services Used
- EC2
- Security Group

## Nginx Installation &  Linux Commands
apt update -y  :- Update packages

apt install nginx -y  :- Installation of Nginx

systemctl status nginx  :- Check Status of Nginx

systemctl restart nginx  :- Restart

df -h  :- Disk usages

free -h  :- Memory Usages

ps -ef  :- Running Process

cd  :- Change Directory

mkdir :- Create a Directory

pwd  :- Check Present Working Directory

ls -al :- List all hidden or normal files and Directories

vim filename  :- Create a file or enter data

cp  :- Use for Copy the files and Directories

## Website Hosted using Nginx
