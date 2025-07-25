# 🕵️‍♂️ Network Sniffer using Python

A lightweight Python-based packet sniffer that captures and analyzes network traffic. This project demonstrates raw socket programming and basic packet inspection techniques.

## 🚀 Features

- Capture real-time network packets
- Parse and display Ethernet, IP, TCP, UDP, and ICMP headers
- Hexdump view of raw packet data
- Console-based interface

## 🧠 Skills Demonstrated

- Raw socket programming in Python
- Understanding of OSI and TCP/IP models
- Binary and hex data parsing
- Network protocol structure (Ethernet, IP, TCP/UDP/ICMP)

## ⚙️ Technologies Used

- Python (v3.6+)
- `socket` module
- `struct` module
- Linux terminal

> Note: This program requires administrative privileges to run.

## 📁 Folder Structure

```

NetworkSniffer\_Python/
├── sniffer.py         # Main packet sniffer script
├── README.md          # Project documentation
└── sample\_output.txt  # Sample output of a capture session

````

## 🔧 How to Run

1. Clone this repository:

```bash
git clone https://github.com/TechHimanshuDixit/NetworkSniffer_Python.git
cd NetworkSniffer_Python
````

2. Run the script with administrative privileges:

```bash
sudo python3 sniffer.py
```

> Use `Ctrl + C` to stop the sniffer.

## 📌 Sample Output

```
Ethernet Frame:
  - Destination: 08:00:27:13:69:77
  - Source:      08:00:27:89:3f:1a
  - Protocol:    0x0800 (IPv4)

IPv4 Packet:
  - Version: 4
  - Header Length: 20 bytes
  - TTL: 64
  - Protocol: TCP
  - Source IP: 192.168.0.105
  - Target IP: 172.217.167.206
```

## 📫 Contact

📧 [himanshudixit2002@gmail.com](mailto:himanshudixit2002@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/himanshudixit2002)
🐙 [GitHub](https://github.com/TechHimanshuDixit)

---

> ⚠️ **Disclaimer:** Use this tool only for educational and authorized testing purposes. Unauthorized network sniffing may be illegal.

