# Security-Operation-Center-Analyst
# OVERVIEW
This lab focuses on creating a controlled, virtualized environment that mimics real world enterprise infrastructure to practice threat detection, analysis, and response. 
The goal of this lab is to simulate protecting an organizations digital assets by providing centralized monitoring to detect, analyze, and respond to cyber threats in real time from the perspective of a Blue Hat (defensive), while using a Red Hat (offensive) component to generate actionable alerts.


# ENVIRONMENT

<img width="171" height="183" alt="image" src="https://github.com/user-attachments/assets/546c9101-19e7-41f8-9206-1f100d0abc4a" />

<img width="242" height="180" alt="image" src="https://github.com/user-attachments/assets/cc9f9fc2-d35b-41ea-9329-a01053c617fa" />

<img width="283" height="112" alt="image" src="https://github.com/user-attachments/assets/80f32023-833a-408f-bcbe-fc17048ad3f3" />

<img width="487" height="47" alt="image" src="https://github.com/user-attachments/assets/ad9417ab-1707-4682-b28d-907f59dbf153" />

  
Virtual Machines:
* Winnie the Vulnerable (Windows 10 Pro, Sysmon, and Splunk) Blue Hat
* Kali in the Alley (Kali-Linux) Red Hat
  <img width="931" height="756" alt="image" src="https://github.com/user-attachments/assets/ff388672-b072-48ac-89bb-2bd20625c67f" />


Virtual Network:
* VNET - Gotham
<img width="681" height="566" alt="image" src="https://github.com/user-attachments/assets/ef8e941c-76fb-48b0-92f1-f3e8a62220bb" />

<img width="677" height="562" alt="image" src="https://github.com/user-attachments/assets/94f4884d-7e4f-40fd-a9c2-f9194c33e486" />

  
Subnet:
* 192.168.20.10/24 
* 192.168.20.11/24  
  
STEPS PERFORMED:

STEP1 Download the following applications required for this project : Virtualbox 7.0,
      Windows 10 Pro iso, Windows Media Checker, Windows C++ 2019 Redistributable              Package, Sysmon64, and Sysmonconfig.xml 
      config.xml, 7zip, and Kali-Linux VM
      <img width="336" height="598" alt="image" src="https://github.com/user-attachments/assets/51fc93dc-46ef-4b52-85ed-1399c8eb2dbf" />


  
STEP2 Install Virtualbox as Administrator accepting all of the defaults

  
STEP3 In Virtualbox, select New and enter a name for your VM.

  
STEP4 Uncheck Unattended Installation and click on Next


STEP5 In the ISO image field, browse to the location of your downloaded Windows 10 Pro 
      iso file.

      
STEP6 Double click on the Virtualbox icon to access the program


STEP8 Highlight System from the column on the left of the screen and select the                Motherboard Tab set the memory to 2048 0r 4096MB


STEP9 Under the Process Tab assign 2 CPUs and accept the remaining defaults


STEP10 Highlight Display from the column on the left of the screen and select the Screen        tab and set the Video Memory to 128MB and accept the remaining defaults


STEP11Highlight the Storage tab and confirm the information displayed is what you              selected during the initial configuration of Virtualbox.


STEP10Repeat Steps 3-11 to create the VM for Kali-Linux in Virtualbox
      
# VALIDATION CHECKS

* Open PowerShell as Admin, change directory to location of Sysmon and run Sysmon64.exe
  <img width="857" height="517" alt="image" src="https://github.com/user-attachments/assets/8ab356f9-0583-4ebc-a5c9-d8c4ba9b5602" />

* Verify that Sysmon is listed under Services in the Window 10Pro VM


* Verify that Sysmon is listed under Microsoft in the Event Viewer
  <img width="958" height="607" alt="image" src="https://github.com/user-attachments/assets/70f30394-c8a7-4ccf-8560-a1f8ed653400" />



* Ping Kali in the Alley from Winnie the Vulnerable
  <img width="535" height="495" alt="image" src="https://github.com/user-attachments/assets/b25f5832-ded3-4c06-8960-5d8c4480de4e" />

* You must configure your Windows firewall to accept ICMP traffic in order to ping         Winnie the Vulnerable from Kali in the Alley

# LESSONS LEARNED
* Prioritize tuning over suppression
* Prioritize critical thinking over technical skills
* Prevent burnout through rotation
* Implement "The Big Picture View"
* Document Everything

# SECURITY TAKEWAYS
* Fight like you train. Regular, rigorous training is a proactive necessity
* Get to the left of the breach by reducing the attack surface
* Master alert fatigue by prioritizing true threats
* Master SIEM/EDR tools to isolate systems
* Follow structured incident response playbooks in the midst of challenges

# FINAL OUTCOME
This lab successfully implemented controlled, virtual SOC while allowing me to protect Gotham's digital assets by providing centralized monitoring. I can detect, analyze, and respond to cyber threats in real time from the perspective of a Blue Hat (defensive), while using a Red Hat (offensive) component to generate actionable alerts.








