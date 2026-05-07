<h1>👨‍💻Enterprise Windows Server Hybrid Infrastructure Project:</h1>

<h2>Description</h2>
 <b> Designed and deployed a multi-phase, production-simulated enterprise environment. This lab replicates the full lifecycle of corporate IT operations: from foundational networking and Active Directory to high-availability storage, PKI security, and Hybrid Cloud integration with Microsoft Intune. Learning Material and Project Execution Time: 10/2026 to 5/2026 <br />


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
 
<b> Phase 3: Pictures:</b>
<h2></h2>

<p align="center">
Phase 3 - Joining Member Servers to the Domain and Placing them in the proper OU - PIC 1:  <br/>
<img src="https://media.licdn.com/dms/image/v2/D5622AQGl22wg5WW5PQ/feedshare-shrink_1280/B56Z2V_gjKGsAM-/0/1776337947045?e=1779926400&v=beta&t=AbqB_vIGkdw26hegX_08kPQjuLJpsleCRPxnUtCZqCI" height="80%" width="80%" alt="Phase 3 - Joining Member Servers to the Domain and Placing them in the proper OU - PIC 1"/>
<br />
 <h2></h2>
 
 <p align="center">
Phase 3 - After Installing the Role on the Memeber Servers, I added my account to the DHCP Admins Local Group:  <br/>
<img src="https://media.licdn.com/dms/image/v2/D5622AQEWzzFYronDMg/feedshare-image-high-res/B56Z2V_gf5IsAU-/0/1776337946822?e=1779926400&v=beta&t=ADy9E4WZd3qtTlZE68pjFnPLcdwzGpLVOCyKgVO5GFU" height="80%" width="80%" alt="Phase 3 - After Installing the Role on the Memeber Servers, I added my account to the DHCP Admins Local Group"/>
<br />
 <h2></h2>
 
 <p align="center">
Phase 3 - Configured the Client Network DHCP Scope and Scope Options on the Primary DHCP Server:  <br/>
<img src="https://media.licdn.com/dms/image/v2/D5622AQE0rCD-KW6FaA/feedshare-shrink_800/B56Z2V_gjXHAAg-/0/1776337947136?e=1779926400&v=beta&t=UrftFOH1vcsiwLtxqAgBNOxzvc83SoehH7KVt_2Zo6o" height="80%" width="80%" alt="Phase 3 - Configured the Client Network DHCP Scope and Scope Options on the Primary DHCP Server"/>
<br />
 <h2></h2>

  <p align="center">
Phase 3 - Configuring the DHCP Failover Cluster (Load Balanced Mode) with Shared Authentication - PIC 1:  <br/>
<img src="https://media.licdn.com/dms/image/v2/D5622AQHB8ksBx-4-yw/feedshare-shrink_480/B56Z2V_ggoHgAo-/0/1776337946877?e=1779926400&v=beta&t=SDI7uteo1oSCfWLUviWscRevneQflZeRG9FzpBZuvec" height="80%" width="80%" alt="Phase 3 - Configuring the DHCP Failover Cluster (Load Balanced Mode) with Shared Authentication - PIC 1"/>
<br />
 <h2></h2>

  <p align="center">
Phase 3 - Successful Implentation of DHCP Failover Cluster (Load Balanced Mode) with Shared Authentication:  <br/>
<img src="https://media.licdn.com/dms/image/v2/D5622AQFdRa5atuqK2A/feedshare-shrink_800/B56Z2V_ghMGwAc-/0/1776337946934?e=1779926400&v=beta&t=OVJs7M0dXxLo-QsU2bj0VO0NbSsDPthyPBCx05kIDzU" height="80%" width="80%" alt="Phase 3 - Successful Implentation of DHCP Failover Cluster (Load Balanced Mode) with Shared Authentication"/>
<br />
 <h2></h2>

   <p align="center">
Phase 3 - Client Successfully recived an DHCP address from the Client Network Scope:  <br/>
<img src="https://media.licdn.com/dms/image/v2/D5622AQG410GQAy9ZSA/feedshare-shrink_20/B56Z2V_ggkKMAI-/0/1776337946874?e=1779926400&v=beta&t=9J9m-GrUhFO83pFLvZbSWqzfBACnlnyO7A1trnvzRAw" height="80%" width="80%" alt="Phase 3 - Client Successfully recived an DHCP address from the Client Network Scope"/>
<br />
 <h2></h2>

   <p align="center">
Phase 3 - Client Successfully Has Joined the Domain now that it has a dhcp address:  <br/>
<img src="https://media.licdn.com/dms/image/v2/D5622AQGg5xvMoIW0cg/feedshare-image-high-res/B56Z2V_giGIIAU-/0/1776337947060?e=1779926400&v=beta&t=EJgw8E5uk0miaVALoEKPEwh3r0rcPPAjynLV6piFk0U" height="80%" width="80%" alt="Phase 3 - Client Successfully Has Joined the Domain now that it has a dhcp address"/>
<br />
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
 
<b> Phase 4 - Pictures:</b>
<p align="center">
Phase 4 - RAID - PIC 1:  <br/>
<img src="https://i.imgur.com/TkD3Zgy.png" height="80%" width="80%" alt="Phase 4 - RAID - PIC 11"/>
<br />
 <h2></h2>
 
<p align="center"> 
Phase 4 - RAID - PIC 2:  <br/>
<img src="https://i.imgur.com/3FGBXiG.png" height="80%" width="80%" alt="Phase 4 - RAID - PIC 2"/>
<br />
 <h2></h2>
 
