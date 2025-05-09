🌐 Terraform AWS Setup (VPC + EC2)

This Terraform script sets up a basic AWS infrastructure including:

    🟢 VPC with a public subnet

    🌐 Internet Gateway and Route Table

    🔐 Security Group for HTTP and SSH access

    💻 EC2 instance (Amazon Linux 2) with a public IP

    🗝️ SSH Key Pair for secure acces

✅ Prerequisites

Before starting, ensure you have:

    ✅ Terraform installed

    ✅ AWS CLI configured

    ✅ SSH key pair available at:

~/.ssh/id_rsa
~/.ssh/id_rsa.pub


Configure AWS CLI inside your Amazon Linux 2 instance
------------------------------------------------
 I am attaching Clip for your reference ....
-----------------------------------------------
![Image](https://github.com/user-attachments/assets/b44208d9-5a27-4799-8fea-a38a992f5849)

After successful login 
copy main.tf  file in directory  

🚀 How to Use

1️⃣ Initialize Terraform  : terraform init

![Image](https://github.com/user-attachments/assets/2151d3fa-080b-4b12-8e8b-6f31f4563429)

------------------------------------------------------------

2️⃣terraform plan 

![Image](https://github.com/user-attachments/assets/c5f97dd2-3a37-4cae-9e8f-89c630e88d82)


------------------------------------------------------------------

3️⃣️⃣ Apply the Configuration  :terraform apply

![Image](https://github.com/user-attachments/assets/2ec8f9ce-83e4-419b-b609-41482da6870a)

![Image](https://github.com/user-attachments/assets/6755aeb1-a9f2-4b73-abd0-009f96247c12)


------------------------------------------------------------
🧹 (Optional) Destroy Resources  : terraform destroy
