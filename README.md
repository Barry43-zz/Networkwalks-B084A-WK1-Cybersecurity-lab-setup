# Networkwalks-B084A-WK1-Cybersecurity-lab-setup
A virtual cybersecurity lab built with Kali Linux and Oracle Virtualbox for learning ethical hacking, network security, penetration testing, and cybersecurity fundamentals
# 🔐 Kali Linux Cybersecurity Lab



### Building a Virtual Cybersecurity Environment Using Kali Linux & Oracle VirtualBox



![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red)

![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-blue)

![Virtualization](https://img.shields.io/badge/Virtualization-VirtualBox-green)

![Status](https://img.shields.io/badge/Project-Completed-success)



---



## 📌 Project Overview



This project documents the creation and configuration of

a virtual cybersecurity laboratory using Kali Linux and

Oracle VirtualBox.



The main goal is to establish a controlled virtual

environment for learning cybersecurity concepts,

understanding network security, and practicing ethical

hacking techniques.



The laboratory provides a foundation for conducting

authorized security experiments, network analysis,

penetration testing exercises, and vulnerability

assessment in an isolated environment.



This project also serves as a practical demonstration

of my hands-on learning journey in cybersecurity.



---



## 🎯 Project Objectives



The primary objectives of this project include:



- Installing and configuring Oracle VirtualBox.

- Setting up Kali Linux as a virtual machine.
  
- Create a private **NAT Network** for the cybersecurity lab.
 
- Understanding virtual networking.

- Configuring network connectivity.

- Exploring essential Linux commands.

- Understanding basic cybersecurity tools.

- Preparing an environment for ethical hacking practice.

- Documenting the entire laboratory setup process.



---



## 🛠️ Tools & Technologies



| Purpose |

- Network reconnaissance
- Port scanning
- Vulnerability assessment
- Packet analysis
- Web security testing
- Exploitation practice
- Security-tool experimentation




---



## 🏗️ Lab Architecture



The laboratory consists of a host operating system

running Oracle VirtualBox, with Kali Linux deployed

as a virtual machine.



### Environment Architecture



Host Machine

|

|

Oracle VirtualBox

|

|

Kali Linux

|

|

Virtual Network

|

|

Cybersecurity Lab



Additional virtual machines can be introduced later

to simulate attacker and target environments.



---



## ⚙️ System Configuration



The following table documents the laboratory

configuration.



| Component | Configuration |

|-----------|---------------|

| Host Operating System | [Windows] |

| Virtualization Software | Oracle VirtualBox |

| Virtual Machine OS | Kali Linux |

| Allocated RAM | [Your RAM] |

| CPU Cores | [Your CPU Cores] |

| Virtual Disk | [Your Disk Size] |

| Network Adapter | [NAT / NAT Network / Host-Only] |



---



## 🚀 Lab Setup Procedure



### Step 1: Install Oracle VirtualBox

<img width="1915" height="999" alt="image" src="https://github.com/user-attachments/assets/003771ad-03af-45a9-9312-2bd1b27a902f" />


Download and install Oracle VirtualBox on the

host machine.



VirtualBox provides the virtualization environment

required to run Kali Linux.



### Step 2: Download Kali Linux

<img width="1916" height="959" alt="image" src="https://github.com/user-attachments/assets/e64d9799-5c7e-4f23-aa67-ff055337e8b8" />


Download the official Kali Linux virtual machine

image from the Kali Linux website.



### Step 3: Import Kali Linux into VirtualBox


Import the downloaded Kali Linux virtual machine

into Oracle VirtualBox.



### Step 4: Configure Network Settings



Configure the virtual machine network adapter

according to the laboratory requirements.



Network configuration:



Adapter Type: [INTEL]

Network: [NAT Network]

IP Address: [10.0.0.2]

Gateway: [10.0.0.1]



### Step 5: Start Kali Linux



Start the virtual machine and complete the initial

system configuration.



Verify that Kali Linux boots successfully and that

the desktop environment is accessible.


## Step 6. Configure the Kali Linux Network

The Kali Linux network configuration was checked and configured with a consistent IPv4 address.

Example configuration:

```text
IP Address: 10.0.0.2
Subnet Mask: 255.255.255.0
Gateway: 10.0.0.1
DNS: 8.8.8.8
```




### Step 6: Verify Network Connectivity



Check the assigned IP address:



ip addr



Check network connectivity:



ping -c 4 8.8.8.8



Check DNS resolution:



nslookup google.com



### Step 8: Create a Virtual Machine Snapshot



Create a snapshot of the configured Kali Linux

environment.



This provides a recovery point before conducting

future cybersecurity experiments.



---








---



## 📸 Project Screenshots



Screenshots documenting the laboratory setup

are available below.



### 1. VirtualBox Environment



![VirtualBox](screenshots/virtualbox-dashboard.png)



### 2. Kali Linux Desktop



![Kali Linux](screenshots/kali-linux-desktop.png)



### 3. Kali Linux Terminal



![Kali Terminal](screenshots/kali-terminal.png)



### 4. Network Configuration



![Network Configuration](screenshots/network-configuration.png)



### 5. Cybersecurity Lab Environment



![Lab Environment](screenshots/lab-environment.png)



---



## 🧠 Skills & Knowledge Gained



Through this project, I developed practical

knowledge of:



- Virtualization and virtual machine management.

- Kali Linux installation and configuration.

- IP addressing and network configuration.

- Network connectivity troubleshooting.

- Cybersecurity laboratory design.

- Technical documentation.



---



---



## 🛡️ Security & Ethical Considerations



This laboratory is designed strictly for educational

purposes and authorized cybersecurity testing.



All security experiments must be conducted against

systems that I own or have explicit permission to test.



The laboratory should be properly isolated to prevent

accidental testing against unauthorized networks

or external systems.



---



## 📚 Learning Resources



- Kali Linux: https://www.kali.org/

- Oracle VirtualBox: https://www.virtualbox.org/

- Wireshark: https://www.wireshark.org/



---



## 👨‍💻 Author



**[Vincent Goodluck B.]**



Aspiring Cybersecurity Professional



LinkedIn: [https://www.linkedin.com/public-profile/settings/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_self_edit_contact_info%3BjZK2nhFhS9%2BKlX2WbWkm1A%3D%3D]



---



## ⭐ Acknowledgment



This project is part of my continuous learning journey

in cybersecurity, ethical hacking, and network security.



I believe in learning through practical experience,

documenting my progress, and continuously improving

my technical skills.



---



**If you find this project useful, consider giving

the repository a ⭐ star!**



#CyberSecurity #KaliLinux #VirtualBox

#EthicalHacking #NetworkSecurity #PenetrationTesting #Networkwalks
