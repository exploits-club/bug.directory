tags: #ctf #kvm #hypervisor
original link: [corCTF 2024: trojan-turtles writeup](https://zolutal.github.io/corctf-trojan-turtles/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 32 - Popping Basebands, Pwnie Nominated PrivEscs, The Compiler Landscape, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-32-2/)

---
## Exploits Club Summary:
> We love a good CTF write-up and this post from [@zolutal](https://x.com/zolutal?ref=blog.exploits.club) is just that. The [Shellphish](https://shellphish.net/?ref=blog.exploits.club) member detailed his solution for trojan-turtles, a **KVM challenge featured in corCTF 2024**. The write-up begins with an o**verview of KVM, providing a great primer for those unfamiliar**. It then details the solution itself, starting **with a diff of the two provided kernel modules, identifying the backdoor, and hitting the vulnerable code path.** The post ends with a deep-dive on exploitation, in which the **Extended Page Table is modified to map the host's address space into the guest.**