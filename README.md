# Atom-Bomb
DDoS Tool that supports:
  * DNS Amplification (Domain Name System)
  * NTP Amplification (Network Time Protocol)
  * SNMP Amplification (Simple Network Management Protocol)
  * SSDP Amplification (Simple Service Discovery Protocol)

![](https://i.imgur.com/wnHDni0.png)

Donation would be much appreciated: 14pB8q646XbCS9s6jKzsCavqhnzTCv3489
# Requierments
 * OS Supports raw sockets
 * Python 2.7

# Usage
```
          _                  ____                  _     
     /\  | |                |  _ \                | |    
    /  \ | |_ ___  _ __ ___ | |_) | ___  _ __ ___ | |__  
   / /\ \| __/ _ \| '_ ` _ \|  _ < / _ \| '_ ` _ \| '_ \ 
  / ____ \ || (_) | | | | | | |_) | (_) | | | | | | |_) |
 /_/    \_\__\___/|_| |_| |_|____/ \___/|_| |_| |_|_.__/ 
                                                         
                                                         
	https://github.com/SMCbite1024/Atom-bomb
	   https://twitter.com/SMCbite1024

Usage: 
atombomb.py target.com [options]        # DDoS
atombomb.py benchmark [options]         # Calculate AMPLIFICATION factor


Options:
  -h, --help            show this help message and exit
  -d FILE:FILE|DOMAIN, --dns=FILE:FILE|DOMAIN
                        DNS Amplification File and Domains to Resolve (e.g:
                        dns.txt:[evildomain.com|domains_file.txt]
  -n FILE, --ntp=FILE   NTP Amplification file
  -s FILE, --snmp=FILE  SNMP Amplification file
  -p FILE, --ssdp=FILE  SSDP Amplification file
  -t N, --threads=N     Number of threads (default=1)
```
