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
```
/screenshots
  ├── nat-network-config.png
  ├── kali-ip-config.png
  └── snapshot-list.png
```

🔜 **Next Steps**
- Add a deliberately vulnerable target VM (Metasploitable2 or DVWA) to the network
- Run initial reconnaissance and port scans (`nmap`) against it
- Document results in this repo as I go

⚠️ **Important:** This lab is used only for machines I own or have set up myself inside this isolated network. It is never used against systems I don't own or don't have explicit permission to test.

---
Built by Shomari Ismail Kimela — Computer Science and Engineering student
