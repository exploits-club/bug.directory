tags: #linux #kernel #lpe
original link: [SSD Advisory: Linux Kernel taprio OOB](https://ssd-disclosure.com/ssd-advisory-linux-kernel-taprio-oob/?ref=blog.exploits.club)
newsletter link:  [exploits.club Weekly Newsletter 36 - Regex Fuzzing, C++ Metadata, Kernel Streaming, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-36-regex-fuzzing-c-metadata-kernel-streaming-and-more/)

---
## Exploits Club Summary:
> We have covered a few of the bugs from TyphoonPWN 2024, and this week we got a write-up for a Linux LPE entry. **The vulnerability manifests from a logic bug, eventually leading to an OOB access.** An attacker **can pass an arbitrary `mqprio` to the kernel,** which begs the question...**what can we do with that?** The post walks through a code path **where the the value will be propagated for "direct PC-control", so that's pretty cool.** As usual with [SSD Advisories](https://ssd-disclosure.com/?ref=blog.exploits.club), **complete exploit code** is included.