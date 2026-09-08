# Kali Linux Penetration Testing Lab (VirtualBox)

📌 **Project Overview**
This repo documents a personal cybersecurity and penetration-testing lab I built using VirtualBox and Kali Linux on a Windows host.
The goal was to create a controlled, isolated environment where I could safely and repeatedly practice network scanning, reconnaissance, vulnerability assessment, and other security-testing skills.
The lab runs on a private NAT Network, so I can add target machines later without any risk to my host system or any external network.

🎯 **Objectives**
What I set out to do in this project:
- Install and configure VirtualBox on Windows
- Import Kali Linux as a virtual machine
- Create a private NAT Network for the lab
- Connect Kali Linux to that network
- Assign Kali a consistent IP address
- Verify network connectivity and DNS resolution from inside the VM
- Take a clean snapshot for quick recovery
- Document the full setup process here
- Prepare the environment to add target machines for future testing

🛡️ **Purpose of the Lab**
This lab gives me an isolated, controlled space to learn and practice cybersecurity skills, including:
- Network reconnaissance
- Port scanning
- Vulnerability assessment
- Packet analysis
- Web security testing
- Exploitation practice (against machines I set up myself)
- General security-tool experimentation

✅ **Current Status**
- [x] VirtualBox installed and configured
- [x] Kali Linux VM imported and running
- [x] Private NAT Network created
- [x] Kali VM connected with a consistent IP
- [x] Connectivity and DNS resolution verified
- [x] Clean snapshot taken
- [ ] Target VM (e.g. Metasploitable) — planned next

🖥️ **Environment**
- **Host OS:** Windows
- **Hypervisor:** VirtualBox
- **Guest OS:** Kali Linux
- **Network:** Private NAT Network (isolated)

📷 **Screenshots**
*Virtualbox*
The step is done by downloading it from the official website and then installing it in the window host
![image alt](https://github.com/netcater/NETWORKWALKS-B083-WK1-PM1-CYBERSECURITY-LABs-SETUP/blob/2d1dc52f5f64a81da24e181ebebe8786c6cbf59b/kali1.PNG)

*Importing Kali Linux*
Step is done by downloading the official kali linux vm from the web browser extracting it and then importing it to the virtual box.
![image alt](https://github.com/netcater/NETWORKWALKS-B083-WK1-PM1-CYBERSECURITY-LABs-SETUP/blob/04c596f7a632083cf1f131119310e2225fceba37/vm1.PNG)

*NAT Network configaration*
The step is aimed to 
-Isolation from your host and the outside world
-Allowing outbound internet access
-Leting multiple VMs talk to each other privately
-Enhancing predictable, consistent addressing
![image alt](https://github.com/netcater/NETWORKWALKS-B083-WK1-PM1-CYBERSECURITY-LABs-SETUP/blob/7e7a7aa0a435bf4df6b6d63efc20fac3ea1d31fa/netsetting.PNG)

 *Kali linux IP configuration*
 The aim is to ensure that the 
 **IP Address** is 10.0.0.2
 **DNS** is 8.8.8.8
 **Gateway** is 10.0.0.1
 ![image alt](https://github.com/netcater/NETWORKWALKS-B083-WK1-PM1-CYBERSECURITY-LABs-SETUP/blob/0bcf8a9104f1d6807bf124d94bb886ac66a6eafb/net4.PNG)

 🔗 **Tools & Resources**
-7-Zip: https://7-zip.org/download.html
-VirtualBox: https://virtualbox.org/wiki/Downloads
-Kali Linux: https://kali.org/get-kali


🔜 **Next Steps**
-Structured information gathering and target discovery
- Add a deliberately vulnerable target VM (Metasploitable2 or DVWA) to the network
- Using different tools to perform real hacking
- Network and service discovery with result analysis
- Run initial reconnaissance and port scans (`nmap`) against it
- Document results in this repo as I go

⚠️ **Important:** This lab is used only for machines I own or have set up myself inside this isolated network. It is never used against systems I don't own or don't have explicit permission to test.

---
Built by Shomari Ismail Kimela 
-Computer Science and Engineering student
-NETWORKWALKS cybersecurity intern. 
