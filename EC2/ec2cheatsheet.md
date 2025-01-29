# AWS EC2 Cheat Sheet

## **1. EC2 (Elastic Compute Cloud)**

### **Definition:**
EC2 is a cloud-based virtual server that allows users to run applications without managing physical hardware.

### **Purpose:**
Provides scalable and flexible compute capacity for various workloads like web hosting, databases, and machine learning.

### **Real-World Example:**
A startup launches an e-commerce website and needs on-demand servers to handle traffic spikes.

### **Analogy:**
EC2 is like renting a hotel room instead of buying a house; you use it as needed without long-term commitment.

---

## **2. EC2 Instance Types**

### **Definition:**
Different instance types are optimized for specific workloads based on CPU, memory, and storage needs.

### **Categories:**
- **General Purpose (T, M Series)** – Balanced for various applications.
- **Compute Optimized (C Series)** – High-performance CPUs for intensive tasks.
- **Memory Optimized (R, X Series)** – Ideal for large databases and caching.
- **Storage Optimized (I, D Series)** – Best for high I/O operations.
- **GPU Instances (P, G Series)** – Used for AI/ML and gaming applications.

### **Analogy:**
Choosing an EC2 instance is like picking a vehicle—trucks for heavy loads, sports cars for speed, and sedans for balance.

---

## **3. EC2 Pricing Models**

### **Definition:**
Different pricing options allow cost optimization based on usage patterns.

### **Types:**
- **On-Demand** – Pay per hour or second with no long-term commitments.
- **Reserved Instances** – Up to 75% discount for long-term commitments.
- **Spot Instances** – Cheapest option but can be interrupted anytime.
- **Dedicated Hosts** – Physical servers dedicated to a single customer.

### **Analogy:**
On-Demand is like taking a taxi, Reserved is like leasing a car, and Spot is like hitchhiking when a ride is available.

---

## **4. EC2 Key Features**

- **Elastic Load Balancing (ELB)** – Distributes traffic across multiple instances.
- **Auto Scaling** – Adjusts the number of instances based on demand.
- **Security Groups** – Acts as a firewall to control inbound/outbound traffic.
- **Elastic Block Store (EBS)** – Provides persistent storage for EC2 instances.
- **EC2 Placement Groups** – Controls instance placement for performance optimization.

### **Analogy:**
Security Groups are like airport security, ensuring only authorized people get through.

---

## **5. EC2 Storage Options**

### **Definition:**
Storage options for EC2 instances vary based on speed, persistence, and cost.

### **Types:**
- **Instance Store** – Temporary storage tied to an instance.
- **EBS (Elastic Block Store)** – Persistent, high-performance block storage.
- **EFS (Elastic File System)** – Managed file storage that scales automatically.

### **Analogy:**
EBS is like an external hard drive that stays even if your laptop shuts down.

---

## **6. EC2 Access & Security**

### **.pem File (Key Pair)**

### **Definition:**
A .pem file is a private key used to securely access an EC2 instance.

### **Purpose:**
Ensures only authorized users can SSH into an EC2 instance.

### **Analogy:**
A .pem file is like a digital key that unlocks your EC2 instance.

---

### **SSH Access**

### **Definition:**
Secure Shell (SSH) is used to connect to EC2 instances remotely over a command-line interface.

### **Purpose:**
Allows secure remote administration of Linux-based EC2 instances.

### **Analogy:**
SSH is like a secure tunnel that lets you control a remote computer from anywhere.

---

### **RDP Access**

### **Definition:**
Remote Desktop Protocol (RDP) is used to connect to Windows-based EC2 instances with a graphical interface.

### **Purpose:**
Enables users to remotely access and manage Windows EC2 instances.

### **Analogy:**
RDP is like screen sharing, allowing you to control a computer as if you were sitting in front of it.

---

This cheat sheet provides essential details for AWS **EC2, instance types, pricing, features, storage options, and access methods**.

