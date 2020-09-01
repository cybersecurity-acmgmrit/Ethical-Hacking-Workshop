# Network Mapper
***

##### NOTE: run jupyter notebook as a root user (python3 -m notebook --allow-root)


> Nmap is a network scanner used to find...
>> * live hosts in a network
>> * open/closed ports ( Services offered by a host ) [ port number, protocol, service name, state ]
>> * Versions of services running at different ports
>> * Operating System of the Host
>> * Nmap scripts


### Finding Live Host
> $ nmap -sn < target >
>> * Finds live hosts in a network


### Version scan
> $ nmap -sV < target >

> * It is very useful because there is a chance to find unpatched vulnerable versions so that we can take a chance of them

> * You can increase or decrease the amount of probes to use during version detection by
changing the intensity level of the scan with the argument --version-intensity [0-9] ,
as follows:
>> $ nmap -sV --version-intensity 9 < target >


### OS Detection
> $ nmap -O < target >

##### NOTE:
> * If OS scan fails we can explicitly force nmap by adding --osscan-guess argument
>> $ nmap -O --osscan-guess < target >

> * To launch only OS scan explicitly by adding --osscan-limit argument
>> $ nmap -O --osscan-limit < target >


### Aggressive detection mode
> * Nmap has a special flag to activate aggressive detection, namely -A . Aggressive mode
enables...
>> * OS detection ( -O )
>> * version detection ( -sV )
>> * script scanning ( -sC )
>> * traceroute ( --traceroute )
> * This mode sends a lot more probes, and **it is more likely to be detected**, but
provides a lot of valuable host information

>> $ nmap -A < target >


## Nmap Scripting Engine

**NSE scripts are divided into the following categories:**
>**auth:** This category is for scripts related to user authentication

>**broadcast:** This is a very interesting category of scripts that use broadcast
petitions to gather information

>**brute:** This category is for scripts that help conduct brute-force password
auditing

>**default:** This category is for scripts that are executed when a script scan is
executed ( -sC )

>**discovery:** This category is for scripts related to host and service discovery.

>**dos:** This category is for scripts related to denial of service attacks

>**exploit:** This category is for scripts that exploit security vulnerabilities

>**external:** This category is for scripts that depend on a third-party service

>**fuzzer:** This category is for NSE scripts that are focused on fuzzing

>**intrusive:** This category is for scripts that might crash something or generate a lot
of network noise; scripts that system administrators may consider intrusive
belong to this category

>**malware:** This category is for scripts related to malware detection

>**safe:** This category is for scripts that are considered safe in all situations

>**version:** This category is for scripts that are used for advanced versioning

>**vuln:** This category is for scripts related to security vulnerabilities


### Syntax
> nmap --script <_script_name_> --script-args <_arguments_> <_target_>

### TCP Scan(full-open scan) Vs SYN scan(half-open scan)(stealth scan)
> **TCP Scan**:
>> * Esatblishes 3 way handshake so it takes more time but gives accurate results
>> * packets are dropeed when firewall is present
>> * nmap -sT <_target_>

> **SYN Scan**:
>> * Full 3 way handshake is not happen here after 2 steps connection is closed. Syn packet is send and when syn-ack(if port is open) or reset(if port is closed) packet is received connection is closed
>> * reduces scan time
>> * can bypass firewall
>> * nmap -sS <_target_>


### Inverse TCP flag scan
**xmas scan**
> * nmap -sX <_target_>

**FYN scan**
> * nmap -sF <_target_>

**NULL scan**
> * nmap -sN <_target_>
