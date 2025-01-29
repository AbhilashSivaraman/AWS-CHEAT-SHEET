# AWS IAM & Security Cheat Sheet

## **AWS shared responsibility Model**

AWS is responsible **for** the security of the cloud (infrastructure, hardware, networking, and managed services), while the customer is responsible for security **in** the cloud (data, applications, identity management, and configurations).


## **1. AWS Security**

### **Definition:**
AWS Security ensures data protection, access control, and compliance using various security services.

### **Purpose:**
Protects cloud resources from unauthorized access, cyber threats, and data loss.

### **Real-World Example:**
Just like banks secure money with vaults, AWS secures cloud data with encryption and access policies.

### **Analogy:**
AWS Security is like a home security system—it locks doors (firewalls), requires keys (credentials), and has security cameras (monitoring tools).

---

## **2. IAM (Identity and Access Management)**

### **Definition:**
IAM manages who can access AWS resources and what actions they can perform.

### **Purpose:**
Controls permissions to prevent unauthorized access and ensure least-privilege security.

### **Real-World Example:**
A company assigns different keycard access levels—employees can enter offices, but only managers can access restricted areas.

### **Analogy:**
IAM is like a school ID system—students, teachers, and staff have different access levels based on their roles.

---

## **3. Components of IAM**

1. **Users** – Individual AWS accounts for people or applications.  
   - **Analogy:** A student in a school system with a unique ID.  

2. **Groups** – A collection of users with shared permissions.  
   - **Analogy:** A class in school where all students get the same privileges.  

3. **Roles** – Temporary permissions assigned to users or services.  
   - **Analogy:** A substitute teacher who gets temporary access to a classroom.  

4. **Policies** – Rules defining what actions are allowed or denied.  
   - **Analogy:** A school rulebook that tells students what they can and cannot do.   

5. **MFA (Multi-Factor Authentication)** – Adds extra security by requiring an additional verification step.  
   - **Analogy:** A two-lock system where you need both a key and a fingerprint to open a door.  

---

## **4. Types of IAM Policies**

### **Definition:**
IAM policies are rules that define permissions for AWS users, groups, or roles.

### **Purpose:**
They control what actions can be performed on AWS resources, ensuring security and least privilege.

### **Real-World Example:**
A company sets different Wi-Fi access rules—employees can access all networks, but guests can only use the public network.

### **Analogy:**
IAM policies are like school rules—students can enter classrooms, but only teachers can access the staff room.

### **Types:**

1. **AWS Managed Policies** – Predefined policies created by AWS for common use cases.  
   - **Analogy:** A school handbook with standard rules that apply to all students.  

2. **Customer Managed Policies** – Custom policies created by users for specific needs.  
   - **Analogy:** A teacher making their own classroom rules, separate from the school-wide rules.  

3. **Inline Policies** – Policies attached directly to a specific user, group, or role, rather than being reusable.  
   - **Analogy:** A hall pass that applies only to one student and isn’t shared with others.  

---

## **5. Types of IAM Access**

### **Definition:**
IAM access types define how users, applications, and AWS services interact with AWS resources.

### **Purpose:**
Ensures secure and controlled access to AWS resources, allowing only necessary actions.

### **Real-World Example:**
Just like an employee can either log in to a company’s system or use automated scripts to perform tasks, AWS users and applications also have different ways to access resources.

### **Analogy:**
Access in AWS IAM is like a school’s security system—some people enter using ID cards (passwords), some through guest passes (temporary access), and some through automated systems (service accounts).

### **Types:**

1. **Console Access** – Users log in to the AWS Management Console using a username and password.  
   - **Analogy:** A student logging into an online school portal with their ID and password.  

2. **Programmatic Access** – Users or applications use **Access Keys** to interact with AWS via CLI, SDKs, or APIs.  
   - **Analogy:** A robot (automation script) using a special key to open locked doors automatically.  

---

This cheat sheet covers all essential IAM and Security concepts.
