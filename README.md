# Blue Team Concepts and Terminology

This page aims to give people an idea of concepts and terminology related to Blue Teaming in a digestible manner.

# <span style="font-size: 28px;">Incident Handling</span>
When personal and business data is compromised, swiftly responding and effectively investigating is critical. After the investigation, remediation should be done to resolve the disruption. An essential step in this process is prioritization, which involves first handling the most critical alerts. 

# <span style="font-size: 28px;">Events</span>
Actions that happen throughout a network/system

# <span style="font-size: 28px;">Incidents</span>
Events with adverse outcomes (unauthorized access, installation of malware)

# <span style="font-size: 28px;">Cyber Kill Chain (7 Steps)</span>
Recon > Weaponize > Deliver > Exploit > Install > C&C > Action

Recon
In the initial stage, the attacker chooses a target and performs information gathering (OSINT). They want to gather as much information as possible. Information from this stage can be used later on throughout the kill chain. Attackers will use passive and active gathering methods (think Social Media and scanning external sites).

Weaponize
In this stage, malware is developed and inserted into a payload. The goal is to craft something that will bypass detections and create a pathway into the target through remote access.

Delivery
The payload is sent to the victims associated with that target. Phishing emails are a classic example of using typosquatting to represent a fake version of the target's website to gain user credentials. 

Exploitation
This stage has the payload active/triggered, and the attacker tries to gain control/access.

Installation
