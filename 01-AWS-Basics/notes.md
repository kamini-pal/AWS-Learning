# 🌩️ AWS Day 1 - Fundamentals

---

## 🔹 What is AWS?

AWS (Amazon Web Services) is a cloud computing platform provided by Amazon.

It allows you to:
- Run servers
- Store data
- Build applications
- Scale resources anytime

👉 Instead of buying physical hardware, you rent it from AWS.

---

## 🔹 Traditional IT vs Cloud Computing

### 🖥️ Traditional IT (On-Premises)

- You buy your own servers
- Setup in your office/data center
- Maintenance is your responsibility
- High cost (hardware + electricity + staff)

### ☁️ Cloud Computing

- Rent servers from AWS
- No physical setup needed
- Pay only for what you use
- Scalable (increase/decrease anytime)

### 🔁 Diagram

User → Internet → Cloud (AWS Data Center)

---

## 🔹 Types of Cloud Services

### 1. IaaS (Infrastructure as a Service)

- You get: Virtual machines, storage, networking
- You manage: OS, apps

👉 Example: EC2

---

### 2. PaaS (Platform as a Service)

- You get: Platform to build apps
- You don’t manage OS

👉 Example: AWS Elastic Beanstalk

---

### 3. SaaS (Software as a Service)

- Ready-to-use software
- No setup needed

👉 Example: Gmail, Zoom

---

## 🔹 Deployment Models of Cloud

### 1. Public Cloud
- Available for everyone
- Example: AWS

### 2. Private Cloud
- Used by one organization only

### 3. Hybrid Cloud
- Combination of public + private

---

## 🔹 AWS Pricing

AWS follows "Pay As You Go"

You pay for:
- Compute (EC2)
- Storage (S3)
- Data transfer

👉 No upfront cost

---

## 🔹 AWS Global Infrastructure

AWS has data centers worldwide.

It includes:
- Regions
- Availability Zones
- Edge Locations

---

## 🔹 What is AWS Region?

- A geographical area where AWS data centers are located

👉 Example:
- Mumbai (ap-south-1)
- US East (us-east-1)

---

## 🔹 What is Availability Zone (AZ)?

- One region contains multiple AZs
- Each AZ = one data center

👉 AZs are isolated but connected

---

## 🔹 What is Local Zone?

- Extension of AWS region
- Used for low-latency applications

---

## 🔹 Why AWS Regions Matter?

- Low latency (faster response)
- Data compliance (country rules)
- High availability

---

## 🔹 Example (Real World)

If your users are in India:
👉 Choose Mumbai region

Flow:
User → Internet → Mumbai Region → AZ → Server

---

## 🔹 Quick Revision

- AWS = Cloud platform
- IaaS = Infrastructure
- PaaS = Platform
- SaaS = Software
- Region = Location
- AZ = Data center

---

## 🔹 Interview Questions

Q1: What is AWS?
A: AWS is a cloud platform providing computing services.

Q2: Difference between IaaS, PaaS, SaaS?
A:
- IaaS → Control over infrastructure
- PaaS → Only app development
- SaaS → Ready-to-use software

Q3: What is an Availability Zone?
A: A data center inside a region.

Q4: What is AWS pricing model?
A: Pay-as-you-go model.

---

## 🔹 Common Mistakes

- Thinking AZ = Region ❌
- Ignoring region selection ❌
- Not understanding pricing ❌
