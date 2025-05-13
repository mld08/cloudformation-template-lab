# AWS re/Start Challenge Lab  
## Using AWS CloudFormation to Create a VPC and an EC2 Instance

### 📝 Description

This challenge lab is designed to help you practice creating AWS infrastructure using **AWS CloudFormation**. You'll write a CloudFormation template to provision a basic network architecture that includes a Virtual Private Cloud (VPC), networking components, and an EC2 instance.

---

### 🎯 Objectives

The goal is to create a CloudFormation template that successfully deploys the following resources:

- **Amazon VPC**  
  A custom Virtual Private Cloud for network isolation.

- **Internet Gateway**  
  Attached to the VPC to allow internet connectivity.

- **Security Group**  
  Configured to allow **SSH access (port 22)** from anywhere (`0.0.0.0/0`).

- **Private Subnet**  
  Created within the VPC for hosting the EC2 instance.

- **Amazon EC2 Instance**  
  A `t3.micro` instance launched inside the private subnet.  
  > ⚠️ *Note: You do **not** need to SSH into the instance or use Remote Desktop for this lab.*

---

### 🛠️ Instructions

1. **Write** your CloudFormation template step by step.
2. **Validate** the template using the AWS CloudFormation console or CLI.
3. **Deploy** and **test** the stack to ensure all resources are created successfully.
4. **Iterate** on your template until it works without errors.
5. **Notify** your instructor once the stack deploys correctly for review.

---

### 📌 Tips

- Use **parameters**, **mappings**, and **outputs** in your template for clarity and reusability.
- Check for **resource dependencies** and ensure they are correctly defined.
- Test your template in a **safe environment** before final submission.

---

### ✅ Success Criteria

- All components are created as specified.
- No deployment errors are encountered.
- Resources are logically connected and properly configured.

---

Good luck and happy building! 🚀

