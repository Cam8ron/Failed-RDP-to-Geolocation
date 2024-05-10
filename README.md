<h1>Failed RDP to IP Geolocation Information</h1>

<B> This repository contains a PowerShell script that parses Windows Event Log data to identify unsuccessful RDP attacks. The script also leverages a third-party API to obtain geographic information about the attacker's location. 

The script is utilized by showcasing the setup of Azure Sentinel, a Security Information and Event Management (SIEM) solution, to monitor a live virtual machine that acts as a honeypot. During the demonstration, we can observe live RDP brute force attacks originating from various locations worldwide. To plot the geolocation information of the attackers on an Azure Sentinel Map, I will utilize a custom PowerShell script.

<h2>Description</h2>
<b>This repository hosts a PowerShell script that extracts data from the Windows Event Log to identify unsuccessful Remote Desktop Protocol (RDP) attacks. Additionally, the script integrates with a third-party API to gather geolocation details about the attackers.
</b>
<br />
<br />
The script is featured in a demo where I establish Azure Sentinel (SIEM) and a live virtual machine acting as a honeypot. In this demo, we can observe active RDP brute force attacks coming from different regions worldwide. To chart the geolocation data of the attackers on an Azure Sentinel Map, I will use a tailored PowerShell script.
<br />
<br />

<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from Russia coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/gbyxhP1.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
