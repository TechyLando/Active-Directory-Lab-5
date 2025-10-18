<h1>Active Directory Lab 5</h1>

<h2>Description</h2>
Project consists of creating a Temporary Administrator User using Windows Powershell, then deleteing. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Azure Bastion</b> 
- <b>Windows Server Manager 2022 </b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Windows Power Shell <b/>
   

<h2>Program walk-through:</h2>

<p align="center">
Using Windows Powershell, checking to see current local administrators, adding "tempadmin" and passowrd: <br/>
<img src="https://i.imgur.com/lR72Uih.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Adding "tempadmin" user to administrators: <br/>
<img src="https://i.imgur.com/VsFG592.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Opening Local Users and Groups, going to Adminsitrators, to confirm the add: <br/>
<img src="https://i.imgur.com/FrgkxOu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Going back to Powershell to delete the "tempadmin" user from Administartors and Users:<br/>
<img src="https://i.imgur.com/InLbgol.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!
