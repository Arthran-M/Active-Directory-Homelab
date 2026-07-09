<h1>Enterprise Cybersecurity Homelab</h1>


<h2>Description</h2>

<p>
This project involved building a simulated enterprise business network using six virtual machines connected through a private NAT network to recreate a realistic on-premises IT environment. The lab 
consisted of a Windows Server Active Directory Domain Controller, Windows and Linux client workstations, a dedicated Ubuntu email server, as well as a 
Kali Linux attacker machine. A dedicated machine was configured to host Wazu, which was used for centralised security monitoring, log collection, endpoint detection and response (EDR/XDR) capabilities and vulnerability detection.
</p>

<p>
The Active Directory Domain Controller provided core enterprise services including DNS, DHCP and Single Sign On (SSO), which allowed for centralised identity 
and access management for doamin-joined systems. 
After provisioning and configuring the infrastructure, the lab was used to simulate common attack scenarios against the enterprise environment. These included 
phishing-based credential capture, brute force authentication attacks and remote administration using WinRM and RDP. Wazuh was used to collect the resulting security events, demonstrating 
how endpoint activity and authentication events can be monitored within a centralised SIEM. 
</p>

<p>
The primary objective of this project was to develop practical experience with enterprise infrastructure, Active Directory administration, Windows and Linux system management, virtual networking, SIEM deployment
and security operations workflows within a controlled lab environment.
</p>



<h2>Tools Used</h2>

- <b>Microsoft Active Directory</b> 
- <b>Wazuh SIEM</b>
- <b>Mailhog</b>
- <b>Evil-WinRM</b>
- <b>Hydra</b>
- <b>NetExec</b>
- <b>XFreeRDP</b>


<h2>Environments Used</h2>

- <b>Windows Server 2025</b> 
- <b>Windows 11 Enterprise</b> 
- <b>Ubuntu Desktop</b> 
- <b>Ubuntu Server 2022</b> 
- <b>Kali Linux</b> 

<h2>Topology:</h2>





<h2>Environment Configuration</h2>


<h2>Attack Simulations</h2>



<h2>Detection and Monitoring</h2>





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


