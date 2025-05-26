# CyberSecInternTASK-1
Task 1: Scan Your Local Network for Open Ports

Tools Used

- Nmap 7.97: For performing a TCP SYN scan
- Operating System: Windows
- Command Prompt (Admin): For running the scan with administrative privileges

---

Target Information

- Target IP Address: `192.168.27.220`
- Scan Type: TCP SYN Scan (`-sS`), also known as a "half-open" scan
- Output File: `scan_results.txt`

---

Command Used

```bash
nmap -sS 192.168.27.220 -oN scan_results.txt
