## 🛡️ Network Packet Sniffer

This repository contains **Task 1** of the **CodeAlpha CyberSecurity Internship**, developed by **Himanshu Dixit**.  
The task involves creating a simple **Network Packet Sniffer** using Python and the `scapy` library.

---

## 📁 Project Structure

CodeAlpha_CyberSecurity/ ├── Task_1/                # Contains the source code │   └── sniffer.py         # Python script to sniff and analyze network packets ├── Output_Task_1/        # Contains the output result of a sample packet sniffing session │   └── output.txt

---

## 🧠 Features

- Captures network packets in real-time.
- Extracts and displays:
  - Source and Destination IP addresses
  - Protocol type (TCP, UDP, ICMP, etc.)
  - Source and Destination ports
  - Payload size in bytes
- Identifies and classifies IP layer protocols.

---

## 🚀 Getting Started

### 🔧 Requirements

Make sure you have the following installed:

- Python 3.x
- `scapy` library

Install scapy using pip:

```bash
pip install scapy


---

🧪 How to Run

Run the script with administrator/root privileges (required for packet sniffing):

sudo python3 sniffer.py

Once running, the script will continuously print packet information until you press Ctrl + C to stop it.


---

🖥️ Sample Output

==============================
Source IP         : 20.42.65.94  
Destination IP    : 192.168.29.142  
Protocol          : TCP  
Source Port       : 443  
Destination Port  : 65182  
Payload Length    : 32 bytes


---

📌 Notes

You may need to run the script in a terminal with elevated privileges (admin/root).

Use responsibly. Network sniffing should only be performed on networks you own or have permission to monitor.



---

👨‍💻 Author

Himanshu Dixit
Intern at CodeAlpha


---

📄 License

This project is licensed for educational purposes under the MIT License.

---
