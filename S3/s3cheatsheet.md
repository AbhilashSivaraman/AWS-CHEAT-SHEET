# AWS S3 Cheat Sheet

## **1. S3 Buckets**

### **Definition:**
S3 (Simple Storage Service) is an object storage service that allows users to store and retrieve data in scalable, secure buckets.

### **Purpose:**
Used to store and manage data such as images, videos, backups, and logs in the cloud.

### **Real-World Example:**
Similar to how a Dropbox or Google Drive folder holds files, an S3 bucket holds data in AWS.

### **Analogy:**
An S3 bucket is like a digital locker where you can keep different types of files and access them from anywhere.

---

## **2. S3 Versioning**

### **Definition:**
S3 Versioning keeps multiple versions of an object in a bucket, preventing accidental deletion or modification.

### **Purpose:**
Helps recover deleted or changed files by maintaining historical versions.

### **Real-World Example:**
Google Docs keeps different versions of a document so you can revert to an earlier version if needed.

### **Analogy:**
A teacher keeping multiple drafts of an assignment before submitting the final version.

---

## **3. S3 Static Website Hosting**

### **Definition:**
Allows hosting static websites (HTML, CSS, JavaScript) directly from an S3 bucket.

### **Purpose:**
Used to serve simple websites without needing a web server.

### **Real-World Example:**
A portfolio website that only contains static pages without backend processing.

### **Analogy:**
Similar to putting up a bulletin board where people can read notices but not modify them.

---

## **4. S3 Replication (SRR & CRR)**

### **Definition:**
Replication automatically copies objects between S3 buckets within the same region (SRR) or across different regions (CRR).

### **Purpose:**
Used for backup, compliance, and disaster recovery.

### **Real-World Example:**
Banks keep duplicate transaction records in multiple locations to prevent data loss.

### **Analogy:**
SRR is like making a photocopy of a document and storing it in another drawer. CRR is like storing the copy in another city for disaster protection.

### **Types:**
- **Same-Region Replication (SRR)** – Copies objects to another bucket in the same AWS region.
- **Cross-Region Replication (CRR)** – Copies objects to a bucket in a different AWS region.

---

## **5. Amazon CloudFront (CDN)**

### **Definition:**
CloudFront is a Content Delivery Network (CDN) that caches and delivers content (images, videos, web pages) with low latency.

### **Purpose:**
Speeds up content delivery by distributing it across global edge locations.

### **Real-World Example:**
Streaming platforms like Netflix store copies of videos in multiple locations to load them faster.

### **Analogy:**
Instead of fetching a book from a faraway library, you get it from a nearby branch, reducing travel time.

---

**Bucket Policy Syntax**
```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::your-bucket-name/*"
    }
  ]
}

```

This cheat sheet provides essential details for AWS **S3, Versioning, Replication, Static Website Hosting, and CloudFront CDN**.

