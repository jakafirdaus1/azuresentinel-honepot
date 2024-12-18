# Microsoft Azure Sentinel SIEM and Honey Pot

FAILED RDP to IP Geolocation Information

<h2>Description</h2>
<p align="center"> 
<img src="https://i.imgur.com/rwb6tTB.png" height="35%" width="35%"  />
</p>
In this project, i set up a Microsoft Azure Sentinel and connect it to a live Virtual Machine acting as a honey pot. I used Powershell script that is responsible for parsing out Windows Event Log for failed RDP attacks and using third party API to collect geographic information about the attackers location.</br> 
I will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and Kusto Query Language to plot it on an Azure Sentinel Map!</br>

<h2>Failed RDP (Attackers Public IP)</h2>
<img src="https://i.imgur.com/N8zsXO0.png" height="80%" width="80%" />

<h2>Using third party API to collect geographic info about the attackers location</h2>
<b>Language used: PowerShell</b>
<img src="https://i.imgur.com/u32PDE0.png" height="80%" width="80%" />
<h2>Azure World Map of RDP Brute Force Attack After 12 Hours <br/></h2>
<img src="https://i.imgur.com/IvewDya.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>
(KQL Language Used in this project is attached.</br> Please refer to this repo "https://github.com/joshmadakor1/Sentinel-Lab/blob/main/Custom_Security_Log_Exporter.ps1" for the Powershell Script)
<h2>Conclusion</h2>
This home lab offers a valuable environment for learning and practicing essential skills in security monitoring and incident response using Azure Sentinel SIEM. By completing this project, i gained hands-on experience with a SIEM, which enhanced my security monitoring skills.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
