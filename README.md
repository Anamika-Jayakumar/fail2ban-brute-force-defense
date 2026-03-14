# Fail2Ban Brute Force Attack Prevention

This project demonstrates how a brute-force attack against an FTP server can be detected and automatically blocked using Fail2Ban.

## Objective
Simulate a brute-force login attack using Metasploit and protect the FTP service using Fail2Ban.

## Tools Used
- Kali Linux
- Metasploit Framework
- Fail2Ban
- vsftpd (FTP server)
- iptables firewall

## Attack Simulation
Metasploit was used to perform repeated login attempts against the FTP service using invalid credentials.

## Defense Mechanism
Fail2Ban monitors log files and detects multiple failed login attempts.

When the retry limit is exceeded, Fail2Ban automatically blocks the attacker's IP address using iptables.

## Results
- Attack attempts were detected successfully
- Attacker IP was automatically banned
- System was protected from continuous login attempts

## Skills Demonstrated
- Linux security administration
- Brute-force attack simulation
- Log monitoring and analysis
- Intrusion prevention using Fail2Ban
