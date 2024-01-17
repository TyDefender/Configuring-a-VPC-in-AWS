<h1>Configuring and securing a VPC in AWS</h1>

<h2>Description</h2>
Just wrapped up this project where I took AWS VPC configuration to the next level. Created the VPC, defined the CIDR block, and set up subnets across different zones. Launched a duo of web servers – one private, one flaunting in public, armed with a new key pairs for secure access.

Played around with route tables and Internet Gateways to make that traffic dance to my tune. Security-wise, I crafted a security group allowing SSH – can't compromise on that front. The real excitement kicked in when I connected to my public EC2 instance via SSH. Finishing the project off I blocked access to my public web server using an ACL rule, and then brought it back to life. Flexing those AWS muscles and gaining a better understanding of configuring a VPC on AWS<br/>

<h2>Tools and Services Used</h2>

- <b>EC2</b> 
- <b>VPC</b> 
- <b>SSH</b>
- <b>ACL</b>

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>Project walk-through:</h2>

<p align="center">
Create a VPC and Define CIDR<br/>
<img src="https://i.imgur.com/sZXIFE8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a Public and Private Subnet<br/>
<img src="https://i.imgur.com/XpeFObl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a Internet Gateway<br/>
<img src="https://i.imgur.com/IZo4UGc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create New Routing Table and Target Internet Gateway<br/>
<img src="https://i.imgur.com/u6LIiaM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch Private and Public EC2 Instances<br/>
<img src="https://i.imgur.com/a2Rf53k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Security Group to Allow SSH Access to EC2 Instances<br/>
<img src="https://i.imgur.com/WfeiO2h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Access Instances with SSH<br/>
<img src="https://i.imgur.com/ZtRQ10J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add ACL Rule to Block and Unblock Access<br/>
<img src="https://i.imgur.com/HFAdiIr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
