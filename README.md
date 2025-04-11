# PowerShell Download Automation Playbook
This repository contains all the code for the PowerShell Download Automation Playbook, an Azure Logic App that automates incident response for suspicious PowerShell download activities detected in Microsoft Sentinel. It triggers on incidents, isolates devices, collects data (DeviceId, email logs, URLs, SHA256 hashes), saves reports to OneDrive, analyzes threats with VirusTotal and Microsoft Defender, and executes remediation like file removal or password resets, with recommendations for forensics and device restoration if compromised.

## Top to bottom Logic App Overview

### Part 1
<p align="center">
  <img src="images/1.PNG" />
</p>

### Part 2
<p align="center">
  <img src="images/2.PNG" />
</p>

### Part 3
<p align="center">
  <img src="images/3.PNG" />
</p>

### Part 4
<p align="center">
  <img src="images/4.PNG" />
</p>

### Part 5
<p align="center">
  <img src="images/5.PNG" />
</p>

### Part 6
<p align="center">
  <img src="images/6.PNG" />
</p>

### Part 7
<p align="center">
  <img src="images/7.PNG" />
</p>
