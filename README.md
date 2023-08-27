# Window_Hacking_Practice
# Objective
Get the access of windows 7 with exploitation of smb-vuln-ms17-010.nse or smbvuln-ms17-054.nse
# SMB-vuln-ms17-010.nse (EternalBlue)
This vulnerability allows remote attackers to execute arbitrary code on a target system without user interaction. In essence, it can lead to the complete compromise of a Windows machine if not patched.
# smbvuln-ms17-054.nse (ShadowBrokers Exploits)
The specific impact depends on the individual exploit being used, but generally, these exploits can allow attackers to gain unauthorized access to systems, execute malicious code, and potentially move laterally within a network.
# Requirement To Perform Attack
# Vulnerable System 
The target system must be running a vulnerable version of the Windows operating system with SMB version 1 (SMBv1) enabled. Specifically, this vulnerability affects Windows 7 and Windows Server 2008 R2 systems, although there have been variations of this exploit for other versions
# Network Access
The attacker needs network access to the target machine over the SMB protocol. This can be achieved over a local network or, in some cases, over the internet if the vulnerable system is exposed.
# EternalBlue Exploit
The attacker typically uses a tool or script that leverages the EternalBlue exploit to send specially crafted packets to the target system's SMB service. This exploit takes advantage of the vulnerability in SMBv1 to execute malicious code remotely.
# Payload
Once the attacker gains control of the target system, they may deploy a malicious payload, which can be malware, ransomware, or any other malicious software, to achieve their specific objectives, such as data theft, system control, or encryption for ransom.

