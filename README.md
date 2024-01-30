# Microsoft-Sentinel-Siem https://learn.microsoft.com/api/credentials/share/en-us/DareisNewton-9253/47F83B0C5B4AFB18?sharingId=A6292BECA0845FA8
Description


In this lab/project Were I was Able to earn an Applied Skills badge using Microsoft Azure used a Microsoft Virtual Machine as a honeypot, by turning off external firewall to expose to internet, to allow attackers to find VM, create a log repository in log analytics workspace, which will be used to injest logs from VM. Will watch failed logs in event viewer which i did purposely to see failed attempts looking for event id 4625 which shows failed attempts. 	Use ipgeolocation.io that has an API post ip in there will let you know the country that it came from state, province City Etc, use parameters to set custom log then send to log analytics workspace in Azure, Then Set up Azure Sentinel, Microsofts Cloud Native Siem which Provides threat protection, and investigation, I created a map where it shows where the attacks where coming from showing the country, and IP address over a 2 day span.

Resources used

Windows 10 Virtual Machine

Powershell

Log Analytics Workspace

Azure Sentinel

Workbook for Map


Project Details


Adding Vm To Log Analytics Workspace for injestion 
https://imgur.com/hlh5ZZ2

Failed Logon Attempts
https://imgur.com/aKGRKyH

You can See All Failed attempts in Windows Event Viewer
https://imgur.com/36IHhWZ

Also Can see Failed attempts in powershell
https://imgur.com/mNHfkmN

As the VM is exposed to internet you can see the logs populating as time goes by in log Analytics Workspace
https://imgur.com/JLpRaxo

Workbook of Map after a few hours
https://imgur.com/Zly6mCx

Workbook of manp after a full day added some features where you can see the country the attempts are coming from as well
https://imgur.com/kzTSe28
