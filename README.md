# wireshark--http--vshttps-
## Objective 
A beginner friendly project showing the difference between insecure HTTP traffic and encrypted HTTPS traffick using wireshark .
## Why it matters
HTTP sends data in plain text, making it easy for attackers to intercept.HTTPS encrypts traffic,protecting cridentials and user privacy.This project demonstrates the importance of secure communication.
## Tools used
-Wireshark
-kali linux vm 
-Test website with HTTP/HTTPS login

## Steps 
1.captured HTTP traffic using filter `http`.
2 Logged into a test site with dummy cridentials.
3.Observed cridentials in plain text.
4 Captured HTTPS traffic using ilter`tls`.
5 Logged into the same site.
6.Observed encrypted packets
## Findings
-HTTP exposes sensitive data directly in packets.
-HTTPS encrypts data making it unreadable to attackers
## Conclusion
This project highlights why HTTPS is critical for protecting sensitive data.
