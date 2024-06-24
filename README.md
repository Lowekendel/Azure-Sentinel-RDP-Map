<h1>Azure Sentinel RDP Map</h1>

 

<h2>Description</h2>
I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. I am able to observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map!
<br />


<h2>Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Azure Sentinel</b>
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Pinging VM to make sure connection is secure: <br/>
<img src="https://i.imgur.com/VhMUEef.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run script to get GeoData from attackers:  <br/>
<img src="https://i.imgur.com/4peQLNH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Extracting Fields from Raw Data: <br/>
<img src="https://i.imgur.com/zs0EaWc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Overview of Failed login attempts:  <br/>
<img src="https://i.imgur.com/n89II3r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
--!>
