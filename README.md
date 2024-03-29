<h1>Kali Linux | Windows 10 Homelab with Virtual Box (Hacking into Windows from Linux) Part 1: Networking</h1>


 ### [Video Demonstration](https://youtu.be/Zi2vE54___Q)


<h2>Description</h2>
<b>In part 1 of this tutorial, I will be setting up an internal network between two virtual machines using basic networking. 

This is to ensure any malware is completely isolated to the sandbox environment, having no access to personal networks or devices connected to my network.
</b>
<br />
<br />

<h2>Languages Used</h2>

- <b>Command Prompt</b> 

<h2>Utilities Used</h2>

- <b>VirtualBox</b>
- Microsoft Windows 10 ISO
- Kali Linux 

<h2>1. Download VirtualBox</h2>

<p align="center">
<img src="https://i.imgur.com/CGDpVTG.png" (https://imgur.com/2MViSiL) height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>2. Download Windows 10 Media Tool</h2>
<p align="center">

<img src="https://i.imgur.com/S3MUqyx.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>3. Create an ISO using the Media Tool</h2>

<p align="center">
<img src="https://i.imgur.com/LJrvbUW.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>4. Download Kali Linux</h2>

<p align="center">
<img src="https://i.imgur.com/szPqev8.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>5. Locate ISO in Virtual Box (for Windows) > do the same for Kali, but double click the file that downloads and it will populate in VirtualBox automatically</h2>


<p align="center">
<img src="https://i.imgur.com/KHVOQKQ.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>6. Set snapshots for both Windows and Linux</h2>


<p align="center">
<img src="https://i.imgur.com/PGJ81um.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>7. Set internal network for Linux</h2>


<p align="center">
<img src="https://i.imgur.com/fTb4kSn.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>8. Set internal network for Windows</h2>


<p align="center">
<img src="https://i.imgur.com/sES8GAo.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>9. Set up Windows 10 Pro</h2>


<p align="center">
<img src="https://i.imgur.com/nFuj56x.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>10. Set static IP in Windows to 192.168.20.10</h2>


<p align="center">
<img src="https://i.imgur.com/PFdkv7U.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>11. Set static IP in Linux to 192.168.20.11 > set Netmask at 24</h2>


<p align="center">
<img src="https://i.imgur.com/VqTS7B3.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>12. Ping Linux from Windows to confirm both are connected | NOTE: if you try to ping from Linux at this point, it won't go through because the firewall is enabled for Windows. Don't disable as we need it running for Part 2, so just ping from Linux.</h2>
<p align="center">
<img src="https://i.imgur.com/35Zb42j.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
