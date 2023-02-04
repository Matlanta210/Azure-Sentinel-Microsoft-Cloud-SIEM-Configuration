# SIEM Configuration Using Microsoft Azure Sentinel
Azure Sentinel (Microsoft Cloud SIEM) Configuration

<h2>Description</h2>
In this lab, I configured and set up a SIEM using Azure Sentinel (Microsoft cloud SIEM) to gather information on an exposed Virtual Machine in the cloud. The exposed Virtual Machine will then be configured on the internet to attrack attackers all over the world. I then configured Log Analytics in Azure and ran a PowerShell script on the Virtual Machine, to extract metadata from the Windows Event Viewer to a 3rd party API. The API then maps out geographical data of the attackers in Azure Sentinel. The purpose of the lab was to gain experience with Azure cloud services, Azure Sentinel(SIEM), Virtual Machine, PowerShell, API and Windows Event Viewer. My main goal was to learn and understand the key components of a SIEM and how they can be used to monitor and secure an organzation. 




### In the first part of our home lab/SIEM project, we will configure a virtual machine on Azure with disabled firewalls to make it exposed to the internet. We will then configure Log Analytics where the geo data from the attacks on our virtual machine will be tracked and then sent over to our SIEM that will then eventually map the geo location of each attack in Azure. To conclude the first part of the lab, we will view event viewer to see the information on the successful and failed log in attempts from our RDP connection. The 2nd part of our lab we will be using RDP that will transmit the data from the attackers and then send it over to our 3rd party API that will track the latitude and longitude of the attacks and will display them in our Azure Sentinel/SIEM.


### [Here Is The Full Walk Through and YouTube Demonstration on Part 1 of this lab](https://www.youtube.com/watch?v=4rJB0yv6U-o)


 

Below is the Project Diagram we will be using curtesy of Josh Madakor

<br />
<img src="https://imgur.com/HfJsrmy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>VMware Virtual Machine</b>

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
