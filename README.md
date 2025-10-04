# Cyber Security Internship Task 8  
**Topic: Identify and Remove Suspicious Browser Extensions — VPN Hands-on Lab**

---

## Objective

Understand the role of VPNs in protecting privacy and securing communication by setting up and testing a free VPN service. Analyze changes in IP address, examine network speed impact, and summarize important VPN concepts.

---

## Task Deliverables

- Step-by-step process of VPN setup
- Screenshots: IP address before and after VPN, speed test results
- Research on VPN encryption, protocols, privacy features, limitations
- Interview Q&A

---

## VPN Setup & Testing Steps

1. **Select a Free VPN Service**
   - Used ProtonVPN Free Tier

2. **Account Creation**
   - Registered at ProtonVPN’s website using email.

3. **Download & Install VPN Client**
   - Downloaded ProtonVPN application for Windows and completed the installation.

4. **Connect to VPN**
   - Connected to a Tokyo, Japan server via the ProtonVPN app.

5. **Verify IP Change**
   - Before VPN: IP shown as local Indian address.
   - After VPN: IP changed to a Tokyo, Japan-based address (see screenshots).

6. **Test & Compare Network Speed**
   - Before VPN: Download = 18.56 Mbps, Upload = 18.18 Mbps, Ping = 84 ms  
   - With VPN: Download = 4.05 Mbps, Upload = 7.08 Mbps, Ping = 1 ms  
   - (Speeds measured using Speed.is. See screenshots.)

7. **Research on VPN Technology**
   - Explored encryption protocols (OpenVPN, WireGuard, IKEv2/IPSec)
   - Studied benefits and limitations of VPNs

---

## Screenshots

- ![IP address with VPN active]
- ![Speed test without VPN]
- ![IP address with VPN off]
- ![Speed test with VPN]
---

## Key Findings

- VPN successfully masked real IP, assigning a foreign location (Tokyo, Japan)
- Noticeable drop in internet speed while connected to VPN
- VPN encrypts internet traffic, securing data from local ISP and attackers
- Free VPNs may offer limited locations, speeds, and session times

---

## Interview Questions & Answers

**Q1: What is a VPN?**  
A Virtual Private Network (VPN) is a technology that creates a secure and encrypted connection over a less secure network, such as the Internet. It masks the user's IP address and encrypts all traffic passing through the connection.

**Q2: How does a VPN protect privacy?**  
By encrypting internet traffic and masking the original IP address, a VPN prevents snooping by ISPs, hackers, and public Wi-Fi administrators. It routes data through a secure tunnel to a remote server.

**Q3: Difference between VPN and proxy?**  
- VPN encrypts all device traffic at the OS/network level, while a proxy only routes specific application traffic (e.g. browser).
- VPN provides stronger privacy and encryption; a proxy does not encrypt traffic.

**Q4: What is encryption in VPN?**  
Encryption is the process of converting readable data into a coded format. VPNs use protocols like OpenVPN and WireGuard with AES-256 encryption to ensure only authorized parties can read the data.

**Q5: Can VPN guarantee complete anonymity?**  
No. VPNs provide significant privacy improvement, but do not guarantee total anonymity, since services can still track via cookies, browser fingerprinting, and account logins.

**Q6: What protocols do VPNs use?**  
Common VPN protocols include OpenVPN, IKEv2/IPSec, L2TP/IPSec, WireGuard, and PPTP.

**Q7: What are some VPN limitations?**  
- Can slow down internet speed due to encryption overhead
- Free servers may be overloaded, limited in locations
- Some websites and services block VPN IPs
- VPN does not block all forms of tracking (e.g., cookies, DNS leaks)

**Q8: How does a VPN affect network speed?**  
Network speed may decrease because data takes a longer route and encryption adds latency. The extent depends on server distance/load and protocol efficiency.

---

## Useful References

- ProtonVPN Free Setup: [protonvpn.com/free-vpn](https://protonvpn.com/free-vpn)
- VPN Encryption Explained: [purewl.com/vpn-encryption-explained-a-quick-overview](https://www.purewl.com/vpn-encryption-explained-a-quick-overview/)
- Proxy vs. VPN: [checkpoint.com/cyber-hub/network-security/what-is-network-security/proxy-vs-vpn-4-key-differences/](https://www.checkpoint.com/cyber-hub/network-security/what-is-network-security/proxy-vs-vpn-4-key-differences/)

---

## Conclusion

This task demonstrates hands-on VPN setup, validates changes in IP/geolocation and network speed, and covers essential VPN concepts for cybersecurity interviews.
