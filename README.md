# SIEM-Azure-Sentinel-Project

Description

The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.

The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to look up the attackers Geolocation information and plot it on an Azure Sentinel Map!

![Screenshot 2024-08-21 015607](https://github.com/user-attachments/assets/5cd9a744-5695-437a-a738-607e188d5270)

Languages Used
PowerShell: Extract RDP failed logon logs from Windows Event Viewer

Utilities Used
ipgeolocation.io: IP Address to Geolocation API

Attacks from Switzerland,Zurich coming in; Custom logs being output with geodata

![Screenshot 2024-08-21 020143](https://github.com/user-attachments/assets/2a29c44e-7874-4443-9bad-bfbfbd7d5928)

World map of incoming attacks after 24 hours (built custom logs including geodata)

![image](https://github.com/user-attachments/assets/1907fa6c-3fb7-46e7-b22c-52bcba4d210f)

