# 🚀 SAMMAP

> 🔍 A Python-Based Network Reconnaissance Scanner Built Using Nmap

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-green)
![License](https://img.shields.io/badge/License-Educational-orange)

---

## ✨ Features

✅ Open Port Scanning
✅ Service Detection
✅ Version Detection
✅ Scan Time Tracking
✅ Report Generation
✅ Colorful CLI Banner
✅ Easy to Use

---

## 📂 Project Structure

```text
SamMap/
│
├── sammap.py
├── banner.py
├── requirements.txt
├── README.md
│
└── reports/
    └── report.txt
```

---

## ⚙️ Requirements

* Python 3.x
* Nmap

---

## 📥 Installation

### Kali Linux

```bash
sudo apt update
sudo apt install nmap python3 python3-pip -y

pip3 install python-nmap colorama pyfiglet
```

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/SamMap.git

cd SamMap
```

---

## 🚀 Usage

Run the tool:

```bash
sudo python3 sammap.py
```

Enter Target IP:

```text
Enter Target IP : 192.168.1.1
```

---

## 📊 Example Output

```text
PORT      STATE     SERVICE             VERSION
-----------------------------------------------------
21        open      ftp                 vsftpd 2.3.4
22        open      ssh                 OpenSSH 8.2
80        open      http                Apache httpd 2.4.41
3306      open      mysql               MySQL 5.7
```

---

## 📄 Report Location

After scanning, the report will be saved automatically:

```text
reports/report.txt
```

---

## 🛠 Future Updates

* 🔍 OS Detection
* 🌐 Host Discovery
* 📡 Traceroute
* 📑 HTML Report
* 🎨 Improved UI
* 📈 Scan Statistics

---

## ⚠️ Disclaimer

This tool is intended for:

✅ Learning
✅ Lab Environments
✅ Authorized Security Assessments

❌ Do NOT scan systems or networks without proper permission.

---

## 👨‍💻 Author

**MR.SAM**

⭐ If you like this project, give it a Star on GitHub!

