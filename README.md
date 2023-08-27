# Window_Hacking_Practice
# Objective - Get the access of windows 7 with exploitation of smb-vuln-ms17-010.nse or smbvuln-ms17-054.nse
# SMB-vuln-ms17-010.nse (EternalBlue)
This vulnerability allows remote attackers to execute arbitrary code on a target system without user interaction. In essence, it can lead to the complete compromise of a Windows machine if not patched.
# smbvuln-ms17-054.nse (ShadowBrokers Exploits)
The specific impact depends on the individual exploit being used, but generally, these exploits can allow attackers to gain unauthorized access to systems, execute malicious code, and potentially move laterally within a network.
# Requirement To Perform Attack
**1.Vulnerable System:** The target system must be running a vulnerable version of the Windows operating system with SMB version 1 (SMBv1) enabled. Specifically, this vulnerability affects Windows 7 and Windows Server 2008 R2 systems, although there have been variations of this exploit for other versions.

**2.Network Access:** The attacker needs network access to the target machine over the SMB protocol. This can be achieved over a local network or, in some cases, over the internet if the vulnerable system is exposed.

**3.EternalBlue Exploit:** The attacker typically uses a tool or script that leverages the EternalBlue exploit to send specially crafted packets to the target system's SMB service. This exploit takes advantage of the vulnerability in SMBv1 to execute malicious code remotely.

**3.Payload:** Once the attacker gains control of the target system, they may deploy a malicious payload, which can be malware, ransomware, or any other malicious software, to achieve their specific objectives, such as data theft, system control, or encryption for ransom.
# Hands-On
**Step1-** First we start are try hack me Blue Machine and get ip address of machine and then in our linux system check the vulnerabilities which we want to exploit by using nmap and ip address of our blue machine is 10.10.127.251

![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/a62ea2ff-0f97-46e7-946f-eea62998d88d)
![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/d03b80d1-4ba5-44b2-9463-bef753c383bc)

**Step2-** Now we can check the permissions and port number of the machine by scanning with nmap command

![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/37840c8b-2bd5-444e-af01-5395b29df6ad)

**Step3-** Now we can check the tun0 ip address for setting the payload and Rhosts and Lhosts

![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/b782eb11-cc48-4ca6-9555-248d7bb112b9)
![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/18e61032-2488-4de8-a617-72b1cacc6457)
![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/fe5c64b1-c0f7-4bb8-83ff-34f4ef78f7c6)
![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/7821a9a0-a16a-4e3f-8318-db24999bed23)
![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/0b2f8144-0085-4426-9b24-af49630c75b0)
![image](https://github.com/bhavish95/Window_Hacking_Practice/assets/111994995/732e4c99-7164-41bd-bb29-95129bb507c9)


