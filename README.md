
<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
I recently implemented an Active Directory (AD) environment using Windows Server 2019, integrated with a Windows 10 client machine. The project aimed to create a robust AD infrastructure, enhance security and access management via Keycloak, and perform security health checks using PingCastle.

I installed and configured Windows Server 2019 as the Domain Controller (DC) and set up DNS and DHCP for network management. I configured Active Directory Domain Services (AD DS), managing Organizational Units (OUs), user accounts, groups, and computer accounts. I also developed Group Policies to manage security settings, software installations, and user permissions.

For client-side integration, I joined a Windows 10 machine to the AD domain, enabling centralized management and policy enforcement. This included configuring domain user accounts for single sign-on (SSO) and network resource access.

To enhance security and access management, I deployed Keycloak. I configured it to work alongside AD for federated identity management, synchronizing user accounts and credentials for SSO across applications. I implemented Role-Based Access Control (RBAC) policies and configured multi-factor authentication (MFA) and fine-grained authorization policies.

Using PingCastle, I performed comprehensive AD security assessments. I conducted scans to identify vulnerabilities and misconfigurations, analyzed reports, and addressed key issues like weak passwords and outdated protocols. Regularly scheduled scans ensured ongoing AD security and compliance.

The project resulted in a stable, secure AD environment with Windows Server 2019 and Windows 10 integration. Centralized management improved operational efficiency. Keycloak provided robust identity and access management, and PingCastle ensured continuous AD security monitoring and improvement. This project demonstrated my ability to design, implement, and secure an AD environment using advanced tools.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Python</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Windows server 2019</b> 
- <b>Oracle Virtual Machine</b>
- <b>Keycloak</b>
- <b>PingCastle</b>


<h2>Program walk-through:</h2>

<p align="center">
Creating users with powershell : <br/>
<img src="https://imgur.com/3P9qNiE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center" >
Configurating the domain name and ip address of the server<br/>
 <img src="https://imgur.com/8lxGKCz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
creating client machine<br/>
 <img src="https://imgur.com/WBL6aM9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Creating an Admin user<br/>
 <img src="https://imgur.com/9NqCpCs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Creating Windows 10 vm<br/>
 <img src="https://imgur.com/wkaBo0E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Creating realm in keycloak<br/>
 <img src="https://imgur.com/ruYy0iI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Setting up all the configurations of LDAP Provider in keycloak<br/>
 <img src="https://imgur.com/QJQcAxs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Clients created in keycloak<br/>
 <img src="https://imgur.com/WZ94J0o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Creating a user in the admin section of keycloak<br/>
 <img src="https://imgur.com/WtBUGwP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
The user that was created in the admin section<br/>
 <img src="https://imgur.com/8vSrLNy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Interface of ping castle, where we are going to conduct a healthcheck of our AD<br/>
 <img src="https://imgur.com/9K3Z3BL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Result of healthcheck<br/>
 <img src="https://i.imgur.com/aItBy8w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />

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
