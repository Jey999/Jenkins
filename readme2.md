Amazon Web Services (AWS) is a secure cloud services platform, offering compute power, database storage, content delivery and other functionality to help businesses scale and grow.


Amazon EC2 uses Amazon S3 for storing Amazon Machine Images (AMIs). You use AMIs for launching EC2 instances. In case of instance failure, you can use the stored AMI to immediately launch another instance, thereby allowing for fast recovery and business continuity.

1. Running web and application servers in the cloud to host dynamic websites.
2. Securely store all your files on the cloud so you can access them from anywhere.
3. Using managed databases like MySQL, PostgreSQL, Oracle or SQL Server to store information.


1) loging in terminal through aws:

ssh -i vj-eng42-class.pem ubuntu@ec2-3-10-143-2.eu-west-2.compute.amazonaws.com

2) simply copy:
scp -i ~/.ssh/vj-eng42-class.pem provision.sh ubuntu@ec2-3-10-143-2.eu-west-2.compute.amazonaws.com:/home/ubuntu/
provision.sh
