# PowerShell Download Automation Playbook
This repository contains all the code for the PowerShell Download Automation Playbook, an Azure Logic App that automates incident response for suspicious PowerShell download activities detected in Microsoft Sentinel. It triggers on incidents, isolates devices, collects data (DeviceId, email logs, URLs, SHA256 hashes), saves reports to OneDrive, analyzes threats with VirusTotal and Microsoft Defender, and executes remediation like file removal or password resets, with recommendations for forensics and device restoration if compromised.

## Step-by-step Logic App Overview

### 🟢 Step 1: Trigger - When a Sentinel Incident is Created
![Step 1](images/1.png)

### 📦 Step 2: Parse Incident JSON
![Step 2](images/2.png)

### 🧩 Step 3: Extract Entities (DeviceId, AccountUPN)
![Step 3](images/3.png)

### 🧠 Step 4: Initialize Variables
![Step 4](images/4.png)

### 🔄 Step 5: Conditions or Loops (if any)
![Step 5](images/5.png)

### 🔗 Step 6: External API Calls / Enrichment
![Step 6](images/6.png)

### ✉️ Step 7: Notifications or Final Actions
![Step 7](images/7.png)