<p align="center"> 
Phase 4 - RAID - PIC 3:  <br/>
<img src="https://i.imgur.com/oKGciPh.png" height="80%" width="80%" alt="Phase 4 - RAID - PIC 3"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Sucessful RAID - PIC 4:  <br/>
<img src="https://i.imgur.com/pnMsHSK.png" height="80%" width="80%" alt="Phase 4 - RAID - PIC 4 "/>
<br />
 <h2></h2>

  <p align="center"> 
Phase 4 - Storage Pool - PIC 1:  <br/>
<img src="https://i.imgur.com/y1DP69I.png" height="80%" width="80%" alt="Phase 4 - Storage Pool - PIC 1"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Storage Pool - PIC 2:  <br/>
<img src="https://i.imgur.com/IRuOdmg.png" height="80%" width="80%" alt="Phase 4 - Storage Pool - PIC 2"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - ISCSI Config - PIC 1:  <br/>
<img src="https://i.imgur.com/Vh2x6F4.png" height="80%" width="80%" alt="Phase 4 - ISCSI Config - PIC 1"/>
<br />
 <h2></h2>
  
 <p align="center"> 
Phase 4 - ISCSI Config - PIC 2:  <br/>
<img src="https://i.imgur.com/TRmr6Z9.png" height="80%" width="80%" alt="Phase 4 - ISCSI Config - PIC 2"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Sucessful ISCSI Config - PIC 3:  <br/>
<img src="https://i.imgur.com/s71OzID.png" height="80%" width="80%" alt="Phase 4 - ISCSI Config - PIC 3"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Share Drives and NTFS Permissions Implementation - PIC 1:  <br/>
<img src="https://i.imgur.com/A9QSIRD.png" height="80%" width="80%" alt="Phase 4 - Share Drives and NTFS Permissions Implementation - PIC 1"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Share Drives and NTFS Permissions Implementation - PIC 2:  <br/>
<img src="https://i.imgur.com/5ueaYdm.png" height="80%" width="80%" alt="Phase 4 - Share Drives and NTFS Permissions Implementation - PIC 2"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Sucessful Share Drives and NTFS Permissions Implementation - PIC 3:  <br/>
<img src="https://i.imgur.com/JvNanqd.png" height="80%" width="80%" alt="Phase 4 - Share Drives and NTFS Permissions Implementation - PIC 3"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Folder Redirection Configuration for Finance & Sales Dept - PIC 1:  <br/>
<img src="https://i.imgur.com/cjRAPPy.png" height="80%" width="80%" alt="Phase 4 - Folder Redirection Configuration for Finance & Sales Dept - PIC 1"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Successful Folder Redirection Configuration for Finance & Sales Dept - PIC 2:  <br/>
<img src="https://i.imgur.com/DDGLOkM.png" height="80%" width="80%" alt="Phase 4 - Successful Folder Redirection Configuration for Finance & Sales Dept - PIC 2"/>
<br />
 <h2></h2>

  <p align="center"> 
Phase 4 - FSRM - Configuring and Deploying Hard Qouta For the Deptment Share Drive:  <br/>
<img src="https://i.imgur.com/GeOosOR.png" height="80%" width="80%" alt="Phase 4 - FSRM - Configuring and Deploying Hard Qouta For the Deptment Share Drive"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - FSRM - Configuring and Deploying Active File Screens For the Deptment Share Drive - PIC 1:  <br/>
<img src="https://i.imgur.com/JgRld5k.png" height="80%" width="80%" alt="Phase 4 - FSRM - Configuring and Deploying Active File Screens For the Deptment Share Drive - PIC 1/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - FSRM - Successful Deployment of Active File Screens For the Deptment Share Drive:  <br/>
<img src="https://i.imgur.com/ZHXLJ6b.png" height="80%" width="80%" alt="Phase 4 - FSRM - Successful Deployment of Active File Screens For the Deptment Share Drive"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Configuring and Deploying a DFS Namespace:  <br/>
<img src="https://i.imgur.com/1O1IsHO.png" height="80%" width="80%" alt="Phase 4 - Configuring and Deploying a DFS Namespacee"/>
<br />
 <h2></h2>

  <p align="center"> 
Phase 4 - Configuring and Deploying a DFS Replication (With Replication Schedule) Group for Folders in the DFS Namespace - PIC 1 :  <br/>
<img src="https://i.imgur.com/Fq0Qwov.png" height="80%" width="80%" alt="Phase 4 - Configuring and Deploying a DFS Replication (With Replication Schedule) Group for Folders in the DFS Namespace"/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 4 - Successful Implementation of DFS Replication:  <br/>
<img src="https://i.imgur.com/RA5OeBK.png" height="80%" width="80%" alt="Phase 4 - Successful Implementation of DFS Replicatione"/>
<br />
 <h2></h2>

<b> Project Highlights:</b>
- <b> High-Availability Storage: Built a redundant storage stack using iSCSI SAN simulation, RAID 5, and Failover Clustering.</b>
- <b> Data Governance: Managed file shares via DFS-Namespaces and DFS-Replication, utilizing FSRM for hard quotas and active file screening.</b>

<h2></h2>

<h2>💼 Phase 4 Skills Demonstrated: </h2>
- <b>Storage Management | High Availability | DFS | FSRM | Windows Server | File Services | Access Control .</b>
<h2></h2>




<h2>🚀 Phase 5: COMING SOON </h2>


<b> PROJECT BY MALACHI BENTON <br />
  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
