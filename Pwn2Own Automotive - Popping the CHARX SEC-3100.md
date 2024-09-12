tags: #car_hacking #pwn2own #cop
original link: [Pwn2Own Automotive: Popping the CHARX SEC-3100](https://blog.ret2.io/2024/07/24/pwn2own-auto-2024-charx-exploit/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 31](https://blog.exploits.club/exploits-club-weekly-newsletter-31/)

---
## Exploits Club Summary:
> Last week, we covered [Ret2 Systems'](https://ret2.io/?ref=blog.exploits.club) blog detailing the discovery of **two vulnerabilities in the CHARX SEC-3100 used at Pwn2Own Automotive.** This week, the team followed up with details on exploitation. The write-up starts with a bit of a recap, explaining how the **primitive gives the ability to traverse a freed list.** It then jumps into how they can **control a node because iterating over the freed list actually traverses the tcache bin.** The post then touches on populating the tcache before talking about the last obstacle in the exploit - ASLR. A**fter a pretty cool "smart-bruteforce", the post rounds out with an explanation of the COP Chain before giving a step-by-step walkthrough of the exploit's flow to put everything together.** 



---
backlinks: 
[[Pwn2Own Automotive - CHARX Vulnerability Discovery]]