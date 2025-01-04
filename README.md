# BlackArch Linux Commands Reference

A comprehensive list of BlackArch Linux commands, organized by sections for easy reference.

---

## Table of Contents
- [System Information](#system-information)
- [Package Management](#package-management)
- [Networking](#networking)
- [Web Application Testing](#web-application-testing)
- [Wireless Testing](#wireless-testing)
- [Cryptography Tools](#cryptography-tools)
- [Forensics](#forensics)
- [Reverse Engineering](#reverse-engineering)
- [Exploitation](#exploitation)
- [Maintained by](#maintained-by)

---

## System Information
Commands to gather system details and manage system-level tasks.

- `uname -a` - Display kernel version and system information.
- `lscpu` - Show CPU architecture details.
- `lsblk` - List information about block devices.
- `df -h` - Display disk usage in a human-readable format.
- `free -h` - Show memory usage.

---

## Package Management
Commands to manage packages in BlackArch Linux.

- `sudo pacman -S <package>` - Install a package.
- `sudo pacman -R <package>` - Remove a package.
- `sudo pacman -Syu` - Update the system and all packages.
- `blackman -S <tool>` - Install a BlackArch tool.
- `blackman -Sg <group>` - Install all tools from a specific group.

---

## Networking
Commands for network analysis and testing.

- `nmap <target>` - Perform network scanning on the target.
- `tcpdump -i <interface>` - Capture network packets on a specific interface.
- `wireshark` - Graphical network protocol analyzer.
- `ip a` - Show IP addresses and network interfaces.
- `netstat -tulnp` - Display open ports and associated services.

---

## Web Application Testing
Commands and tools for testing web applications.

- `sqlmap -u <URL>` - Test for SQL injection vulnerabilities.
- `wpscan --url <URL>` - Scan WordPress for vulnerabilities.
- `dirb <URL>` - Brute-force directories and files on a web server.
- `nikto -h <host>` - Perform a web server vulnerability scan.
- `arachni <URL>` - Comprehensive web application scanner.

---

## Wireless Testing
Tools and commands for wireless network security testing.

- `airmon-ng start <interface>` - Start monitor mode on a wireless interface.
- `airodump-ng <interface>` - Capture wireless packets.
- `aireplay-ng -0 5 -a <BSSID> <interface>` - Deauthenticate clients from an access point.
- `aircrack-ng <file>` - Crack WPA/WEP passwords from capture files.
- `kismet` - Wireless network and device detector.

---

## Cryptography Tools
Tools for encryption, decryption, and cryptographic analysis.

- `hashcat -m <mode> -a <attack_mode> <hashfile>` - Password cracking with GPU acceleration.
- `gpg --encrypt --recipient <email> <file>` - Encrypt files using GPG.
- `openssl enc -aes-256-cbc -in <file> -out <encrypted_file>` - Encrypt a file with AES.
- `john --wordlist=<wordlist> <hashfile>` - Password cracking with John the Ripper.
- `cryptsetup luksOpen <device> <name>` - Open a LUKS-encrypted device.

---

## Forensics
Commands and tools for digital forensic analysis.

- `foremost -i <image>` - Recover files based on headers.
- `sleuthkit` - Suite of tools for forensic analysis.
- `autopsy` - Graphical interface for forensic investigations.
- `volatility -f <memory_dump>` - Analyze memory dumps.
- `strings <file>` - Extract readable strings from a binary.

---

## Reverse Engineering
Commands and tools for reverse engineering binaries.

- `gdb <binary>` - Debug binaries.
- `radare2 <binary>` - Powerful reverse engineering framework.
- `objdump -d <binary>` - Disassemble binaries.
- `strings <binary>` - Extract human-readable strings from binaries.
- `ltrace ./<binary>` - Trace library calls during execution.

---

## Exploitation
Tools for identifying and exploiting vulnerabilities.

- `metasploit` - Comprehensive exploitation framework.
- `exploitdb -s <search_term>` - Search for exploits in the Exploit-DB database.
- `beef-xss` - Browser Exploitation Framework.
- `msfvenom -p <payload> -o <output_file>` - Create payloads.
- `setoolkit` - Social engineering toolkit.

---

## Maintained by

This document was created and maintained by **Chris Cruz**, a cybersecurity specialist and expert in ethical hacking, vulnerability analysis, and incident response. Chris has extensive experience with BlackArch Linux and Arch Linux, empowering students, ethical hackers, and professionals in government and enterprise sectors to understand and mitigate cyber threats. 

Passionate about promoting ethical hacking practices and sharing knowledge, Chris aims to help others develop a deep understanding of cybersecurity tools and methodologies.
