# Computer Fundamentals Lab: From Hardware to Cloud

## 1. Project Overview
This project explains the core computer fundamentals covered in TryHackMe's Computer Fundamentals module. The overall goal is to show how computer hardware, operating systems, client-server communication, virtualization, and cloud computing work together to build the devices we all know and love today.

## 2. Computer System Overview
A computer system is made of two parts: hardware and software.

Hardware is the physical part of the computer. Software is the programs and operating systems that run on and communicate with the hardware.

Basic Flow: [Hardware] -> [Operating System] -> [Applications] -> [Network / Internet] -> [Servers / Cloud Services]

## 3. Main Hardware Components
| Component | Purpose |
|---|---|
| CPU | Processes instructions/logic and runs programs |
| RAM | Temporarily stores active data |
| Storage (HDD/SSD) | Saves files, applications, and the operating system |
| Motherboard | Connects all major components |
| GPU | Handles graphics and parallel processing |
| Network Interface | Connects the computer to a network |
| PSU | Supplies electricity to all system components |

## 4. Operating System Role
The operating system manages the computer's hardware and software.

Examples:
- Windows
- macOS
- Linux
- Android
- iOS

The operating system handles various tasks, including:
- Processes
- Memory
- Files
- Devices
- User accounts
- Network connections

## 5. Computer Types
| Type | Example | Use |
|---|---|---|
| Desktop | Gaming PC, office PC | Personal or work computing |
| Laptop | MacBook, Windows laptop | Portable computing |
| Server | Web server, database server | Provides services to users |
| Mobile Device | Phone, tablet | Portable apps and communication |
| IoT Device | Smart camera, smart thermostat | Specialized connected device |
| Embedded System | Router, car system, appliance chip | Runs a specific task |

## 6. Client-Server Model
The client-server model explains how computers communicate with each other. A client requests a service. A server provides that service.

Example:
1. A laptop opens a website.
2. The browser sends a request.
3. The web server receives the request.
4. The server sends back the webpage.
5. The browser displays the page.

| Role | Meaning |
|---|---|
| Client | Requests data or services |
| Server | Provides data or services |

## 7. Virtualization Basics
Virtualization allows one physical computer to run multiple virtual machines. Virtual machines act like separate computers, but share the same physical hardware using the host machine.

Benefits:
- Better hardware age
- Safe testing environments
- Easier backup and recovery
- Isolated systems
- Useful cybersecurity labs

Example:
[Physical Computer] -> [Hypervisor] -> [Virtual Machine 1: Linux] AND [Virtual Machine 2: Windows] AND [Virtual Machine 3: Security Lab]

## 8. Cloud Computing Basics
Cloud computing allows users and businesses to access computing resources over the internet. Instead of buying and managing physical servers, companies can rent servers, storage, databases, and applications from cloud providers. There are different deployment types (public/private) and cloud service models (such as SaaS) that can be provided.

Example Cloud Providers:
- AWS
- Microsoft Azure
- Google Cloud

Cloud services can provide:
- Virtual machines
- Storage
- Databases
- Websites
- Security Tools
- Backup

## 9. Virtualization vs Cloud Computing
| Concept | Simple Meaning |
|---|---|
| Virtualization | Running multiple virtual computers on one physical machine |
| Cloud Computing | Renting computing resources over the internet |
| Hypervisor | Software that creates and manages virtual machines |
| Virtual Machine | A software-based computer running inside another computer |

## 10. Cybersecurity Reflection
Computer fundamentals are invaluable for cybersecurity because attackers and defenders both need to understand how systems work. 

Security professionals use this knowledge to:
- Secure operating systems
- Analyze malware behavior
- Monitor servers
- Protect cloud environments
- Build safe virtual labs
- Investigate compromised machines

## 11. What I Learned
From this module, I learned that computers are built in many layers. Hardware supports the operating system, the operating system runs the applications, the applications connect to networks, and servers/cloud systems provide services to these applications. The biggest takeaway I got from this is that cybersecurity depends heavily on understanding the systems being protected before they can actually be secured.

## References
- TryHackMe. "Introduction to Cyber Security." TryHackMe, [https://tryhackme.com/](https://tryhackme.com/module/computer-fundamentals)

## Disclaimer
This project is for educational purposes only. It summarizes concepts learned through TryHackMe and does not include walkthrough answers, flags, or private room solutions.
