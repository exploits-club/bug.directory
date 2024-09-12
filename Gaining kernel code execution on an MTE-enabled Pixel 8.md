tags: #android #mte #pixel #lpe #mali #gpu
original link:  [Gaining kernel code execution on an MTE-enabled Pixel 8](https://github.blog/2024-03-18-gaining-kernel-code-execution-on-an-mte-enabled-pixel-8/?ref=blog.exploits.club)
newsletter link: [exploits.club Weekly Newsletter 13](https://blog.exploits.club/exploits-club-weekly-newsletter-12-2/)

---
## Exploits Club Summary:
>  If you have been anywhere near X this week, you probably came across this new post from the man, the myth, the legend, [@mmolgtm](https://twitter.com/mmolgtm?lang=en&ref=blog.exploits.club). This time, he is back for some **GPU hacking fun, popping** [**CVE-2023-6241**](https://developer.arm.com/Arm%20Security%20Center/Mali%20GPU%20Driver%20Vulnerabilities?ref=blog.exploits.club#Technical-Specifications) **to gain arbitrary kernel code execution from a malicious application context.** Even better, the post **demonstrates how MTE is completely useless against the bug** because the exploit flow requires no pointer dereferencing, and instead uses the GPU to access physical memory directly. 