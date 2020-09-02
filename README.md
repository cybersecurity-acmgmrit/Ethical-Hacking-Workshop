# Ethical-Hacking-Workshop

This repository consists of information required to start career in cyber Security


# Ethical Hacking Workshop
***

## Topics to be covered
> * What is CyberSecurity?
> * Why CyberSecurity?
> * CyberAttacks
>> * Malware
>>> * Spyware
>>> * Ransomware
>>> * virus, trojan, worms
>> * Phishing
>> * Man-in-the-Middle-Attack (EavesDropping Attack) (MitM)
>> * Denial-of-Service(DoS) and Distributed Denial-of-Service(DDoS)
>> * Code Injections(SQL, NoSQL, OS, )
>> * Cross-site Scripting(XSS)
>> * Zero-Day Attacks
> * Getting Started (Skills required)
>> * Programming knowledge
>> * Computer Networking
>> * Operating System
>> * Exploitation Techniques
>> * Linux Distributions(kali-linux)
>> * Cryptography
>> * Reverse Engineering
>> * Taking advantage of Existing tools
> * Penetration Testing
>> * Phases of Ethical Hacking
>> * OWASP TOP10
>> * Tools
>> * Guides
>>> * OWASP Web Security Testing Guide<br>
      (https://owasp.org/www-project-web-security-testing-guide/)
>>> * Testing Guide<br>
      (https://owasp.org/www-pdf-archive/OTGv4.pdf)
>>> * Testing Guide checklist<br>
      (https://github.com/tanprathan/OWASP-Testing-Checklist/raw/master/OWASPv4_Check(
>> * Attacks
>>> * https://owasp.org/www-community/attacks/
> * courses and Certifications
> * Various Job roles
> * Add-ons
>> * Bug-Bounty
>>> * bugcrowd
>>> * hackerone
>>> * BountyFactory
>>> * BugBountyjp
>> * CTF's

### What is cyber Security?
> Practice of protecting and Recovering Systems, Networks, programs from Digital attacks

### Why Cyber Security?
> * Information is wealth, so protection of information is necessary
> * Data breaches compromises the user credentials and company's personal data
> * Here is a list of data breaches in 2020
>> * https://www.identityforce.com/blog/2020-data-breaches

## Common types of Cyber Attacks


> ### Malware ( Malicious Software )
>> Malwares enters into a network or system via vulnerability or by social engineering attacks like clicking unknown links that downloads malware into our system
>> * Spyware
>>> * Gathers Information and sends to the hacker without the victims knowledge
>> * Ransomware
>>> * Name itself suggests that it is a type of malware which encrypts victims data and made inaccessible to the victim. Attacker demands some ransome inorder to decrypt the data
>> * Virus and
>>> * Modifies the existing code so that system working fails
>>> * As it name suggests it replicates itself and attacks other devices
>> * Worms
>>> * Worms are also similar to viruses attacking on a network
> ### Phishing
>> * Phishing is the practice of sending fraudulent communications that appear to come from a reputable source, usually through email.
>> * The goal is to steal sensitive data like credit card and login information or to install malware on the victim’s machine.
>> * Phishing is an increasingly common cyberthreat
> ### Man-in-the-Middle-Attack (MitM) (Eavesdropping Attack)
>> * In MitM attacks attacker pretends himself as the original source or destination but serves in between you and the server so that he can capture all your traffic.
>> * Common MitM Attacks
>>> * On unsecure public Wi-Fi, attackers can insert themselves between a visitor’s device and the network. Without knowing, the visitor passes all information through the attacker.
>>> * Once malware has breached a device, an attacker can install a software to process all of the victim’s information.
> ### Denial-of-service-attack
>> * A denial-of-service attack floods systems, servers, or networks with traffic to exhaust resources and bandwidth
>> * As a result, the system is unable to fulfill legitimate requests.
>> * Attackers can also use multiple compromised devices to launch this attack. This is known as a distributed-denial-of-service (DDoS) attack.
> ### Code Injections
>> * SQL Injection
>>> * malicious SQL statements are inserted into an entry field for execution
>> * Cross-site-Scripting (XSS)
> ### Zero-Day-Attack
>> * It is an attack that launched on the same as vulnerability founds means
>> * When a vulnerability is found in a software attacking the software and it's users before releasing a patch for it
>> * Thatswhy we have to use upto date softwares and apps


## Skills Required for an Ethical hacker


> * Programming knowledge
> * Computer Networking
> * Operating System
> * Exploitation Techniques
> * Linux Distributions(kali-linux)

> * Cryptography
> * Reverse Engineering
> * Taking advantage of Existing tools


### Programming Knowledge

> 0. What is a programming language?
>> It is a language used to talk with computers<br>
    (As we have many languages to speak, similarly computers also have many programming languages)

> 1. Actually there is know soln for this problem<br>
    (As an ethical hacker one must have basic understanding of all programming languages)
> 2. One should able to understand the syntax and logic behind the existing code
> 3. For building custom softwares and tools of your own
> 4. Attempting to reverse engineer code and finding Exploits in code
> 5. For solving a problem sometimes we need programming knowledge
> 6. Few Programming languages are
>>   * C/C++
>>   * Python
>>   * HTML
>>   * JavaScript
>>   * PHP
>>   * SQL
>>   * Bash
>>   * Assembly

> **C/C++**
>> 90% of all Operating System and other language libraries today we use are written in C/C++<br>
    (Even all the background of python runs on C)

> **Python**
>> * Easy to learn
>> * Automating tasks (Interpreted Language)
>> * Wide language used and top trending language
>> * Also used as Backend language in web(FrameWorks: flask, django)

> **HTML**
>> * All the web pages contains HTML so understanding of HTML is necessary
      (Login forms and other data entry methods on the web use HTML forms to get data. Been able to write and interpret HTML, makes it easy for you to identify and exploit weaknesses in the code.)

> **PHP**
>> * PHP is the most popular Backend language for web
      (Most websites today are coded in PHP)
      (But increasing in trends people are moving to new language like python(django) and JavaScript(Node))

> **JavaScript**
>> * Almost all websites use frontend as JavaScript
>> * There is a most famous exploit called (CROSS SITE SCRIPTING)
>> * javascript is used as both frontend and backend language now-a-days(FrameWorks:Node)

> **SQL**
>> * Everything in the internet is strored in databases
>> * SQL is the language of the databases
      (For talking with databases SQL knowledge is necessary)
>> * increasing in trends developers are choosing new database technologies like
>>> * postgresql
>>> * NOSQL...
>> * Well known popular attack known as SQL Injection
>> * As it is a client side language we are able to perform client side attacks using JS

> **Bash**
>> * Most Ethical Hackers use linux Distributions
>> * Linux terminal provides programming on kernal
>> * for writing terminal code BASH scripting is used
>> * For automating daily tasks Bash can be used

>**Assembly**
>> * For attacking at processor level Assembly language is important
>> * As processor can understand Assembly language only


### Computer Networking

> 1. One should how data is being transferred from one device to another device<br>
    (so that we can manipulate and can perform man in the middle attacks)<br>
    (As a client we make requests to the server and server responds back with a response inorder to understand all this phenomenon Networking is necessary)
> 2. Basic knowledge of protocols and ports are important<br>
    (Computer Networks is the Backbone of the internet to understand things which are going on the internet networking knowledge is mandatory as internet follows those protocols we can find vulnerabilities and exploit them)
> 3. During Information Gathering phase one should able to know open/closed ports os and other details of the target System/Server<br>
    (For System scanning and knowledge of ports networking knowledge is necessary)<br>
    (Scanning is a set of procedures for identifying live hosts, ports & services)<br>
> 4. Sniffing packets<br>
    (Monitering & capturing packets through a given network)<br>
    (Example: phone tapping)<br>
> 5. Understanding and performing attacks like DoS<br>
    (Denial of Service is an attack performed at the physical layer which makes the Server busy by reaching maximum number of user or by exhausting band width All the above stuff is networking concepts) 


### Linux Distributions

> 1. Most web servers are run on the Linux operating system.
       (As an ethical hacker, one of your most frequent roles will be to gain access to the server. This automatically makes Linux a must-have skill for ethical hacking. You should have an in-depth knowledge and understanding of this operating system.)
> 2. Some of the linux destros for hackers are
>> * Kali Linux
>> * BackBox
>> * Parrot Security OS
>> * BlackArch


## Phases of Ethical Hacking
> * **Information gathering(Reconnaissance)**
>> * Active
>> * Passive
>>> * Information Gathering by googling or from social media
>>> * hunter.io : website for gathering gmails from a specific organisation
>>> * WappAnalyser : chrome extension which gives the details of a website
>>> * Website Enumeration : https://www.virustotal.com/
> * **Scanning & Enumeration**
>> * nmap
> * **Gaining Access**
>> * Exploitation
> * **Maintaining Access**
> * **Covering Tracks**


## Information gathering(Reconnaissance)
> ### What is Reconnaissance?
>> * Gathering information about the target to exploit 

> ### Passive Footprinting 
>> * Gaining public information about the target
    
> ### Active Footprinting
>> * Social engineering and human interaction 
    
### Vulnerability Research 
> * National Vulnerability Database 
>> * http://www.nvd.nist.gov
> * CVE
>> * http://www.cvedetails.com
> * Securiteam
>> * http://www.securiteam.com

### Nmap
> * open-source tool 
> * used for port scanning 
>> - finding live targets
>> - open ports (services) 
>> - Operating System 
> * www.nmap.org

### Ports
> * 1 - 65535 ports available 
> * some commonly used ports
>> - 21 ftp
>> - 22 ssh
>> - 80 http
>> - 443 https
>> - 3306 sql .... 

## OpenWebApplicationSecurityProject TOP10

> Once again lets look into the Famous Attacks related WEBAPPS
>> - https://owasp.org/www-project-top-ten/

> Top 10 Web Application Security Risks
>> 1. Injection(SQL, NoSQL)
>>> - https://owasp.org/www-project-top-ten/OWASP_Top_Ten_2017/Top_10-2017_A1-Injection
>> 2. Broken Authentication
>> 3. Sensitive Data Exposure
>>> - protecting details like passwords creditcard details, API keys
>>> - Ensure to remove them while uploading/sharing to others or opensource
>>> - opensources like github, bitbucket, codepen etc
>> 4. XML External Entities(XXE)
>> 5. Broken Access Control
>> 6. Security Misconfiguration
>> 7. Cross-Site Scripting(XSS)
>> 8. Insecure Deserialization
>> 9. Using Components with Known Vulnerabilities
>> 10. Insufficient Logging & Monitering


## Tools
* Burp Suite
* OWASP ZAP
* Nmap
* Wire Shark
* SQL Map
* Wfuzz
* Metasploit 
* aircrack-ng
* nikto
* webappanalyzer(chromeextension)


> ### Nmap
>> * Used to find open ports and os

> ### Metasploit
>> * Used for injecting/launching attacks on the target
    
> ### aircrack-ng
>> * Suite of tools used for wireless pentesting
    
> ### Wireshark
>> * Used to intercept network traffic 
    
    

addons
categorize as
footprinting
exploiting 
.....
