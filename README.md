# Sentinel-Lab
 ### [Video Demonstration](https://www.loom.com/share/12a6a53af2f84d19bf03d8c96b579879?sid=898e61dd-0c41-4c2c-a591-1b468e8c9683)
<h2>Description</h2>
In this lab, I created a live virtual machine on the Microsoft Azure Cloud Platform to function as a honeypot, which was integrated with Microsoft Sentinel (SEIM). I used a Powershell script from this repository to create failed RDP logs. Additionally, I used a third-party API to collect geographic information from the attacker's location. The outcome of this exercise is the real-time monitoring and analysis of live cyberattacks, specifically focusing on RDP Brute Force attacks. The geographic locations of these threat actors will be visually mapped for everyone to see!
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
<img src="https://i.imgur.com/Kouf3ls.png)" height="100%" width="100%" alt="Image Analysis Dataflow"/>
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
