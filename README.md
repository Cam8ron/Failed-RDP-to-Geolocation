<h1>Failed RDP to IP Geolocation Information</h1>

<B> This repository contains a Home Lab that demonstrates the use of a PowerShell script to parse Windows Event Log data to identify unsuccessful RDP logons. The script also leverages a third-party API to obtain geographic information about the attacker's location. 

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
