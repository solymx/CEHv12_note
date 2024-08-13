
# Problem: Run the nmap and need the least amount of noise

- -T0 makes the least noise.
- -T5 the most noise.

# Some tool intro

- Bluto is a DNS penetration testing tool based on Python
- Cain and Abel (often abbreviated to Cain) was a password recovery tool for Microsoft Windows
- Nikto is a free software command-line vulnerability scanner that scans web servers for dangerous
files/CGIs
- CHNTPW 是一個用來重新設定Windows NT登入密碼的軟體工具，在Linux環境下修改或是清除本機密碼
- Kismet is a network detector, packet sniffer, and intrusion detection system for 802.11 wireless LANs

# 讓醫療資料保密不安全的法律
- HIPAA/PHI
# nmap use

- `-sV`: Probe open ports to determine service/version info
- `-F` : (Fast (limited port) scan)，如果題目問要最快速的話
- `-oX` <filespec> : Requests that XML output be directed to the given filename.

# 攻擊 DES

- meet-in-the-middle attack (MITM) : 這是已知明文攻擊，針對加解密是按照順序進行的算法，可以透過其作攻擊

