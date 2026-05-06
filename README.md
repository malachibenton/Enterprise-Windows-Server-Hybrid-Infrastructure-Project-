<h1>👨‍💻Enterprise Windows Server Hybrid Infrastructure Project:</h1>

<h2>Description</h2>
 <b> Designed and deployed a multi-phase, production-simulated enterprise environment. This lab replicates the full lifecycle of corporate IT operations: from foundational networking and Active Directory to high-availability storage, PKI security, and Hybrid Cloud integration with Microsoft Intune. <br />

<h2>🏗️ Infrastructure Stack</h2>


- <b>  Operating Systems & Networking: 1 Cisco CSR1000v Router , 4 Windows Servers (2022/2025), 1 Windows 11.</b> 
- <b>  Identity: Active Directory Domain Services (AD DS) with Hybrid Azure AD Join.</b> 
- <b>  Management: Microsoft Intune, Windows Autopilot, Group Policy (GPO), WSUS.</b> 
- <b>  Security: AD CS (PKI), NPS (RADIUS), Cisco VPN, PowerShell Script Block Logging GPO. </b> 
- <b>  Storage: DFS-R, Failover Clustering, iSCSI SAN Simulation, FSRM. </b> 


<h2>🚀 Phase 2: Active Directory & Group Policy Deployment: </h2>
<b> (DeleteAFTER) Pics here:</b>
<h2></h2>

<b> Project Highlights:</b>
- <b> Structured OU hierarchy for scalable user and device management: Using the "Tiered Administration mixed with Department OU Structure".</b>
- <b> Utilized PowerShell scripts & CSV files for bulk user creation and OU delegation.</b>
- <b> Implemented enterprise-wide GPOs, including restricted execution policies, firewall rules, and PowerShell Script Block Logging for forensic visibility..</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

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
