<h1>👨‍💻Enterprise Windows Server Hybrid Infrastructure Project:</h1>

<h2>Description</h2>
 <b> Designed and deployed a multi-phase, production-simulated enterprise environment. This lab replicates the full lifecycle of corporate IT operations: from foundational networking and Active Directory to high-availability storage, PKI security, and Hybrid Cloud integration with Microsoft Intune. <br />


<h2>🏗️ Infrastructure Stack</h2>


- <b>  Operating Systems & Networking: 1 Cisco CSR1000v Router , 4 Windows Servers (2022/2025), 1 Windows 11.</b> 
- <b>  Identity: Active Directory Domain Services (AD DS) with Hybrid Azure AD Join.</b> 
- <b>  Management: Microsoft Intune, Windows Autopilot, Group Policy (GPO), WSUS.</b> 
- <b>  Security: AD CS (PKI), NPS (RADIUS), Cisco VPN, PowerShell Script Block Logging GPO. </b> 
- <b>  Storage: DFS-R, Failover Clustering, iSCSI SAN Simulation, FSRM. </b> 

<h2>🚀 Phase 1: Network Infrastructure Deployment: </h2>
<b> (DeleteAFTER) Pics here:</b>
<h2></h2>

<b> Project Highlights:</b>
- <b> Deployed a virtualized enterprise environment using Hyper-V.</b>
- <b> Configured Cisco CSR1000v for routing and NAT.</b>
- <b> Validated full network connectivity across the environment.</b>
<h2></h2>


<h2>🚀 Phase 2: Active Directory & Group Policy Deployment: </h2>

<h2>🔧 Key Implementations:</h2>

- <b>✔️ Installed and configured Active Directory Domain Services (AD DS) </b>
- <b>✔️ Designed Organizational Unit (OU) structure for logical administration</b>
- <b>✔️ Automated user account creation using PowerShell + CSV</b>
- <b>✔️ Implemented Group Policy Objects (GPOs) to enforce: Password and account lockout policies • Windows Defender Firewall configurations • Logon banners and software deployment (I know its not ideal to do with GPOs instead Microsoft Intune, but wanted to perform it) • Printer deployment • PowerShell execution policy restrictions • Script Block Logging for enhanced visibility </b>
<h2></h2>

<b> (DeleteAFTER) Pics here:</b>
<h2></h2>

<b> Project Highlights:</b>
- <b> Structured OU hierarchy for scalable user and device management: Using the "Tiered Administration mixed with Department OU Structure".</b>
- <b> Utilized PowerShell scripts & CSV files for bulk user creation and OU delegation.</b>
- <b> Implemented enterprise-wide GPOs, including restricted execution policies, firewall rules, and PowerShell Script Block Logging for forensic visibility..</b>
<h2></h2>

<h2>💼 Phase 2 Skills Demonstrated: </h2>
- <b> Active Directory | Group Policy | Identity & Access Management (IAM) PowerShell Automation | Security Policy Enforcement | Windows Server </b>
<h2></h2>

<h2>🚀 Phase 3: Core Network Services Deployment: </h2>


<h2>🔧 Key Implementations:</h2>

- <b>✔️ Deployed the DNS Server Role to the Domain Controller (Primary Zone AD-Integrated Holder) </b>
- <b>✔️ Deployed a Forward Secondary & Stub Lookup Zones on Member Servers </b>
- <b>✔️Configured DNS Record Aging and Scavenging Policies </b>
- <b>✔️Configured a Conditional Forwarder </b>
- <b>✔️Deployed DHCP Servers with failover (with Shared secret authentication for secure replication (similar to OSPF) to member servers (load balancing mode)</b>
- <b>✔️Scope configuration for the Client Network Subnet (According to the Network Topology from Phase 1) </b>

 <h2></h2>
<b> (DeleteAFTER) Pics here:</b>
<h2></h2>

<b> Project Highlights:</b>
- <b> Configured DHCP Failover and optimized DNS (Aging/Scavenging, Stub Zones) for network resilience.</b>
- <b> Reliable IP address assignment across client systems.</b>

<h2></h2>

<h2>💼 Phase 3 Skills Demonstrated: </h2>
- <b> DNS Administration | DHCP Configuration | High Availability Network Services | Windows Server .</b>
<h2></h2>

<h2>🚀 Phase 4: File Services, Storage & High Availability: </h2>


<h2>🔧 Key Implementations:</h2>

- <b>✔️Configured and implemented redundant storage using RAID 5  </b>
- <b>✔️Configured Storage Spaces and iSCSI (SAN simulation) for centralized storage access </b>
- <b>✔️Deployed File Server with shared drives and folder redirection </b>
- <b>✔️Implemented NTFS and share permissions for role-based access control </b>
- <b>✔️Enhanced storage management with File Server Resource Manager (FSRM): Hard quotas to control disk usage & Active file screening to enforce file policies</b>
- <b>✔️Configured Distributed File System (DFS): Namespace for unified file access and Replication (DFS-R) with scheduled sync for redundancy </b>

 <h2></h2>
<b> (DeleteAFTER) Pics here:</b>
<h2></h2>

<b> Project Highlights:</b>
- <b> High-Availability Storage: Built a redundant storage stack using iSCSI SAN simulation, RAID 5, and Failover Clustering.</b>
- <b> Data Governance: Managed file shares via DFS-Namespaces and DFS-Replication, utilizing FSRM for hard quotas and active file screening.</b>


<h2></h2>

<h2>💼 Phase 4 Skills Demonstrated: </h2>
- <b>Storage Management | High Availability | DFS | FSRM | Windows Server | File Services | Access Control .</b>
<h2></h2>


<b> (DeleteAFTER) EDIT PICS here:</b>


<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
