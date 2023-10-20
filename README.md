# Sentinel-Lab

<h2>Description</h2>
In this lab, I created a live virtual machine on the Microsoft Azure Cloud Platform to create a honeypot that is connected to Microsoft Sentinel (SEIM). I used a Powershell script from this repository to create failed RDP logs and I also used a third-party API to collect geographic information from the attacker's location. We will observe live attacks (RDP Brute Force) from all around the world. The locations of these attackers will be plotted on a map for everyone to see! 
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/07encyr.png" height="100%" width="100%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Environments Used</h2>

- <b>Windows 10 </b>(22H2)


<h2>Attacks from Italy coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/twUuHkn.png" height="100%" width="100%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 15 hours~ (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/2ooeX4C.png)" height="100%" width="100%" alt="Image Analysis Dataflow"/>
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
