# Curated Penetration Testing Resources

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
  <img align="left" alt="theepiccode's Linkedin" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
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
- [Footprinting and Reconnaissance](#Footprinting-Reconnaissance)
- [Scanning Networks](#Scanning-Networks)
- [Enumeration](#Enumeration)
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

### Footprinting and Reconnaissance
1. [**Autopsy**](https://www.autopsy.com)

   Led by Brian Carrier, whose team builds easy-to-use tools for cyber first responders to intrusions, crime scenes, and war zones. Our team also develops Cyber Triage, fast and affordable incident response software any organization can use to rapidly investigate compromised endpoints.

2. Bulkextractor- https://github.com/simsong/bulk_extractor
    A program that extracts features such as email addresses, credit card numbers, URLs, and other types of information from digital evidence files. It is a useful forensic investigation tool for many tasks such as malware and intrusion investigations, identity investigations and cyber investigations, as well as analyzing imagery and pass-word cracking. 

3. Media Acquistion- https://guymager.sourceforge.io/
   Acquisition refers to the channels that site visits come through to get to your site, or how your visits are acquired. An example of acquisition channels include:
  Organic which refers to visits that came from someone going to your site from organic search results.

4. Toolsley- https://www.toolsley.com
    A privately owned website dedicated to bring you no-hassle tools that are for verifying, hashing, generating and identifying multiple formats of data files.
### Scanning Networks
1. Nmap- https://www.nmap.org
    A free and open source (license) utility for network discovery and security auditing. Many systems and network administrators also find it useful for tasks such as network inventory, managing service upgrade schedules, and monitoring host or service uptime. Nmap uses raw IP packets in novel ways to determine what hosts are available on the network, what services (application name and version) those hosts are offering, what operating systems (and OS versions) they are running, what type of packet filters/firewalls are in use, and dozens of other characteristics. It was designed to rapidly scan large networks, but works fine against single hosts. 

2. Wireshark- https://www.wireshark.org
    The world’s foremost and widely-used network protocol analyzer. It lets you see what’s happening on your network at a microscopic level and is the de facto (and often de jure) standard across many commercial and non-profit enterprises, government agencies, and educational institutions. Wireshark development thrives thanks to the volunteer contributions of networking experts around the globe and is the continuation of a project started by Gerald Combs in 1998.
### Enumeration
1. Network Map (nmap) - https://github.com/nmap/nmap
   A free and open source (license) utility for network discovery and security auditing. Many systems and network administrators also find it useful for tasks such as network inventory, managing service upgrade schedules, and monitoring host or service uptime. Nmap uses raw IP packets in novel ways to determine what hosts are available on the network, what services (application name and version) those hosts are offering, what operating systems (and OS versions) they are running, what type of packet filters/firewalls are in use, and dozens of other characteristics. It was designed to rapidly scan large networks, but works fine against single hosts.
2. Dracnmap - https://github.com/Screetsec/Dracnmap
   An open source program which is using to exploit the network and gathering information with nmap help. Nmap command comes with lots of options that can make the utility more robust and difficult to follow for new users. Hence Dracnmap is designed to perform fast scaning with the utilizing script engine of nmap and nmap can perform various automatic scanning techniques with the advanced commands.
3. Port scanning
   Network port scanner has become an essential part of network admins go-to tools to secure networks with port scanning and network port investigation. Ports act as communication terminals that allow communication between different network components by running various services. A network port scanner enables port scanning your entire network to determine which ports on your network are open and what services are running on them. 
4. Host to IP 
5. Xerosploit - https://github.com/LionSec/xerosploit
   A penetration testing toolkit whose goal is to perform man in the middle attacks for testing purposes. It brings various modules that allow to realise efficient attacks, and also allows to carry out denial of service attacks and port scanning. Powered by bettercap and nmap.
6. RED HAWK (All In One Scanning) - https://github.com/Tuhinshubhra/RED_HAWK
7. ReconSpider(For All Scaning) - https://github.com/bhavsec/reconspider
   Most Advanced Open Source Intelligence (OSINT) Framework for scanning IP Address, Emails, Websites, Organizations and find out information from different sources.
   Recon Spider also combines the capabilities of Wave,Photon and Recon Dog to do a comprehensive enumeration of attack surface.
8. IsItDown (Check Website Down/Up) 
   Check if a website's server is working or not with this simple tool.
9. Infoga - Email OSINT = https://github.com/m4ll0k/Infoga
   A tool gathering email accounts informations (ip,hostname,country,...) from different public source (search engines, pgp key servers and shodan) and check if emails was leaked using haveibeenpwned.com API. Is a really simple tool, but very effective for the early stages of a penetration test or just to know the visibility of your company in the Internet.
10. ReconDog - https://github.com/s0md3v/ReconDog
    Main Features = Wizard + CLA interface, extracts targets from STDIN (piped input) and act upon them. All the information is extracted with APIs, no direct contact is made to the target. 
11. Striker - https://github.com/s0md3v/Striker
    Recon & Vulnerability Scanning Suite
12. SecretFinder (like API & etc) - https://github.com/m4ll0k/SecretFinder
    A python script based on LinkFinder (version for burpsuite here), written to discover sensitive data like apikeys, accesstoken, authorizations, jwt,..etc in JavaScript files. It does so by using jsbeautifier for python in combination with a fairly large regular expression. The regular expressions consists of four small regular expressions. These are responsible for finding and search anything on js files.    
13. Port Scanner - rang3r = https://github.com/bao7uo/PortRanger
    Converts an unordered list of ports on separate lines, which may contain duplicates, to a more condensed, comma-separated list of port ranges without duplicates in ascending numerical order.
15. Breacher - https://github.com/s0md3v/Breacher
    A script to find admin login pages and EAR vulnerabilites.
### System Hacking
1. Setoolkit - https://github.com/trustedsec/social-engineer-toolkit
  An open-source penetration testing framework designed for social engineering. SET has a number of custom attack vectors that allow you to make a believable attack quickly. SET is a product of TrustedSec, LLC – an information security consulting firm located in Cleveland, Ohio.
2. SocialFish - https://github.com/UndeadSec/SocialFish
   A program designed to know social media stats and information related to an account.
3. HiddenEye - https://github.com/Open-Security-Group-OSG/HiddenEyeReborn
   Multi-featured tool for human mistakes exploitation.
4. Evilginx2 - https://github.com/kgretzky/evilginx2
   A man-in-the-middle attack framework used for phishing login credentials along with session cookies, which in turn allows to bypass 2-factor authentication protection.
5. I-See_You(Get Location using phishing attack) - https://github.com/Viralmaniar/I-See-You
   ISeeYou is a Bash and Javascript tool to find the exact location of the users during social engineering or phishing engagements. Using exact location coordinates an attacker can perform preliminary reconnaissance which will help them in performing further targeted attacks.
6. SayCheese (Grab target's Webcam Shots) - https://github.com/hangetzzu/saycheese
   Take webcam shots from target just sending a malicious link
7. QR Code Jacking - https://github.com/cryptedwolf/ohmyqr
   Port Forwarding using Ngrok or Serveo
8. BlackPhish - https://github.com/iinc0gnit0/BlackPhish
   Super lightweight with many features and blazing fast speeds.
### Payload Creation
1. The FatRat - https://github.com/Screetsec/TheFatRat
   An exploiting tool which compiles a malware with famous payload, and then the compiled maware can be executed on Linux , Windows , Mac and Android. TheFatRat Provides An Easy way to create Backdoors and Payload which can bypass most anti-virus.
2. Brutal - https://github.com/Screetsec/Brutal
   A toolkit to quickly create various payload,powershell attack , virus attack and launch listener for a Human Interface Device
3. MSFvenom Payload Creator - https://github.com/g0tmi1k/msfpc
   A wrapper to generate multiple types of payloads, based on users choice. The idea is to be as simple as possible (only requiring one input) to produce their payload.
4. Venom Shellcode Generator -  https://github.com/r00t-3xp10it/venom
   Built to take advantage of apache2 webserver to deliver payloads (LAN)
   using a fake webpage writen in html that takes advantage of <iframe> <meta-http-equiv> or <form> tags to
   be hable to trigger payload downloads, the user just needs to send the link provided to target host.
5. Spycam - https://github.com/thelinuxchoice/spycam
   Another tool for spying through the victim's camera, for capturing pictures and videos. 
6. Mob-Droid - https://github.com/kinghacker0/Mob-Droid
   Helps you to generate metasploit payloads in easy way without typing long commands and save your time.
7. Enigma -  https://github.com/UndeadSec/Enigma
   Multiplatform payload dropper.
### Sniffing
1. OpenVAS - https://www.openvas.org/
   A full-featured vulnerability scanner. Its capabilities include unauthenticated testing, authenticated testing, various high level and low level Internet and industrial protocols, performance tuning for large-scale scans and a powerful internal programming language to implement any type of vulnerability test.
2. Nikto - https://cirt.net/Nikto2
   An Open Source (GPL) web server scanner which performs comprehensive tests against web servers for multiple items, including over 6700 potentially dangerous files/programs, checks for outdated versions of over 1250 servers, and version specific problems on over 270 servers.
3. Wapiti - https://wapiti.sourceforge.io/
   Allows you to audit the security of your websites or web applications. It performs "black-box" scans (it does not study the source code) of the web application by crawling the webpages of the deployed webapp, looking for scripts and forms where it can inject data. Once it gets the list of URLs, forms and their inputs, Wapiti acts like a fuzzer, injecting payloads to see if a script is vulnerable.
4. Metasploit - https://www.metasploit.com/
   Knowledge is power, especially when it’s shared. A collaboration between the open source community and Rapid7, Metasploit helps security teams do more than just verify vulnerabilities, manage security assessments, and improve security awareness; it empowers and arms defenders to always stay one step (or two) ahead of the game.
5. Maltego - https://www.maltego.com/
   An open source intelligence (OSINT) and graphical link analysis tool for gathering and connecting information for investigative tasks.
6. Canvas - https://www.immunityinc.com/products/canvas/
   Makes available hundreds of exploits, an automated exploitation system, and a comprehensive, reliable exploit development framework to penetration testers and security professionals worldwide. 
7. Sn1per - https://github.com/1N3/Sn1per
   An automated scanner that can be used during a penetration test to enumerate and scan for vulnerabilities. Sn1per Professional is Xero Security's premium reporting addon for Professional Penetration Testers, Bug Bounty Researchers and Corporate Security teams to manage large environments and pentest scopes.
8. Lazyrecon - https://github.com/nahamsec/lazyrecon
   A script written in Bash, it is intended to automate some tedious tasks of reconnaissance and information gathering. This tool allows you to gather some information that should help you identify what to do next and where to look.
9. Osmedeus - https://github.com/j3ssie/Osmedeus
   Allows you automated run the collection of awesome tools to reconnaissance and vulnerability scanning against the target.
10. Reconness - https://github.com/reconness/reconness
    With ReconNess you can put all your learning effort only on how to exploit the targets using one specific kind of vulnerability for example and at the same time you are sure that your #recon is good and organized.
11. IronWASP - https://resources.infosecinstitute.com/ironwasp-part-1-2/
    An open source tool used for web application vulnerability testing. It is designed in such a way that users having the right knowledge can create their own scanners using this as a framework. IronWASP is built using Python and Ruby and users having knowledge of them would be able to make full use of the platform. However, IronWASP provides with a lot of features are simple to understand.
    

### Social Engineering
1. Awesome Social Engineering - https://github.com/v2-dev/awesome-social-engineering
   A curated list of awesome social engineering resources, inspired by the awesome-* trend on GitHub.

### Denial Of Service
1. SlowLoris 
   An HTTP Denial of Service attack that affects threaded servers.
2. Asyncrone | Multifunction SYN Flood DDoS Weapon - https://github.com/fatihsnsy/aSYNcrone 
   A C language based, mulltifunction SYN Flood DDoS Weapon. Disable the destination system by sending a SYN packet intensively to the destination.
3. UFOnet - https://github.com/epsylon/ufonet
  A free software, P2P and cryptographic -disruptive toolkit- that allows to perform DoS and DDoS attacks; on the Layer 7 (APP/HTTP) through the exploitation of Open Redirect vectors on third-party websites to act as a botnet and on the Layer3 (Network) abusing the protocol.
4. GoldenEye - https://github.com/jseidl/GoldenEye
   GoldenEye is an HTTP DoS Test Tool.
### Session Hijacking
1. Debinject - https://github.com/UndeadSec/Debinject
   Inject malicious code into .debs
2. Pixload - https://github.com/chinarulezzz/pixload
   Set of tools for hiding backdoors creating/injecting payload into images.

### Evading IDS, Firewalls and Honeypots
1. Bluetooth Honeypot- https://github.com/andrewmichaelsmith/bluepot 
   A Bluetooth Honeypot written in Java, it runs on Linux. The system also allows monitoring of attacks via a graphical user interface that provides graphs, lists, a dashboard and further detailed analysis from log files.
2. Kippo - https://github.com/desaster/kippo
   Kippo is a medium interaction SSH honeypot designed to log brute force attacks and, most importantly, the entire shell interaction performed by the attacker.
3. MushMush - http://mushmush.org/
   A non-profit organization registered in Sankt Pölten, Austria. The foundation is dedicated to the advancement and development of open source software.
4. Formidable Honeypot - https://es.wordpress.org/plugins/formidable-honeypot/
   The «honeypot» technique for SPAM protection is invisible to humans, and tricks robots into filling out an invisible form field. Then, if that invisible field has been filled, the form cannot be submitted. Easy, non-instrusive SPAM protection.
5. Elastic Honey - https://github.com/jordan-wright/elastichoney
   A Simple Elasticsearch Honeypot
6. Honey Thing - https://github.com/omererdem/honeything
   A honeypot for Internet of TR-069 things. It's designed to act as completely a modem/router that has RomPager embedded web server and supports TR-069 (CWMP) protocol.
### Hacking Web Servers

### Hacking Web Applications
1. Awesome Web Hacking - https://github.com/infoslack/awesome-web-hacking
   A collection of tools used for SQL Injections and hacking websites.
### SQL Injection
1. Sqlmap tool - https://github.com/sqlmapproject/sqlmap
   An open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.
2. NoSqlMap - https://github.com/codingo/NoSQLMap
   An open source Python tool designed to audit for as well as automate injection attacks and exploit default configuration weaknesses in NoSQL databases and web applications using NoSQL in order to disclose or clone data from the database.
3. Damn Small SQLi Scanner - https://github.com/stamparm/DSSS
   A fully functional SQL injection vulnerability scanner (supporting GET and POST parameters) written in under 100 lines of code.
4. Explo - https://github.com/telekom-security/explo
   A simple tool to describe web security issues in a human and machine readable format. By defining a request/condition workflow, explo is able to exploit security issues without the need of writing a script. This allows to share complex vulnerabilities in a simple readable and executable format.
5. Blisqy - Exploit Time-based blind-SQL injection - https://github.com/JohnTroony/Blisqy
   A tool to aid Web Security researchers to find Time-based Blind SQL injection on HTTP Headers and also exploitation of the same vulnerability.
6. Leviathan - Wide Range Mass Audit Toolkit - https://github.com/utkusen/leviathan
   A mass audit toolkit which has wide range service discovery, brute force, SQL injection detection and running custom exploit capabilities. It consists open source tools such masscan, ncrack, dsss and gives you the flexibility of using them with a combination.
7. SQLScan - https://github.com/Cvar1984/sqlscan
   Quick web scanner for find an sql inject point on a website.
   
### Hacking Wireless Networks
1. WiFi-Pumpkin https://github.com/P0cL4bs/wifipumpkin3
   A powerful framework for rogue access point attack, written in Python, that allow and offer to security researchers, red teamers and reverse engineers to mount a wireless network to conduct a man-in-the-middle attack.
2. pixiewps - https://github.com/wiire-a/pixiewps
   A tool written in C used to bruteforce offline the WPS PIN exploiting the low or non-existing entropy of some software implementations, the so-called "pixie-dust attack" discovered by Dominique Bongard in summer 2014. It is meant for educational purposes only.
3. Bluetooth Honeypot GUI Framework - https://github.com/andrewmichaelsmith/bluepot
   The system allows monitoring of attacks via a graphical user interface that provides graphs, lists, a dashboard and further detailed analysis from log files.
4. Fluxion - https://github.com/thehackingsage/Fluxion
   It is a remake by Mr. SAGE with less bugs and more functionality. It's compatible with the latest release of Kali (rolling). 
5. Wifiphisher - https://github.com/wifiphisher/wifiphisher
   A rogue Access Point framework for conducting red team engagements or Wi-Fi security testing. Using Wifiphisher, penetration testers can easily achieve a man-in-the-middle position against wireless clients by performing targeted Wi-Fi association attacks.
6. Wifite - https://github.com/derv82/wifite2
   Designed to use all known methods for retrieving the password of a wireless access point (router). 
7. EvilTwin - https://github.com/Z4nzu/fakeap
   A script to perform Evil Twin Attack, by getting credentials using a Fake page and Fake Access Point
8. Fastssh - https://github.com/Z4nzu/fastssh
   A Shell Script to perform multi-threaded scan and brute force attack against SSH protocol using the most commonly credentials.

### Hacking Mobile Platforms
1. Keydroid - https://github.com/F4dl0/keydroid
   Android Keylogger + Reverse Shell.
2. MySMS - https://github.com/papusingh2sms/mysms
   Script that generates an Android App to hack SMS through WAN
3. Lockphish (Grab target LOCK PIN) - https://github.com/JasonJerry/lockphish
   The first tool (05/13/2020) for phishing attacks on the lock screen, designed to grab Windows credentials, Android PIN and iPhone Passcode using a https link.
4. DroidCam (Capture Image) - https://github.com/kinghacker0/WishFish
   Using WishFish tool you can generate different phishing links of wishing or custom sites which can grab victim's front camera pictures and also gives you information about target's IP Address. 
5. EvilApp (Hijack Session) - https://github.com/Ro9ueAdmin/EvilApp
   Script to generate Android App that can hijack autenticated sessions in cookies.
6. HatCloud(Bypass CloudFlare for IP) - https://github.com/HatBashBR/HatCloud
   It makes bypass in CloudFlare for discover real IP. This can be useful if you need test your server and website. Testing your protection against Ddos (Denial of Service) or Dos. CloudFlare is services and distributed domain name server services, sitting between the visitor and the Cloudflare user's hosting provider, acting as a reverse proxy for websites. Your network protects, speeds up and improves availability for a website or the mobile application with a DNS change.
### IoT Hacking
1. Vehicle Security - https://github.com/jaredthecoder/awesome-vehicle-security
  A curated list of awesome resources, books, hardware, software, applications, people to follow, and more cool stuff about vehicle security, car hacking, and tinkering with the functionality of your car.
  
### Cloud Computing

### Cryptography
1. Awesome Cryptography - https://github.com/sobolevn/awesome-cryptography
   A curated list of cryptography resources and links.
