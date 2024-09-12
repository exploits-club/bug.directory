tags: #pwn2own #car_hacking #stack_overflow
original link: [From Pwn2Own Automotive: Taking Over the Autel Maxicharger](https://www.zerodayinitiative.com/blog/2024/8/22/from-pwn2own-automotive-taking-over-the-autel-maxicharger?ref=blog.exploits.club)  
newsletter link: [exploits.club Weekly Newsletter 36 - Regex Fuzzing, C++ Metadata, Kernel Streaming, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-36-regex-fuzzing-c-metadata-kernel-streaming-and-more/) 

---
## Exploits Club Summary:
> A short post from ZDI which briefly touches on two vulnerabilities identified in the Autel Maxicharger firmware during Pwn2Own automotive earlier this year. The **first bug was a straightforward overflow in BLE message parsing, and the second was a hardcoded backdoor in the WiFi authentication.** The post does a bit of patch diffing to show the introduced fixes but doesn't touch on anything related to exploitation. 