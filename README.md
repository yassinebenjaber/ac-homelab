# **Active Directory & Security Management with Keycloak**

## **Description**
I implemented an **Active Directory (AD) environment** using **Windows Server 2019**, integrated with a **Windows 10 client machine** for centralized management and security enforcement.

### **Key Implementations**
- **Active Directory Setup:** Configured **AD DS**, **DNS**, **DHCP**, and **Group Policies** for user and system management.  
- **Client Integration:** Joined a Windows 10 machine to the **AD domain**, enabling **SSO** and centralized policy control.  
- **Keycloak Integration:**  
  - Connected Keycloak to **AD via LDAP** for **federated identity management**.  
  - Implemented **SSO** across apps and enforced **MFA (TOTP-based)** for security.  
- **Security Assessments:** Used **PingCastle** for **AD security audits**, identifying vulnerabilities and enforcing best practices.

This project ensured **secure access management, centralized authentication, and continuous security monitoring** in an **enterprise-grade AD environment**.

---

## **Languages & Utilities Used**
- **PowerShell**  
- **Python**

## **Environments Used**
- **Virtual Box**  
- **Windows Server 2019**  
- **Windows 10**  
- **Keycloak**  
- **PingCastle**


<h2>Program walk-through:</h2>

<p align="center">
Creating users with powershell : <br/>
<img src="https://imgur.com/3P9qNiE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<p align="center" >
Configurating the domain name and ip address of the server<br/>
 <img src="https://imgur.com/0sfqD0y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
creating client machine<br/>
 <img src="https://imgur.com/k1k3aa2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center" >
Creating an Admin user<br/>
 <img src="https://imgur.com/1EYB4hl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
