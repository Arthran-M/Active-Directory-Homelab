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

<h2>Layout:</h2>




<h2>Environment Configuration</h2>
<p align="center">  
The domain that has been created: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Systems that have joined the domain within the enterprise environment:  <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image02.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Sucessfully deployed Wazuh agents:  <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image03.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Wazuh agent configuration files defining  policies for Windows endpoint groups:  <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image07.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Wazuh agent configuration files defining  policies for Linux endpoint group:  <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image08.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Wazuh monitoring setup:  <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image04.png" alt="image alt" width="80%" height="80%">
<br />
<br />
</p>



<h2>Attack Simulations</h2>
<p align="center">  
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image10.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image11.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image12.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image14.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image15.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image16.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image17.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image18.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image19.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image21.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image22.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image22.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image23.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image24.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image25.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image26.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image27.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image28.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image29.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image01.png" alt="image alt" width="80%" height="80%">
</p>



<h2>Detection and Monitoring</h2>
<p align="center">  
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image30.png" alt="image alt" width="80%" height="80%">
<br />
<br />
Launch the utility: <br/>
<img src="https://github.com/Arthran-M/Arthran-M/blob/a6ff3d61cae33e7a636015945ab868d76cb94359/Screenshots/image31.png" alt="image alt" width="80%" height="80%">
</p>


<h2>Lessons Learned</h2>







