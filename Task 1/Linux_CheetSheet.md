# Linux Cheat Sheet

## Cybersecurity & Ethical Hacking Internship - Task 1

---

# 1. System Information

Display system information:

```bash
uname -a
```

Display Linux distribution:

```bash
cat /etc/os-release
```

Check current user:

```bash
whoami
```

Check hostname:

```bash
hostname
```

---

# 2. Navigation Commands

Display current directory:

```bash
pwd
```

List files and folders:

```bash
ls
```

Detailed listing:

```bash
ls -la
```

Change directory:

```bash
cd directory_name
```

Move to parent directory:

```bash
cd ..
```

Move to home directory:

```bash
cd ~
```

---

# 3. File Management

Create a file:

```bash
touch file.txt
```

Create a directory:

```bash
mkdir folder_name
```

Copy files:

```bash
cp source.txt destination.txt
```

Move files:

```bash
mv file.txt folder/
```

Delete files:

```bash
rm file.txt
```

Delete directories:

```bash
rm -r folder_name
```

Display file contents:

```bash
cat file.txt
```

---

# 4. File Permissions

View permissions:

```bash
ls -l
```

Change permissions:

```bash
chmod 777 file.txt
```

Permission Breakdown:

* 7 = Read + Write + Execute
* 6 = Read + Write
* 5 = Read + Execute
* 4 = Read Only

Example:

```bash
chmod 755 script.sh
```

Change ownership:

```bash
sudo chown user:user file.txt
```

---

# 5. User Management

Create new user:

```bash
sudo adduser username
```

Switch user:

```bash
su username
```

Display current user:

```bash
whoami
```

---

# 6. Package Management (APT)

Update package repository:

```bash
sudo apt update
```

Upgrade packages:

```bash
sudo apt upgrade
```

Install package:

```bash
sudo apt install package_name
```

Remove package:

```bash
sudo apt remove package_name
```

Search package:

```bash
apt search package_name
```

---

# 7. Networking Commands

Show IP Address:

```bash
ip a
```

Alternative:

```bash
ifconfig
```

Ping host:

```bash
ping google.com
```

Display routing table:

```bash
route -n
```

Display active network connections:

```bash
netstat -tulnp
```

DNS lookup:

```bash
nslookup google.com
```

Trace route:

```bash
traceroute google.com
```

---

# 8. Process Management

Display running processes:

```bash
ps aux
```

Real-time process monitoring:

```bash
top
```

Terminate process:

```bash
kill PID
```

Force terminate process:

```bash
kill -9 PID
```

---

# 9. Disk Usage

Check disk space:

```bash
df -h
```

Check directory size:

```bash
du -sh folder_name
```

---

# 10. Compression Commands

Create ZIP archive:

```bash
zip archive.zip file.txt
```

Extract ZIP archive:

```bash
unzip archive.zip
```

Create TAR archive:

```bash
tar -cvf archive.tar folder/
```

Extract TAR archive:

```bash
tar -xvf archive.tar
```

---

# 11. Nmap Commands

Basic Scan:

```bash
nmap target_ip
```

Service Version Detection:

```bash
nmap -sV target_ip
```

Operating System Detection:

```bash
nmap -O target_ip
```

Scan All Ports:

```bash
nmap -p- target_ip
```

Example:

```bash
nmap -sV 192.168.174.129
```

---

# 12. Wireshark

Start Wireshark:

```bash
wireshark
```

Purpose:

* Packet Capture
* Network Monitoring
* Protocol Analysis

Common Protocols:

* TCP
* UDP
* DNS
* HTTP
* HTTPS
* ARP

---

# 13. Burp Suite

Launch Burp Suite:

```bash
burpsuite
```

Uses:

* HTTP Request Interception
* Web Security Testing
* Traffic Analysis

---

# 14. Netcat

Start Listener:

```bash
nc -lvnp 4444
```

Connect to Target:

```bash
nc <target_ip> 4444
```

Example:

```bash
nc 192.168.174.129 4444
```

Uses:

* Port Testing
* Network Communication
* Debugging

---

# 15. OpenSSL Commands

Generate MD5 Hash:

```bash
echo "Apex Planet" | md5sum
```

Generate SHA256 Hash:

```bash
echo "Apex Planet" | sha256sum
```

Encrypt File:

```bash
openssl enc -aes-256-cbc -salt -in file.txt -out encrypted.enc
```

Decrypt File:

```bash
openssl enc -aes-256-cbc -d -in encrypted.enc -out decrypted.txt
```

---

# 16. Useful Cybersecurity Commands

Find files:

```bash
find / -name filename
```

Search text inside files:

```bash
grep "text" file.txt
```

Display command manual:

```bash
man command
```

Display command help:

```bash
command --help
```

Check open ports:

```bash
ss -tuln
```

---

# Learning Outcome

This cheat sheet covers essential Linux commands used in cybersecurity, penetration testing, networking, system administration, and security analysis. It serves as a quick reference for Linux operations performed during Task 1 of the Cybersecurity & Ethical Hacking Internship.

---

Prepared By:
Rajat Desai

Cybersecurity & Ethical Hacking Internship
