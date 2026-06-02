# Tool Familiarisation

## 1. Wireshark

### Purpose

Wireshark is a network protocol analyser used to capture and inspect network packets in real time.

### Features

* Packet Capture
* Protocol Analysis
* Traffic Monitoring
* Network Troubleshooting

### Observation

Network packets, including TCP, UDP, ARP, DNS, and HTTPS traffic, were successfully captured and analysed.

---

## 2. Nmap

### Purpose

Nmap is a network scanning tool used to discover hosts, services, and open ports.

### Commands Used

```bash
nmap -sV <target-ip>
```

### Features

* Host Discovery
* Port Scanning
* Service Detection
* Security Assessment

### Observation

Nmap identified open ports and running services on the target machine.

---

## 3. Burp Suite

### Purpose

Burp Suite is a web application security testing platform.

### Features

* HTTP Request Interception
* Web Traffic Analysis
* Vulnerability Testing
* Request Modification

### Observation

HTTP requests and responses between the browser and web server were intercepted and analyzed.

---

## 4. Netcat

### Purpose

Netcat is a networking utility used for communication and debugging.

### Features

* TCP Connections
* UDP Connections
* Port Testing
* Data Transfer

### Commands Used

Listener:

```bash
nc -lvnp 4444
```

Connection:

```bash
nc <target-ip> 4444
```

### Observation

A network connection was established between the attacker and target machines.

---

## Conclusion

The tools provided practical experience in packet analysis, network scanning, web application testing, and network communication. These tools are widely used by cybersecurity professionals for security assessments and penetration testing.
