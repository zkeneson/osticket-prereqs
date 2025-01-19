<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install OS Ticket and Install / Enable IIS in Windows with CGI

<h2>Installation Steps</h2>

<p>
<img width="881" alt="image" src="https://github.com/user-attachments/assets/507b1e54-ac29-433e-88b9-facd6f1cce3b" />


</p>
<p>
Install OS Ticket on Windows VM
</p>
<br />

<p>


</p>
<p>
Install and enable IIS with CGI
</p>
<br />

<p>
<img width="808" alt="image" src="https://github.com/user-attachments/assets/0da707ec-738c-4488-a035-ce2e92c5a6aa" />

</p>
<p>
From the Windows VM (Client-1), open PowerShell and ping the static IP address. Then, run ipconfig /all and observe the DNS server address is the static IP of the DC.
</p>
<br />

<p>
<img width="1550" alt="image" src="https://github.com/user-attachments/assets/225dc840-a1bb-4912-b22f-c166d6f354aa" />


</p>
<p>
Create Active Directory Employees using PowerShell script and observe the new list of generated Employees. 
</p>
<br />

<p>
<img width="1578" alt="image" src="https://github.com/user-attachments/assets/a39ed57a-a399-4abd-95e8-9ca4d6779ed9" />

</p>
<p>
In the Domain Controller VM, create an Account Lockout Policy within the Group Policy Management Editor. 
</p>
<br />



