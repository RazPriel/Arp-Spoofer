# Arp-Spoofer
A simple Python-based ARP spoofer that demonstrates how ARP poisoning works.  

## ✨ Features

- Spoofs ARP tables of a target and a router to redirect network traffic.  
- Displays target and router MAC addresses automatically.  
- Runs continuously until stopped by the user.  

## 🛠️ Requirements

- Python 3.x  
- [Scapy](https://pypi.org/project/scapy/)  

Install dependencies:

```bash
pip install scapy
```

## 🚀 Usage (authorized networks only)

1. Clone this repository:

```bash
git clone https://github.com/your-username/arp-spoofer-demo.git
cd arp-spoofer-demo
```

2. Run the script:

```bash
python3 arp_spoofer.py
```

3. Enter the required details when prompted:

```
[+] Enter target IP: 192.168.1.5
[+] Enter router IP: 192.168.1.1
```

4. The script will continuously spoof ARP tables, redirecting traffic between the target and router.  
   Stop it safely with `Ctrl + C`.
