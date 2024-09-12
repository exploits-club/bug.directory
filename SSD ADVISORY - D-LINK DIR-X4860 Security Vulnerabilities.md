tags: #iot #auth_bypass #command_injection #d-link #router
original link:  [SSD ADVISORY: D-LINK DIR-X4860 Security Vulnerabilities](https://ssd-disclosure.com/2024/05/14/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 22](https://blog.exploits.club/exploits-club-weekly-newsletter-22/)

---
## Exploits Club Summary:
> Sticking with the IoT bug theme, this SSD advisory demonstrates how to chain **an auth bypass with a command execution to pop a D-Link device**. The auth bypass results from an undocumented parameter which can be used to **generate a PrivateKey based on the known username parameter**. The **command injection results from an attacker controlling the IP address when setting up the Virtual Server settings on the device, which is thrown straight into a `FCGI_popen` function.**