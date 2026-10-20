# SOC-Lab-using-WAZUH

## Objective  
The SOC-Lab-using-WAZUH project aimed to design, deploy, and document a hands-on Home SOC Lab using Wazuh (SIEM/XDR). This lab simulates real-world enterprise network architecture and endpoint telemetry generation to develop practical skills in threat detection, SIEM log analysis, rule customization, and automated incident response.

## Skills Learned 
- Advanced understanding of WAZUH concepts and practical application.
- Proficiency in analyzing and interpreting endpoint logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of Windows Event Logs (`Sysmon`) event IDs.
- Development of critical thinking and problem-solving skills in cybersecurity.
  
## Tools Used
<div>
  <img src="https://img.shields.io/badge/Wazuh-000000?style=for-the-badge&logo=wazuh&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows_10-0078D6?style=for-the-badge&logo=windows10&logoColor=white" />
  <img src="https://img.shields.io/badge/VMware_Workstation_Pro-60B5E5?style=for-the-badge&logo=vmware&logoColor=white" />
  <img src="https://img.shields.io/badge/Sysmon-0078D4?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/RDP-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/CMD-000000?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/SSH-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</div>

##  Lab Architecture 
- **SIEM / XDR:** Wazuh (Manager, Indexer, Dashboard)
- **Virtualization:** VMware Workstation Pro
- **Monitored Endpoints:** Ubuntu Linux ,Ubuntu Server ,Windows 10
- **Log Types:** Syslog, Windows Event Logs (`Sysmon`)
- **Framework Alignment:** MITRE ATT&CK®

## Steps
1- WAZUH Server Preparation
  - Downloaded ubuntu server iso and installed it on VMware Workstation Pro
  - Used SSH from my host to ubuntu server and started to download wazuh
  - Got my credentials and logged into wazuh API
  - <img width="1917" height="822" alt="Screenshot 2026-10-17 163807" src="https://github.com/user-attachments/assets/a5c2adfa-74b8-4cec-8ee3-88d68f0181e7" />
2- WAZUH Agents
  - Downloaded and installed windows10 , another ubuntu server on VMware
  - Started to deploy my agents WAZUH-Windows , WAZUH-linux
    
 -   <img width="1911" height="597" alt="Screenshot 2026-10-18 163424" src="https://github.com/user-attachments/assets/74eb6afa-d66a-4462-87f8-77bf92477b65" />
    
3- Reading the Logs

 -   <img width="1917" height="875" alt="Screenshot 2026-10-18 180558" src="https://github.com/user-attachments/assets/c8130ebb-69d1-4513-8f14-a22c55631e1a" />
    
4- Building Dashboard

 -   <img width="1917" height="798" alt="Screenshot 2026-10-18 163334" src="https://github.com/user-attachments/assets/5c79bd49-2a64-4010-b6dd-f572b12d0568" />
 
5- Doing Danger Things

 -   <img width="1901" height="823" alt="Screenshot 2026-10-18 163407" src="https://github.com/user-attachments/assets/17a9d1a4-adfe-469e-b262-f8ddd3b69dd8" />
 
6- File Integrity Monitoring (FIM)

 -   <img width="1917" height="816" alt="Screenshot 2026-10-18 164002" src="https://github.com/user-attachments/assets/f4818e39-4012-4daf-a279-35a34fdca11e" />
 
7- IT Hygiene

 -  <img width="1907" height="862" alt="Screenshot 2026-10-18 163511" src="https://github.com/user-attachments/assets/8593c2bf-888e-4896-86c2-f0e156dc044f" />





  
