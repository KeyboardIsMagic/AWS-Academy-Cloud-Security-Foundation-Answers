# Module 4 Knowledge Check


### **Q1.**
A three-tier web application environment is a modular client-server architecture. What are the three tiers?

**Answer:**
**Presentation, application, and data**

---

### **Q2.**
What is the difference between a security group and network access control list (ACL)?

**Answer:**  
**A security group acts as a virtual firewall for EC2 instances. A network ACL acts as a firewall to control traffic in and out of one or more subnets**

---

### **Q3.**
What is the purpose of an internet gateway? (Select TWO.)

**Answer:**  
- **Perform network address translation (NAT) for instances that have been assigned public IPv4 addresses.**
- **Provide a target within a route table to enable internet-routable traffic.**

---

### **Q4.**
Which statements are true for virtual private cloud (VPC)? (Select THREE.)

**Answer:**
- **Is a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network**
- **Gives you control over your virtual networking resources including selecting the IP address range, creating subnets, and configuring route tables and network gateways**
- **Provides the ability to customize your network including creating a public subnet for your web servers that can access the public internet**


---

### **Q5.**
Security groups are stateful, and network access control lists (ACLs) are stateless. What is the difference between stateful and stateless?

**Answer:**
**Stateful means that return traffic is automatically allowed. Stateless means that return traffic must be explicitly allowed by rules.**


---

### **Q6.**
What are best practices to protect your network? (Select TWO.)

**Answer:**  
- **Use security groups to control access to resources**
- **Place Amazon EC2 instances in private subnets when they will not regularly need direct access to the internet**

---

### **Q7.**
Which service provides an automated security assessment that helps users to improve the security and compliance of applications that they deploy on AWS?

**Answer:**  
**Amazon Inspector**

---

### **Q8.**
A company wants to create a multi-tier website. What is the best practice for creating a load balancer and subnet architecture?

**Answer:**  
**Place the web server and database in a private subnet, and the load balancer in a public subnet**

---

### **Q9.**
What is NOT a best practice to protect compute resources?

**Answer:**
**Enable VPC Flow Logs down to the subnet level**

---

### **Q10.**
Which service can help users to automate management tasks such as collecting system inventory, applying operating system patches, maintaining up-to-date antivirus definitions, and configuring operating systems and applications at scale?

**Answer:**
**AWS Systems Manager**