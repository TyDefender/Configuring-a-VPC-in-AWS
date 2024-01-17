<h1>Configuring and securing a VPC in AWS</h1>

<h2>Description</h2>
Just wrapped up a project where I took AWS VPC configuration to the next level. Created the VPC, defined the CIDR block, and set up subnets across different zones. Launched a duo of web servers – one private, one flaunting in public, armed with a new key pairs for secure access.

Played around with route tables and Internet Gateways to make that traffic dance to my tune. Security-wise, I crafted a security group allowing SSH – can't compromise on that front. The real excitement kicked in when I connected to my public EC2 instance via SSH.

To finished the project off I blocked access to my public web server using an ACL rule, and then brought it back to life. Flexing those AWS muscles and gaining a better understanding of configuring a VPC on AWS<br/>

<h2>Shell Script</h2>

<b>sudo tcpdump -#XXtttt host skyroute66.com -w captured.pcap -C 1 -G 600</b>
- <b>(XX) hexadecimal</b> 
- <b>(tttt) timestamp</b>
- <b>(-w) write</b>
- <b>(-C) Limits the size in megabytes</b>
- <b>(-G) Limits the time in seconds</b>

<h2>Tools Used</h2>

- <b>tcpdump</b> 
- <b>Shell Scripting</b>
- <b>Visual Code Studio</b>
- <b>Wireshark</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b>

<h2>Project walk-through:</h2>

<p align="center">
Create a script (watchdog.sh) designed to execute a targeted tcpdump for skyroute66.com<br/>
<img src="https://i.imgur.com/rus4X38.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use integrated terminal to make watchdog.sh executable<br/>
<img src="https://i.imgur.com/JIFOR2I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visit site to genrate traffic and dump to capture.pcap<br/>
<img src="https://i.imgur.com/H8Kqin1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upload dump file to Wireshark for further analysis<br/>
<img src="https://i.imgur.com/WdWTF2S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
