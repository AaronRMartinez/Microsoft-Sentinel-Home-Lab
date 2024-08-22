# Microsoft-Sentinel-Home-Lab

## Description 

**Creating a honeypot with a virtual machine hosted on Azure and utilizing Microsoft Sentinel to map the location and magnitude of the RDP attacks on the VM**

Utilized a custom PowerShell script to extract and forward Windows Event Viewer metadata to a third party API to derive geolocation data. A Log Analytics Workspace in Azure was set up to ingest the custom logs containing the geographic information (latitude, longitude, state/province, and country). A Table was configured in the Log Analytics Workspace to map geo data in Microsoft Sentinel. Then built a Microsoft Sentinel (Azure SIEM) workbook to display global RDP brute force attacks on world map, indicating the physical location of the attacks and their magnitude.

## Languages Used

**PowerShell:** Script used to extract and forward Windows Event Viewer metadata of RDP failed logon logs

## Utilities

**ipgeolocation.io:** IP Address to Geolocation API

## PowerShell Script Generating Custom Logs with the Geodata

## Microsoft Sentinel World Map Displaying RDP Attacks and the Magnitude on the VM
