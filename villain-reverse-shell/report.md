# Villain Framework Reverse Shell Report

## ⚙️ Setup Info
- Payload: windows/reverse_tcp/powershell
- LHOST: 192.168.1.100
- LPORT: 4444

## 🔁 Payload Delivery Method
The payload was delivered to the target VM by hosting a malicious PowerShell script on a simple HTTP server. On the target machine, the payload was executed via a PowerShell command that downloaded and ran the script, establishing a reverse TCP connection back to the Kali Linux machine running Villain Framework.
## 🖥️ Captured Info
- Hostname: LAPTOPOFPOWER
- IP Address: 192.168.1.105
- User: Samuel Joseph 

## 🔎 Enumeration Performed
```powershell
whoami
ipconfig
systeminfo