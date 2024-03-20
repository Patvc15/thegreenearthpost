This template creates the following resources:
A VPC with a public subnet.
An internet gateway and route table to allow internet access for the public subnet.
A security group for the API server that allows incoming traffic on port 80 (HTTP).
An IAM role and instance profile for the EC2 instance with permission to describe RDS instances.
An EC2 instance for the API server with the specified script in the user data.
A security group for the RDS database that allows incoming traffic on port 3306 (MySQL) from the API server security group.
An RDS database instance with the specified configuration.
Please note:
You need to replace the script in the user data section with your actual script from GitHub.
You may need to adjust the AMI ID and RDS engine version based on your specific needs.
Make sure you update the MasterUserPassword with a strong password.
This template provides a basic starting point for your infrastructure. You can customize it further based on your specific requirements.
