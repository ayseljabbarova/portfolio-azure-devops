# 🔵 Azure Network Deployment Project

This project demonstrates how I deployed a basic Azure network environment including a Virtual Network (VNet), Subnets, a Network Security Group (NSG), and a Virtual Machine (VM).  
It is one of the first practical labs in my Azure & DevOps learning journey.

---

## 🎯 Project Objectives
- Create a resource group  
- Deploy a Virtual Network and subnets  
- Create and attach a Network Security Group  
- Deploy a Windows or Linux Virtual Machine  
- Configure secure access (SSH)  
- Enable basic monitoring using Azure Monitor  

---

## 🛠️ Technologies Used
- Microsoft Azure  
- Azure Portal  
- Virtual Networks  
- Subnets  
- NSGs  
- Virtual Machines  
- Azure Monitor  

---

## 📌 Steps I Completed

### **1️⃣ Created a Resource Group**
- Name: `Rg_network_lab`
- Region: Central US 

---

### **2️⃣ Created a Virtual Network (VNet)**
- Name: `VNet-Lab`
- Address space example: `10.0.0.0/16`

---

### **3️⃣ Created Subnets**
- `Subnet-FrontEnd` – `10.0.1.0/24`  
- `Subnet-BackEnd` – `10.0.2.0/24`

---

### **4️⃣ Created Network Security Group (NSG)**
- Name: `NSG-Lab`
- Allowed inbound:
  - SSH (22) 
- Denied all other inbound traffic

---

### **5️⃣ Deployed a Virtual Machine**
- OS: (Linux)
- Size: Standard D2s v3
- Placed inside FrontEnd subnet
- Attached NSG  
- Configured admin username + password/SSH key

---

### **6️⃣ Enabled Monitoring**
- Connected VM to Log Analytics Workspace
- Enabled VM insights
- Viewed CPU / Disk / Network metrics

---


## 📚 What I Learned
- How Azure networking works  
- How NSGs filter traffic  
- How to deploy and secure a VM  
- How to structure resources in a resource group  
- Basics of monitoring and logging  

---


