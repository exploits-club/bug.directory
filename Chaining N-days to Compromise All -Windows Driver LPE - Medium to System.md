tags: #lpe #windows #kernel
original link:  [Chaining N-days to Compromise All: Windows Driver LPE: Medium to System](https://medium.com/theori-blog/chaining-n-days-to-compromise-all-part-3-windows-driver-lpe-medium-to-system-12f7821d97bb?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 16](https://blog.exploits.club/exploits-club-weekly-newsletter-16/)

---
## Exploits Club Summary:
> [Theori](https://theori.io/?ref=blog.exploits.club) is back again, this time with the third write-up of their 6 bug N-day full chain. Previously, the team detailed how they compromised the browser and escaped the sandbox. In this post, they continue with the attack chain by **escalating privileges through a logic bug in `mkssrv.sys`**. The vulnerability itself stems from the ability to l**ock a Memory Descriptor List area at an arbitrary address,** "including the **kernel address space from a user application".** The post goes into detail on MDLs, the vulnerability, reaching the code path from userspace, and exploitation. 

---
backlinks:
[[Chaining N-days to Compromise All - Part 1 — Chrome Renderer RCE]]
[[Chaining N-days to Compromise All - Part 2 — Windows Kernel LPE (a.k.a Chrome Sandbox Escape)]]
