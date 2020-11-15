# Curated Cyber Sec Resources

![Banner](https://github.com/theepiccode/Curated-CyberSec-Resources/blob/main/Banner.png)
<p align="left"> <img src="https://komarev.com/ghpvc/?username=theepiccode&label=Views&color=blue&style=plastic" alt="theepiccode" /> </p>
<a href = "https://invite.theepiccode.com" align = "left">
<img src = "https://img.shields.io/badge/Discord-Join%20the%20Server-blue" /> 
</a>
<br>
<br>
<a href="https://twitter.com/theepiccode1">
  <img align="left" alt="theepiccode's Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="https://www.linkedin.com/company/theepiccode/">
  <img align="left" alt="theepiccode's Linkdein" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
<a href="https://github.com/theepiccode">
  <img align="left" alt="theepiccode's Github" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
</a>
<a href="https://www.instagram.com/theepiccode/">
  <img align="left" alt="theepiccode's Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<a href="https://www.youtube.com/theepiccode">
  <img align="left" alt="theepiccode's Youtube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />
</a>
<br>
<br>

## Table of Contents

- [Hacking Introduction and Building Lab](#Hacking-Introduction)
- [Footprinting and Reconnaissance](#Footprinting-Reconnaissance)
- [Scanning Networks](#Scanning-Networks)
- [Enumeration](#Enumeration)
- [Voluntarily Analysis](#Voluntarily-Analysis)
- [System Hacking](#System-Hacking)
- [Malware Threats](#Malware-Threats)
- [Sniffing](#Sniffing)
- [Social Engineering](#Social-Engineering)
- [Denial Of Service](#Denial-Of-Service)
- [Session Hijacking](#Session-Hijacking)
- [Evading IDS, Firewalls and Honeypots](#Evading-IDS)
- [Hacking Web Servers](#Hacking-Web-Servers)
- [Hacking Web Applications](#Hacking-Web-Applications)
- [SQL Injection](#SQL-Injection)
- [Hacking Wireless Networks](#Hacking-Wireless-Networks)
- [Hacking Mobile Platforms](#Hacking-Mobile-Platforms)
- [IoT Hacking](#IoT-Hacking)
- [Cloud Computing](#Cloud-Computing)
- [Cryptography](#Cryptography)
- [External Links/Resources](#External-Links-Resources)

### Hacking Introduction and Building Lab
Ethical hacking is a skill that is learned over time. It requires practice and patience to get to a decent skill level in this field. Having a lab setup handy can help you a lot in your learning. A lab lets you practice your skills in a controlled environment, reducing the risks that arise from practicing on real systems. Having your virtual lab will help you in many ways:

You can practice anytime as per your convenience.
You don’t have to put your data under the dangers of getting wiped because of malware infection.
You are also saved from legal troubles that may result from testing on a real website that you do not own.
You get the freedom to experiment and tweak around (mostly impossible with online labs).
The requirements for setting up the lab are hardware and software tools. Let’s go through the hardware requirements first.

1. Hardware Requirements:
A laptop or a desktop with as much RAM and processor power you can arrange.
A large HDD or SSD to store your tools and other important files.
A host OS for your computer system. It can be Windows, Linux( any family, any flavor) or Mac OS depending on your choice.
Latest security patches must be installed on your guest OS before you start.
A WiFi adapter that supports monitor mode. (Optional)

2. Software Requirements:

Virtual Machine Player or Hypervisor: This will be used to host all the guest operating systems, vulnerable virtual machines, and test servers. There are many free and paid options for hypervisors provided by many vendors. For example, VMware has VMWare workstation, Oracle has Oracle VirtualBox and Microsoft has HyperV. You can choose any of these depending on your choice and budget.

Guest Operating Systems: Guest operating systems will include unpatched versions of Windows and Linux. These will be installed to test for zero-days and other vulnerabilities for which patches, as well as exploits, have been released.

Vulnerable VMs: Vulnerable Virtual Machines are developed intentionally for being highly vulnerable. Most of the VMs are parts of hacking events and are released later online. These VMs are usually CTFs with hidden strings that are to be found after compromising (pwning) the VM. Some popular vulnerable VMs are Metasploitable, OWASP broken web application, DVWA(Damn Vulnerable Web Application), BadStore, De-Ice, and Multidae, etc.

3. Essential Tools:
Once you have found and installed your favorite vulnerable assets, it is now time to get the tools required for pwning them. Install these tools on your computer to get started.

__*Metasploit Framework (MSF)*__: An open-source version of the Metasploit tool is used extensively for exploiting known vulnerabilities in systems and software. The exploit list is updates regularly with exploits of most recent findings that went public. Metasploit can be downloaded from: here.

__*WireShark*__: It is a tool used by network administrators but you can use it to supplement your hacking tools arsenal. For you as a hacker(ethical, of course) this tool will help in network pentesting by the same basic feature of network monitoring :it can help you harvest sensitive data like plaintext passwords over unencrypted connections(http, telnet), analyze malware behavior by figuring out the endpoints it tries to connect, and many more. We have done an introductory article on Wireshark which you can check out here

__*Nmap*__: One tool to rule ’em all, it is used by almost every penetration tester. It is a port scanner with a set of additional utilities like OS detection and network mapping(nmap stands for “network mapper” ). It can be automated by writing scripts in NSE(nmap scripting environment). Port scans are used to enumerate services and applications on the target. These enumeration data can be really useful in some cases for pwning the target. Get it here .

__*John The Ripper*__: It is a free and open-source password cracking tool which is highly popular among penetration testers. Popularity is the reason why it is available on fifteen platforms. The tools were initially designed for cracking UNIX password hashes. However, the latest stable release from May 2019 supports Windows NTLM, Kerberos and hundreds of other hashes.
Burpsuite or OWASP ZAP: Both are great all in one tool for penetration testing web applications. Learning about hacking web applications is crucial for an aspiring (ethical) hacker since most of the services are provided online. These two tool-sets contain all the tools you will need for hacking (ethically) into a web application.

__*Kali Linux*__: It is an operating system developed primarily for white hat hackers and penetration testers. This OS has a wide array of tools for almost every task before, during and after a penetration testing session. It contains all the tools mentioned above (No need for installing them manually). Kali Linux can be downloaded from here. 
### Footprinting and Reconnaissance
Before a penetration test even begins, penetration testers spend time with their clients working out the scope, rules, and goals of the test. The penetration testers may break in using any means necessary, from using information found in the dumpster, to locating web application security holes, to posing as the cable guy. After pre-engagement activities, penetration testers begin gathering information about their targets.

**Objective**
The objective of the lab is to extract information concerning the target organization that includes, but is not limited to:

1. Type of firewall implemented, either hardware or software or a combination of both
2. IP address range associated with the target
3. Purpose of the organization and why it exists
4. How big is the organization? What class is its assigned IP Block?
5. Does the organization freely provide information about the type of operating systems employed and network topology in use?
6. Does the organization allow wireless devices to connect to wired networks?
7. Type of remote access used, either SSH or VPN
8. Is help sought from IT positions that give information on network services provided by the organization?
9. Identify organization’s users who can disclose their personal information that can be used for social engineering and assume such possible usernames

**Scenario**
A penetration test begins before penetration testers have even made contact with the victims' systems. Rather than blindly throwing out exploits and praying that one of them returns a shell, a penetration tester meticulously studies the environment for potential weaknesses and their mitigating factors. By the time a penetration tester runs an exploit, he or she is nearly certain that it will be successful. Since failed exploits can in some cases cause a crash or even damage a victim's system, or at the very least make the victim un-exploitable in the future, penetration testers won't get the best results or deliver the most thorough report to their clients if they blindly turn an automated exploit machine on the victim network with no preparation.

### Scanning Networks

*Pre-connection attacks*: in this subsection you'll learn a number of attacks that can be executed without connecting to the target network, and without the need to know the network password; you'll learn how to gather information about the networks around you, discover connected devices, and control connections (deny/allow devices from connecting to networks).

*Gaining Access*: Now that you gathered information about the networks around you, in this subsection you will learn how to crack the key and get the password to your target network weather it uses WEP, WPA or even WPA2.

Post Connection attacks: Now that you have the key, you can connect to the target network, in this subsection you will learn a number of powerful techniques that allow you to gather comprehensive information about the connected devices, see anything they do on the internet (such as login information, passwords, visited urls, images, videos ....etc), redirect requests, inject evil code in loaded pages and much more! All of these attacks work against both wireless and wired networks. You will also learn how to create a fake WiFi network, attract users to connect to it and use all of the above techniques against the connected clients.

**Gaining Access** - In this section you will learn two main approaches to gain full control or hack computer systems:

*Server Side Attacks*:  In this subsection you will learn how to gain full access to computer systems without user interaction. You will learn how to gather useful information about a target computer system such as its operating system, open ports, installed services, then use this information to discover weaknesses and vulnerabilities and exploit them to gain full control over the target. Finally you will learn how to automatically scan servers for vulnerabilities and generate different types of reports with your discoveries.

*Client Side Attacks* - If the target system does not contain any weaknesses then the only way to hack it is by interacting with the users, in this subsection you'll learn how to get the target user to install a backdoor on their system without even realising, this is done by hijacking software updates or backdoornig downloadeds on the fly. This subsection also teaches you how to use social engineering to hack into secure systems, so you'll learn how to gather comprehensive information about system users such as their social accounts, friends, their mails.....etc, you'll learn how to create trojans by backdooring normal files (such as an image or a pdf) and use the gathered information to spoof emails so they appear as if they're sent from the target's friend, boss or any email account they're likely to interact with, to social engineer them into running your torjan.

### Enumeration

### Voluntarily Analysis

### System Hacking

### Malware Threats

### Sniffing

### Social Engineering

### Denial Of Service

### Session Hijacking

### Evading IDS, Firewalls and Honeypots

### Hacking Web Servers

### Hacking Web Applications

### SQL Injection

### Hacking Wireless Networks

### Hacking Mobile Platforms

### IoT Hacking

### Cloud Computing

### Cryptography

### External-Links-Resources
