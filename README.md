# Security-Operation-Center-Analyst
# OVERVIEW
This lab focuses on creating a controlled, virtualized environment that mimics real world enterprise infrastructure to practice threat detection, analysis, and response. 
The goal of this lab is to simulate protecting an organizations digital assets by providing centralized monitoring to detect, analyze, and respond to cyber threats in real time from the perspective of a Blue Hat (defensive), while using a Red Hat (offensive) component to generate actionable alerts.
# ENVIRONMENT
Virtual Network:
* VNET - Gotham
Subnet:
* 192.168.20.10/24 
* 192.168.20.11/24
  
Virtual Machines:
* Winnie the Vulnerable (Windows 10 Pro, Sysmon, and Splunk) Blue Hat
* Kali in the Alley (Kali-Linux) Red Hat
  
STEPS PERFORMED:

STEP1 Download the following applications required for this project : Virtualbox 7.0,
      Windows 10 Pro iso, Windows Media Checker, Windows C++ 2019 Redistributable              Package, Sysmon64, and Sysmonconfig.xml 
      config.xml, 7zip, and Kali-Linux VM

  
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

* Verify that Sysmon is listed under Services in the Window 10Pro VM


* Verify that Sysmon is listed under Microsoft in the Event Viewer


* Ping Kali in the Alley from Winnie the Vulnerable


* Ping 192.168.20.11 from 192.168.20.10


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








