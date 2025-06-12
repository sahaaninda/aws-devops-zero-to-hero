# VPC Demo for 2 tier app in private subnet

AWS Project: VPC with public-private subnet in Production

![Screenshot 2025-06-12 at 11 17 29 AM](https://github.com/user-attachments/assets/ea9b4d16-2f24-44e7-9ba3-c7f4714699d4)


- Bastion Host: A bastion host / jump server is configured to provide secure access to instances and resources located within a private network

Copying the aws key from local machine to Bastion Host

```
# ip of the bastion host
scp -i /Users/anindasaha/Downloads/awskey.pem /Users/anindasaha/Downloads/awskey.pem ubuntu@44.202.182.25:/home/ubuntu
```

- After copying, login to Bastion Host
- From Bastion Host ```ssh``` to the target servers in the private subnet
