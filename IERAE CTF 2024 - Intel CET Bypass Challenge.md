tags: #mitigation #CET #CTF #stack_overflow 
original link:  [IERAE CTF 2024 - Intel CET Bypass Challenge](https://gist.github.com/sroettger/fe66f7eb0cb10a8ebd1454875a7131ea)
newsletter link: [exploits.club Weekly Newsletter 40 - iOS Kernel Exploitation, CET Bypasses, Elgato Hardware Repair, And More](https://blog.exploits.club/exploits-club-weekly-newsletter-40-ios-kernel-exploitation-cet-bypasses-elgato-hardware-repair-and-more/) 

---
## Exploits Club Summary:
> What do you have a straight forward overflow but you need to bypass CET? Well that was the question posed by the Intel CET Bypass Challenge written by [@hugeh0ge](https://x.com/hugeh0ge) for IERAE CTF. [@\_tsuro](https://x.com/_tsuro) decided  to try his hand at answering that question, and lucky for us, decided to document his solution. The post talks through the approach to bypassing CET and some of the other solutions used in the challenge, both intended and unintended. It then talk through his, easier solution which involved a call to `signal` to re-run the main function inside a signal handler. The post then talks through the shortcomings of CET, and potential ways this bypass could have been mitigated.  